# Function: <code>intel_pmu_lbr_filter</code>

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
In arch/x86/events/intel/lbr.c (ffffffff81011eb2)
Location: arch/x86/events/intel/lbr.c:815
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff810117e9)
Location: arch/x86/events/intel/lbr.c:940
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff81011919)
Location: arch/x86/events/intel/lbr.c:934
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff8100fdd0)
Location: arch/x86/events/intel/lbr.c:941
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff81010562)
Location: arch/x86/events/intel/lbr.c:988
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
In arch/x86/events/intel/lbr.c (ffffffff810111e3)
Location: arch/x86/events/intel/lbr.c:1008
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
In arch/x86/events/intel/lbr.c (ffffffff81011843)
Location: arch/x86/events/intel/lbr.c:1030
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void intel_pmu_lbr_filter(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81011fe0)
Location: arch/x86/events/intel/lbr.c:1042
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff81011fe0-ffffffff810121dc: intel_pmu_lbr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_pmu_lbr_filter(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810127a0)
Location: arch/x86/events/intel/lbr.c:1042
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff810127a0-ffffffff8101298e: intel_pmu_lbr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pmu_lbr_filter(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81013c20)
Location: arch/x86/events/intel/lbr.c:1067
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff81013c20-ffffffff81013e1c: intel_pmu_lbr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pmu_lbr_filter(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81013970)
Location: arch/x86/events/intel/lbr.c:1389
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff81013970-ffffffff81013b9b: intel_pmu_lbr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pmu_lbr_filter(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81014b30)
Location: arch/x86/events/intel/lbr.c:1405
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff81014b30-ffffffff81014d53: intel_pmu_lbr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_pmu_lbr_filter(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81015ee0)
Location: arch/x86/events/intel/lbr.c:1405
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff81015ee0-ffffffff81016377: intel_pmu_lbr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pmu_lbr_filter(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81018010)
Location: arch/x86/events/intel/lbr.c:1396
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff81018010-ffffffff810184d7: intel_pmu_lbr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pmu_lbr_filter(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101beb0)
Location: arch/x86/events/intel/lbr.c:1123
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff8101beb0-ffffffff8101c2c8: intel_pmu_lbr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pmu_lbr_filter(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101bb70)
Location: arch/x86/events/intel/lbr.c:1123
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff8101bb70-ffffffff8101bf88: intel_pmu_lbr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pmu_lbr_filter(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810216f0)
Location: arch/x86/events/intel/lbr.c:1200
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff810216f0-ffffffff81021b8e: intel_pmu_lbr_filter (STB_LOCAL)
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
void intel_pmu_lbr_filter(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810127a0)
Location: arch/x86/events/intel/lbr.c:1042
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff810127a0-ffffffff8101298e: intel_pmu_lbr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_pmu_lbr_filter(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810116d0)
Location: arch/x86/events/intel/lbr.c:1042
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff810116d0-ffffffff810118be: intel_pmu_lbr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_pmu_lbr_filter(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81012760)
Location: arch/x86/events/intel/lbr.c:1042
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff81012760-ffffffff8101294e: intel_pmu_lbr_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_pmu_lbr_filter(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81012980)
Location: arch/x86/events/intel/lbr.c:1042
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff81012980-ffffffff81012b6e: intel_pmu_lbr_filter (STB_LOCAL)
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
