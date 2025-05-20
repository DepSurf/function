# Function: <code>__static_call_transform</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __static_call_transform(void *insn, enum insn_type type, void *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff81c39430)
Location: arch/x86/kernel/static_call.c:14
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:arch_static_call_transform
  - arch/x86/kernel/static_call.c:arch_static_call_transform
```
**Symbols:**

```
ffffffff81c39430-ffffffff81c394f0: __static_call_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __static_call_transform(void *insn, enum insn_type type, void *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff81c2b880)
Location: arch/x86/kernel/static_call.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:arch_static_call_transform
  - arch/x86/kernel/static_call.c:arch_static_call_transform
```
**Symbols:**

```
ffffffff81c2b880-ffffffff81c2b989: __static_call_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __static_call_transform(void *insn, enum insn_type type, void *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff81d49f70)
Location: arch/x86/kernel/static_call.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:arch_static_call_transform
  - arch/x86/kernel/static_call.c:arch_static_call_transform
```
**Symbols:**

```
ffffffff81d49f70-ffffffff81d4a079: __static_call_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __static_call_transform(void *insn, enum insn_type type, void *func, bool modinit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff81f19520)
Location: arch/x86/kernel/static_call.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:__static_call_fixup
  - arch/x86/kernel/static_call.c:arch_static_call_transform
  - arch/x86/kernel/static_call.c:arch_static_call_transform
```
**Symbols:**

```
ffffffff81f19520-ffffffff81f19665: __static_call_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __static_call_transform(void *insn, enum insn_type type, void *func, bool modinit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff820c1010)
Location: arch/x86/kernel/static_call.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:__static_call_fixup
  - arch/x86/kernel/static_call.c:arch_static_call_transform
  - arch/x86/kernel/static_call.c:arch_static_call_transform
```
**Symbols:**

```
ffffffff820c1010-ffffffff820c11e8: __static_call_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __static_call_transform(void *insn, enum insn_type type, void *func, bool modinit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff82144cd0)
Location: arch/x86/kernel/static_call.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:__static_call_fixup
  - arch/x86/kernel/static_call.c:arch_static_call_transform
  - arch/x86/kernel/static_call.c:arch_static_call_transform
```
**Symbols:**

```
ffffffff82144cd0-ffffffff82144eb1: __static_call_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __static_call_transform(void *insn, enum insn_type type, void *func, bool modinit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff822273f0)
Location: arch/x86/kernel/static_call.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:__static_call_fixup
  - arch/x86/kernel/static_call.c:arch_static_call_transform
  - arch/x86/kernel/static_call.c:arch_static_call_transform
```
**Symbols:**

```
ffffffff822273f0-ffffffff822275d1: __static_call_transform (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool modinit</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
