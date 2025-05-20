# Function: <code>__static_call_validate</code>

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
void __static_call_validate(void *insn, bool tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff8103fd30)
Location: arch/x86/kernel/static_call.c:47
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:arch_static_call_transform
  - arch/x86/kernel/static_call.c:arch_static_call_transform
```
**Symbols:**

```
ffffffff8103fd30-ffffffff8103fd96: __static_call_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __static_call_validate(void *insn, bool tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff810416c0)
Location: arch/x86/kernel/static_call.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:arch_static_call_transform
  - arch/x86/kernel/static_call.c:arch_static_call_transform
```
**Symbols:**

```
ffffffff810416c0-ffffffff81041731: __static_call_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __static_call_validate(void *insn, bool tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/static_call.c (0)
Location: arch/x86/kernel/static_call.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:arch_static_call_transform
  - arch/x86/kernel/static_call.c:arch_static_call_transform
```
**Symbols:**

```
ffffffff81047950-ffffffff810479dd: __static_call_validate (STB_LOCAL)
ffffffff81c99cbb-ffffffff81c99cd8: __static_call_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __static_call_validate(void *insn, bool tail, bool tramp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/static_call.c (0)
Location: arch/x86/kernel/static_call.c:70
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:arch_static_call_transform
  - arch/x86/kernel/static_call.c:arch_static_call_transform
```
**Symbols:**

```
ffffffff81050900-ffffffff8105098c: __static_call_validate (STB_LOCAL)
ffffffff81e497de-ffffffff81e497f2: __static_call_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __static_call_validate(u8 *insn, bool tail, bool tramp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff8105dd10)
Location: arch/x86/kernel/static_call.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:arch_static_call_transform
  - arch/x86/kernel/static_call.c:arch_static_call_transform
```
**Symbols:**

```
ffffffff8105dd10-ffffffff8105ddb7: __static_call_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __static_call_validate(u8 *insn, bool tail, bool tramp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff8105f3b0)
Location: arch/x86/kernel/static_call.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:arch_static_call_transform
  - arch/x86/kernel/static_call.c:arch_static_call_transform
```
**Symbols:**

```
ffffffff8105f3b0-ffffffff8105f457: __static_call_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __static_call_validate(u8 *insn, bool tail, bool tramp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff81066460)
Location: arch/x86/kernel/static_call.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:arch_static_call_transform
  - arch/x86/kernel/static_call.c:arch_static_call_transform
```
**Symbols:**

```
ffffffff81066460-ffffffff81066507: __static_call_validate (STB_LOCAL)
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
<code>bool tramp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *insn</code> ➡️ <code>u8 *insn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
