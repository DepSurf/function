# Function: <code>hybrid_pmu</code>

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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008cdc)
Location: arch/x86/events/perf_event.h:665
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_event_init
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_event
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:x86_pmu_extra_regs
```
```
In arch/x86/events/intel/core.c (ffffffff8100d9e5)
Location: arch/x86/events/perf_event.h:665
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_filter_match
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dead
  - arch/x86/events/intel/core.c:adl_get_event_constraints
  - arch/x86/events/intel/core.c:intel_guest_get_msrs
  - arch/x86/events/intel/core.c:x86_get_event_constraints
  - arch/x86/events/intel/core.c:__intel_shared_reg_get_constraints
  - arch/x86/events/intel/core.c:__intel_shared_reg_get_constraints
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:adl_set_topdown_event_period
```
```
In arch/x86/events/intel/ds.c (ffffffff81012dda)
Location: arch/x86/events/perf_event.h:665
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
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
In arch/x86/events/core.c (ffffffff81009b58)
Location: arch/x86/events/perf_event.h:665
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:x86_pmu_event_init
  - arch/x86/events/core.c:allocate_fake_cpuc
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:perf_event_print_debug
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_event
  - arch/x86/events/core.c:x86_schedule_events
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:x86_pmu_extra_regs
```
```
In arch/x86/events/intel/core.c (ffffffff8100e015)
Location: arch/x86/events/perf_event.h:665
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_filter_match
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dead
  - arch/x86/events/intel/core.c:adl_hw_config
  - arch/x86/events/intel/core.c:adl_get_event_constraints
  - arch/x86/events/intel/core.c:intel_guest_get_msrs
  - arch/x86/events/intel/core.c:x86_get_event_constraints
  - arch/x86/events/intel/core.c:__intel_shared_reg_get_constraints
  - arch/x86/events/intel/core.c:__intel_shared_reg_get_constraints
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:adl_set_topdown_event_period
```
```
In arch/x86/events/intel/ds.c (ffffffff810142a5)
Location: arch/x86/events/perf_event.h:665
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/ds.c:pebs_update_state
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
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
In arch/x86/events/core.c (0)
Location: arch/x86/events/perf_event.h:679
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/perf_event.h:679
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/perf_event.h:679
Inline: True
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
In arch/x86/events/core.c (0)
Location: arch/x86/events/perf_event.h:682
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/perf_event.h:682
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/perf_event.h:682
Inline: True
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
In arch/x86/events/core.c (0)
Location: arch/x86/events/perf_event.h:686
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/perf_event.h:686
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/perf_event.h:686
Inline: True
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
In arch/x86/events/core.c (0)
Location: arch/x86/events/perf_event.h:711
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/perf_event.h:711
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/perf_event.h:711
Inline: True
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
