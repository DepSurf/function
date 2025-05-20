# Function: <code>__sysvec_deferred_error</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __sysvec_deferred_error(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055940)
Location: arch/x86/kernel/cpu/mce/amd.c:924
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
**Symbols:**

```
ffffffff81055940-ffffffff81055a02: __sysvec_deferred_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __sysvec_deferred_error(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81054860)
Location: arch/x86/kernel/cpu/mce/amd.c:924
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
**Symbols:**

```
ffffffff81054860-ffffffff810548fc: __sysvec_deferred_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sysvec_deferred_error(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056070)
Location: arch/x86/kernel/cpu/mce/amd.c:924
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
**Symbols:**

```
ffffffff81056070-ffffffff8105610c: __sysvec_deferred_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sysvec_deferred_error(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105ebe0)
Location: arch/x86/kernel/cpu/mce/amd.c:937
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
**Symbols:**

```
ffffffff8105ebe0-ffffffff8105ec76: __sysvec_deferred_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sysvec_deferred_error(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106b010)
Location: arch/x86/kernel/cpu/mce/amd.c:760
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
**Symbols:**

```
ffffffff8106b010-ffffffff8106b0e5: __sysvec_deferred_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sysvec_deferred_error(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107af70)
Location: arch/x86/kernel/cpu/mce/amd.c:760
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
**Symbols:**

```
ffffffff8107af70-ffffffff8107b045: __sysvec_deferred_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sysvec_deferred_error(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107d210)
Location: arch/x86/kernel/cpu/mce/amd.c:756
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
**Symbols:**

```
ffffffff8107d210-ffffffff8107d2e5: __sysvec_deferred_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sysvec_deferred_error(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810846f0)
Location: arch/x86/kernel/cpu/mce/amd.c:806
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:sysvec_deferred_error
```
**Symbols:**

```
ffffffff810846f0-ffffffff810847b0: __sysvec_deferred_error (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
