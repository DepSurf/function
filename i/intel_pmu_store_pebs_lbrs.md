# Function: <code>intel_pmu_store_pebs_lbrs</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void intel_pmu_store_pebs_lbrs(struct pebs_lbr *lbr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81012eb0)
Location: arch/x86/events/intel/lbr.c:1094
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
```
**Symbols:**

```
ffffffff81012eb0-ffffffff81012f7d: intel_pmu_store_pebs_lbrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_pmu_store_pebs_lbrs(struct pebs_lbr *lbr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81013660)
Location: arch/x86/events/intel/lbr.c:1094
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
```
**Symbols:**

```
ffffffff81013660-ffffffff8101372f: intel_pmu_store_pebs_lbrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pmu_store_pebs_lbrs(struct pebs_lbr *lbr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81014c10)
Location: arch/x86/events/intel/lbr.c:1119
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
```
**Symbols:**

```
ffffffff81014c10-ffffffff81014d2c: intel_pmu_store_pebs_lbrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pmu_store_pebs_lbrs(struct lbr_entry *lbr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81015120)
Location: arch/x86/events/intel/lbr.c:1452
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
```
**Symbols:**

```
ffffffff81015120-ffffffff81015192: intel_pmu_store_pebs_lbrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pmu_store_pebs_lbrs(struct lbr_entry *lbr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81016390)
Location: arch/x86/events/intel/lbr.c:1468
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
```
**Symbols:**

```
ffffffff81016390-ffffffff8101640d: intel_pmu_store_pebs_lbrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_pmu_store_pebs_lbrs(struct lbr_entry *lbr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81017df0)
Location: arch/x86/events/intel/lbr.c:1468
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
```
**Symbols:**

```
ffffffff81017df0-ffffffff81017e6d: intel_pmu_store_pebs_lbrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pmu_store_pebs_lbrs(struct lbr_entry *lbr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81019e30)
Location: arch/x86/events/intel/lbr.c:1459
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
```
**Symbols:**

```
ffffffff81019e30-ffffffff81019ebf: intel_pmu_store_pebs_lbrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pmu_store_pebs_lbrs(struct lbr_entry *lbr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101de80)
Location: arch/x86/events/intel/lbr.c:1186
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
```
**Symbols:**

```
ffffffff8101de80-ffffffff8101df06: intel_pmu_store_pebs_lbrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pmu_store_pebs_lbrs(struct lbr_entry *lbr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101db80)
Location: arch/x86/events/intel/lbr.c:1186
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
```
**Symbols:**

```
ffffffff8101db80-ffffffff8101dc06: intel_pmu_store_pebs_lbrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pmu_store_pebs_lbrs(struct lbr_entry *lbr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81023c50)
Location: arch/x86/events/intel/lbr.c:1265
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
```
**Symbols:**

```
ffffffff81023c50-ffffffff81023cd6: intel_pmu_store_pebs_lbrs (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void intel_pmu_store_pebs_lbrs(struct pebs_lbr *lbr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81013660)
Location: arch/x86/events/intel/lbr.c:1094
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
```
**Symbols:**

```
ffffffff81013660-ffffffff8101372f: intel_pmu_store_pebs_lbrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_pmu_store_pebs_lbrs(struct pebs_lbr *lbr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810127d0)
Location: arch/x86/events/intel/lbr.c:1094
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
```
**Symbols:**

```
ffffffff810127d0-ffffffff8101289f: intel_pmu_store_pebs_lbrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_pmu_store_pebs_lbrs(struct pebs_lbr *lbr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81013620)
Location: arch/x86/events/intel/lbr.c:1094
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
```
**Symbols:**

```
ffffffff81013620-ffffffff810136ef: intel_pmu_store_pebs_lbrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_pmu_store_pebs_lbrs(struct pebs_lbr *lbr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81013840)
Location: arch/x86/events/intel/lbr.c:1094
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
```
**Symbols:**

```
ffffffff81013840-ffffffff8101390f: intel_pmu_store_pebs_lbrs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct pebs_lbr *lbr</code> ➡️ <code>struct lbr_entry *lbr</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
