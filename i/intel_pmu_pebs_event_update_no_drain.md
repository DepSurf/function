# Function: <code>intel_pmu_pebs_event_update_no_drain</code>

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
void intel_pmu_pebs_event_update_no_drain(struct cpu_hw_events *cpuc, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f5d0)
Location: arch/x86/events/intel/ds.c:1765
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
**Symbols:**

```
ffffffff8100f5d0-ffffffff8100f643: intel_pmu_pebs_event_update_no_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_pmu_pebs_event_update_no_drain(struct cpu_hw_events *cpuc, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fcb0)
Location: arch/x86/events/intel/ds.c:1810
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
**Symbols:**

```
ffffffff8100fcb0-ffffffff8100fd23: intel_pmu_pebs_event_update_no_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pmu_pebs_event_update_no_drain(struct cpu_hw_events *cpuc, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011310)
Location: arch/x86/events/intel/ds.c:1811
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
**Symbols:**

```
ffffffff81011310-ffffffff81011383: intel_pmu_pebs_event_update_no_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pmu_pebs_event_update_no_drain(struct cpu_hw_events *cpuc, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010940)
Location: arch/x86/events/intel/ds.c:1827
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
**Symbols:**

```
ffffffff81010940-ffffffff810109b3: intel_pmu_pebs_event_update_no_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pmu_pebs_event_update_no_drain(struct cpu_hw_events *cpuc, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810123b0)
Location: arch/x86/events/intel/ds.c:1947
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
**Symbols:**

```
ffffffff810123b0-ffffffff8101242b: intel_pmu_pebs_event_update_no_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_pmu_pebs_event_update_no_drain(struct cpu_hw_events *cpuc, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810132b0)
Location: arch/x86/events/intel/ds.c:1956
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
**Symbols:**

```
ffffffff810132b0-ffffffff81013352: intel_pmu_pebs_event_update_no_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pmu_pebs_event_update_no_drain(struct cpu_hw_events *cpuc, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81014e20)
Location: arch/x86/events/intel/ds.c:2014
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
**Symbols:**

```
ffffffff81014e20-ffffffff81014edf: intel_pmu_pebs_event_update_no_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pmu_pebs_event_update_no_drain(struct cpu_hw_events *cpuc, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81018ff0)
Location: arch/x86/events/intel/ds.c:2073
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
**Symbols:**

```
ffffffff81018ff0-ffffffff81019087: intel_pmu_pebs_event_update_no_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pmu_pebs_event_update_no_drain(struct cpu_hw_events *cpuc, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81018a30)
Location: arch/x86/events/intel/ds.c:2127
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
**Symbols:**

```
ffffffff81018a30-ffffffff81018ac7: intel_pmu_pebs_event_update_no_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pmu_pebs_event_update_no_drain(struct cpu_hw_events *cpuc, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101e590)
Location: arch/x86/events/intel/ds.c:2132
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
**Symbols:**

```
ffffffff8101e590-ffffffff8101e627: intel_pmu_pebs_event_update_no_drain (STB_LOCAL)
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
void intel_pmu_pebs_event_update_no_drain(struct cpu_hw_events *cpuc, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fcb0)
Location: arch/x86/events/intel/ds.c:1810
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
**Symbols:**

```
ffffffff8100fcb0-ffffffff8100fd23: intel_pmu_pebs_event_update_no_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_pmu_pebs_event_update_no_drain(struct cpu_hw_events *cpuc, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100ea50)
Location: arch/x86/events/intel/ds.c:1810
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
**Symbols:**

```
ffffffff8100ea50-ffffffff8100eac3: intel_pmu_pebs_event_update_no_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_pmu_pebs_event_update_no_drain(struct cpu_hw_events *cpuc, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fc70)
Location: arch/x86/events/intel/ds.c:1810
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
**Symbols:**

```
ffffffff8100fc70-ffffffff8100fce3: intel_pmu_pebs_event_update_no_drain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_pmu_pebs_event_update_no_drain(struct cpu_hw_events *cpuc, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fe80)
Location: arch/x86/events/intel/ds.c:1810
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
```
**Symbols:**

```
ffffffff8100fe80-ffffffff8100fef3: intel_pmu_pebs_event_update_no_drain (STB_LOCAL)
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
