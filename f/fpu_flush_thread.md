# Function: <code>fpu_flush_thread</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fpu_flush_thread();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/core.c (0)
Location: arch/x86/kernel/fpu/core.c:406
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:flush_thread
```
**Symbols:**

```
ffffffff81c99d95-ffffffff81c99da1: fpu_flush_thread.cold (STB_LOCAL)
ffffffff81049a80-ffffffff81049b9b: fpu_flush_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fpu_flush_thread();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/core.c (0)
Location: arch/x86/kernel/fpu/core.c:742
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:flush_thread
```
**Symbols:**

```
ffffffff81e498e3-ffffffff81e498ef: fpu_flush_thread.cold (STB_LOCAL)
ffffffff810537f0-ffffffff81053981: fpu_flush_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fpu_flush_thread();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81061340)
Location: arch/x86/kernel/fpu/core.c:739
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:flush_thread
```
**Symbols:**

```
ffffffff81061340-ffffffff810613e3: fpu_flush_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fpu_flush_thread();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81062c10)
Location: arch/x86/kernel/fpu/core.c:739
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:flush_thread
```
**Symbols:**

```
ffffffff81062c10-ffffffff81062cb3: fpu_flush_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fpu_flush_thread();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81069d80)
Location: arch/x86/kernel/fpu/core.c:774
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:flush_thread
```
**Symbols:**

```
ffffffff81069d80-ffffffff81069e23: fpu_flush_thread (STB_GLOBAL)
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
