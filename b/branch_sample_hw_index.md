# Function: <code>branch_sample_hw_index</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81347bb3)
Location: include/linux/perf_event.h:1806
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_output_sample
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
In arch/x86/events/core.c (ffffffff81009a2e)
Location: include/linux/perf_event.h:1131
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/core.c (ffffffff8100c85e)
Location: include/linux/perf_event.h:1131
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff81014d45)
Location: include/linux/perf_event.h:1131
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8101847b)
Location: include/linux/perf_event.h:1131
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff813782b8)
Location: include/linux/perf_event.h:1131
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
In arch/x86/events/core.c (ffffffff8100f0dd)
Location: include/linux/perf_event.h:1136
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/core.c (ffffffff81011fd3)
Location: include/linux/perf_event.h:1136
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8101e3ce)
Location: include/linux/perf_event.h:1136
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In arch/x86/events/intel/lbr.c (ffffffff8102393e)
Location: include/linux/perf_event.h:1136
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save_brstack
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save_brstack
```
```
In kernel/events/core.c (ffffffff813a1598)
Location: include/linux/perf_event.h:1136
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
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
