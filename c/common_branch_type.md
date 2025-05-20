# Function: <code>common_branch_type</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81010613)
Location: arch/x86/events/intel/lbr.c:965
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff81011292)
Location: arch/x86/events/intel/lbr.c:985
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff810118f2)
Location: arch/x86/events/intel/lbr.c:1007
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff810120a3)
Location: arch/x86/events/intel/lbr.c:1019
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
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
In arch/x86/events/intel/lbr.c (ffffffff81012861)
Location: arch/x86/events/intel/lbr.c:1019
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81013ce3)
Location: arch/x86/events/intel/lbr.c:1044
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81013a43)
Location: arch/x86/events/intel/lbr.c:1345
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81014c23)
Location: arch/x86/events/intel/lbr.c:1361
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101602c)
Location: arch/x86/events/intel/lbr.c:1361
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101812c)
Location: arch/x86/events/intel/lbr.c:1352
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int common_branch_type(int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/utils.c (ffffffff8100b3b0)
Location: arch/x86/events/utils.c:238
Inline: False
Direct callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
**Symbols:**

```
ffffffff8100b3b0-ffffffff8100b41f: common_branch_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int common_branch_type(int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/utils.c (ffffffff8100ab80)
Location: arch/x86/events/utils.c:238
Inline: False
Direct callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
**Symbols:**

```
ffffffff8100ab80-ffffffff8100abef: common_branch_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int common_branch_type(int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/utils.c (ffffffff81010300)
Location: arch/x86/events/utils.c:239
Inline: False
Direct callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
**Symbols:**

```
ffffffff81010300-ffffffff8101036f: common_branch_type (STB_GLOBAL)
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
In arch/x86/events/intel/lbr.c (ffffffff81012861)
Location: arch/x86/events/intel/lbr.c:1019
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
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
In arch/x86/events/intel/lbr.c (ffffffff81011791)
Location: arch/x86/events/intel/lbr.c:1019
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
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
In arch/x86/events/intel/lbr.c (ffffffff81012821)
Location: arch/x86/events/intel/lbr.c:1019
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
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
In arch/x86/events/intel/lbr.c (ffffffff81012a41)
Location: arch/x86/events/intel/lbr.c:1019
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
