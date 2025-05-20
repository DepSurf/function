# Function: <code>sum_ranges</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81f6c3a1)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:140
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81f94a26)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81fd0032)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff820b0a6a)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff826b7279)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff826e0f95)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff82896f52)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828aeaf7)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b1e3c)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int sum_ranges(struct range *range, int nr_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff82cd61af)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
**Symbols:**

```
ffffffff82cd61af-ffffffff82cd61d1: sum_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int sum_ranges(struct range *range, int nr_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff82fc2172)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
**Symbols:**

```
ffffffff82fc2172-ffffffff82fc2194: sum_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int sum_ranges(struct range *range, int nr_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff831cc7a9)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
**Symbols:**

```
ffffffff831cc7a9-ffffffff831cc7cb: sum_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int sum_ranges(struct range *range, int nr_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff832ae148)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
**Symbols:**

```
ffffffff832ae148-ffffffff832ae16a: sum_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int sum_ranges(struct range *range, int nr_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff8345f0b6)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
**Symbols:**

```
ffffffff8345f0b6-ffffffff8345f0e2: sum_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff83e820b1)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff836a537c)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff838d53fc)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:133
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff8289fe5b)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff82898020)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b2e1e)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b2e4c)
Location: arch/x86/kernel/cpu/mtrr/cleanup.c:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
</details>
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
</ul>
