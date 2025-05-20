# Function: <code>patch_retpoline</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int patch_retpoline(void *addr, struct insn *insn, u8 *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8104c550)
Location: arch/x86/kernel/alternative.c:396
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_retpolines
```
**Symbols:**

```
ffffffff8104c550-ffffffff8104c6d9: patch_retpoline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int patch_retpoline(void *addr, struct insn *insn, u8 *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810586e0)
Location: arch/x86/kernel/alternative.c:447
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_retpolines
```
**Symbols:**

```
ffffffff810586e0-ffffffff81058993: patch_retpoline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int patch_retpoline(void *addr, struct insn *insn, u8 *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810597a0)
Location: arch/x86/kernel/alternative.c:561
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_retpolines
```
**Symbols:**

```
ffffffff810597a0-ffffffff81059a57: patch_retpoline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int patch_retpoline(void *addr, struct insn *insn, u8 *bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81060910)
Location: arch/x86/kernel/alternative.c:646
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_retpolines
```
**Symbols:**

```
ffffffff81060910-ffffffff81060bc7: patch_retpoline (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
