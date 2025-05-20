# Function: <code>fpu_clone</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fpu_clone(struct task_struct *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81049820)
Location: arch/x86/kernel/fpu/core.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:arch_dup_task_struct
```
**Symbols:**

```
ffffffff81049820-ffffffff81049920: fpu_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fpu_clone(struct task_struct *dst, long unsigned int clone_flags, bool minimal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/core.c (0)
Location: arch/x86/kernel/fpu/core.c:559
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
```
**Symbols:**

```
ffffffff81e498d7-ffffffff81e498e3: fpu_clone.cold (STB_LOCAL)
ffffffff810533b0-ffffffff810536bb: fpu_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fpu_clone(struct task_struct *dst, long unsigned int clone_flags, bool minimal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81060ce0)
Location: arch/x86/kernel/fpu/core.c:556
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
```
**Symbols:**

```
ffffffff81060ce0-ffffffff810610ac: fpu_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fpu_clone(struct task_struct *dst, long unsigned int clone_flags, bool minimal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810626e0)
Location: arch/x86/kernel/fpu/core.c:556
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
```
**Symbols:**

```
ffffffff810626e0-ffffffff81062aac: fpu_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fpu_clone(struct task_struct *dst, long unsigned int clone_flags, bool minimal, long unsigned int ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81069800)
Location: arch/x86/kernel/fpu/core.c:584
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:copy_thread
```
**Symbols:**

```
ffffffff81069800-ffffffff81069c1a: fpu_clone (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int clone_flags</code>
</li>
<li>
<b>Param added. </b>
<code>bool minimal</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int ssp</code>
</li>
</ul>
</details>
</li>
</ul>
