# Function: <code>is_pebs_pt</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810057b6)
Location: arch/x86/events/perf_event.h:936
Inline: True
Inline callers:
  - arch/x86/events/core.c:collect_events
```
```
In arch/x86/events/intel/ds.c (ffffffff81011ead)
Location: arch/x86/events/perf_event.h:936
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810066e8)
Location: arch/x86/events/perf_event.h:945
Inline: True
Inline callers:
  - arch/x86/events/core.c:collect_events
```
```
In arch/x86/events/intel/ds.c (ffffffff8101331d)
Location: arch/x86/events/perf_event.h:945
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006416)
Location: arch/x86/events/perf_event.h:1076
Inline: True
Inline callers:
  - arch/x86/events/core.c:collect_events
```
```
In arch/x86/events/intel/ds.c (ffffffff81012ecd)
Location: arch/x86/events/perf_event.h:1076
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006624)
Location: arch/x86/events/perf_event.h:1215
Inline: True
Inline callers:
  - arch/x86/events/core.c:collect_events
```
```
In arch/x86/events/intel/ds.c (ffffffff810140dd)
Location: arch/x86/events/perf_event.h:1215
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006d04)
Location: arch/x86/events/perf_event.h:1215
Inline: True
Inline callers:
  - arch/x86/events/core.c:collect_events
```
```
In arch/x86/events/intel/ds.c (ffffffff8101543e)
Location: arch/x86/events/perf_event.h:1215
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810061c3)
Location: arch/x86/events/perf_event.h:1326
Inline: True
Inline callers:
  - arch/x86/events/core.c:collect_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100eb75)
Location: arch/x86/events/perf_event.h:1326
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_assign_event
```
```
In arch/x86/events/intel/ds.c (ffffffff810173c6)
Location: arch/x86/events/perf_event.h:1326
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007753)
Location: arch/x86/events/perf_event.h:1408
Inline: True
Inline callers:
  - arch/x86/events/core.c:collect_events
```
```
In arch/x86/events/intel/core.c (ffffffff81012275)
Location: arch/x86/events/perf_event.h:1408
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_assign_event
```
```
In arch/x86/events/intel/ds.c (ffffffff8101b576)
Location: arch/x86/events/perf_event.h:1408
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006ed2)
Location: arch/x86/events/perf_event.h:1413
Inline: True
Inline callers:
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
```
```
In arch/x86/events/intel/core.c (ffffffff81011775)
Location: arch/x86/events/perf_event.h:1413
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_assign_event
```
```
In arch/x86/events/intel/ds.c (ffffffff8101b246)
Location: arch/x86/events/perf_event.h:1413
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100c602)
Location: arch/x86/events/perf_event.h:1428
Inline: True
Inline callers:
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
```
```
In arch/x86/events/intel/core.c (ffffffff81016f15)
Location: arch/x86/events/perf_event.h:1428
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_assign_event
```
```
In arch/x86/events/intel/ds.c (ffffffff81020da6)
Location: arch/x86/events/perf_event.h:1428
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810057b6)
Location: arch/x86/events/perf_event.h:936
Inline: True
Inline callers:
  - arch/x86/events/core.c:collect_events
```
```
In arch/x86/events/intel/ds.c (ffffffff81011ead)
Location: arch/x86/events/perf_event.h:936
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81003e96)
Location: arch/x86/events/perf_event.h:936
Inline: True
Inline callers:
  - arch/x86/events/core.c:collect_events
```
```
In arch/x86/events/intel/ds.c (ffffffff81010cdd)
Location: arch/x86/events/perf_event.h:936
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005776)
Location: arch/x86/events/perf_event.h:936
Inline: True
Inline callers:
  - arch/x86/events/core.c:collect_events
```
```
In arch/x86/events/intel/ds.c (ffffffff81011e6d)
Location: arch/x86/events/perf_event.h:936
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810058d6)
Location: arch/x86/events/perf_event.h:936
Inline: True
Inline callers:
  - arch/x86/events/core.c:collect_events
```
```
In arch/x86/events/intel/ds.c (ffffffff8101208d)
Location: arch/x86/events/perf_event.h:936
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_disable
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_enable
```
</details>
</li>
</ul>

## Differences
