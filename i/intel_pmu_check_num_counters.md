# Function: <code>intel_pmu_check_num_counters</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pmu_check_num_counters(int *num_counters, int *num_counters_fixed, u64 *intel_ctrl, u64 fixed_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81bc429a)
Location: arch/x86/events/intel/core.c:5395
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81bc429a-ffffffff81bc431c: intel_pmu_check_num_counters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_pmu_check_num_counters(int *num_counters, int *num_counters_fixed, u64 *intel_ctrl, u64 fixed_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81c956f8)
Location: arch/x86/events/intel/core.c:5415
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81c956f8-ffffffff81c95797: intel_pmu_check_num_counters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pmu_check_num_counters(int *num_counters, int *num_counters_fixed, u64 *intel_ctrl, u64 fixed_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81e44a36)
Location: arch/x86/events/intel/core.c:5485
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81e44a36-ffffffff81e44ae3: intel_pmu_check_num_counters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void intel_pmu_check_num_counters(int *num_counters, int *num_counters_fixed, u64 *intel_ctrl, u64 fixed_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:5611
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81011770-ffffffff81011824: intel_pmu_check_num_counters (STB_LOCAL)
ffffffff82050600-ffffffff82050619: intel_pmu_check_num_counters.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void intel_pmu_check_num_counters(int *num_counters, int *num_counters_fixed, u64 *intel_ctrl, u64 fixed_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:5777
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
**Symbols:**

```
ffffffff81010e00-ffffffff81010eb4: intel_pmu_check_num_counters (STB_LOCAL)
ffffffff820cea3a-ffffffff820cea53: intel_pmu_check_num_counters.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void intel_pmu_check_num_counters(int *num_counters, int *num_counters_fixed, u64 *intel_ctrl, u64 fixed_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:5964
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
**Symbols:**

```
ffffffff81016500-ffffffff810165b4: intel_pmu_check_num_counters (STB_LOCAL)
ffffffff821a9295-ffffffff821a92ae: intel_pmu_check_num_counters.cold (STB_LOCAL)
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
