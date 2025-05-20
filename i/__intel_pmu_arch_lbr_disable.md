# Function: <code>__intel_pmu_arch_lbr_disable</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100fe68)
Location: arch/x86/events/perf_event.h:1359
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
```
```
In arch/x86/events/intel/lbr.c (ffffffff810197b6)
Location: arch/x86/events/perf_event.h:1359
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
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
In arch/x86/events/intel/core.c (ffffffff81013f68)
Location: arch/x86/events/perf_event.h:1441
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101d791)
Location: arch/x86/events/perf_event.h:1441
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
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
In arch/x86/events/intel/core.c (ffffffff810137c8)
Location: arch/x86/events/perf_event.h:1446
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101d491)
Location: arch/x86/events/perf_event.h:1446
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
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
In arch/x86/events/intel/core.c (ffffffff81018e58)
Location: arch/x86/events/perf_event.h:1461
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
```
```
In arch/x86/events/intel/lbr.c (ffffffff81023461)
Location: arch/x86/events/perf_event.h:1461
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
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
