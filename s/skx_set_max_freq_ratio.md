# Function: <code>skx_set_max_freq_ratio</code>

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
bool skx_set_max_freq_ratio(u64 *base_freq, u64 *turbo_freq, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81069e80)
Location: arch/x86/kernel/smpboot.c:1937
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
```
**Symbols:**

```
ffffffff81069e80-ffffffff81069f4f: skx_set_max_freq_ratio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool skx_set_max_freq_ratio(u64 *base_freq, u64 *turbo_freq, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106bb50)
Location: arch/x86/kernel/smpboot.c:1932
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
```
**Symbols:**

```
ffffffff8106bb50-ffffffff8106bc1f: skx_set_max_freq_ratio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool skx_set_max_freq_ratio(u64 *base_freq, u64 *turbo_freq, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106c800)
Location: arch/x86/kernel/smpboot.c:1928
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
```
**Symbols:**

```
ffffffff8106c800-ffffffff8106c8cf: skx_set_max_freq_ratio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool skx_set_max_freq_ratio(u64 *base_freq, u64 *turbo_freq, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81077800)
Location: arch/x86/kernel/smpboot.c:1935
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
```
**Symbols:**

```
ffffffff81077800-ffffffff810778cf: skx_set_max_freq_ratio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool skx_set_max_freq_ratio(u64 *base_freq, u64 *turbo_freq, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8345d706)
Location: arch/x86/kernel/cpu/aperfmperf.c:188
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
```
**Symbols:**

```
ffffffff8345d706-ffffffff8345d7dd: skx_set_max_freq_ratio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool skx_set_max_freq_ratio(u64 *base_freq, u64 *turbo_freq, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff83e7e530)
Location: arch/x86/kernel/cpu/aperfmperf.c:188
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
```
**Symbols:**

```
ffffffff83e7e530-ffffffff83e7e639: skx_set_max_freq_ratio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool skx_set_max_freq_ratio(u64 *base_freq, u64 *turbo_freq, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff836a1290)
Location: arch/x86/kernel/cpu/aperfmperf.c:188
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
```
**Symbols:**

```
ffffffff836a1290-ffffffff836a1399: skx_set_max_freq_ratio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool skx_set_max_freq_ratio(u64 *base_freq, u64 *turbo_freq, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff838d1340)
Location: arch/x86/kernel/cpu/aperfmperf.c:188
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
```
**Symbols:**

```
ffffffff838d1340-ffffffff838d1449: skx_set_max_freq_ratio (STB_LOCAL)
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
