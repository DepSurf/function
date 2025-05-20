# Function: <code>has_branch_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (0)
Location: include/linux/perf_event.h:1021
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/perf_event.h:1021
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1021
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/perf_event.h:1021
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1021
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/perf_event.h:1021
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (0)
Location: include/linux/perf_event.h:1181
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/perf_event.h:1181
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1181
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/perf_event.h:1181
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1181
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/perf_event.h:1181
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (0)
Location: include/linux/perf_event.h:1204
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/perf_event.h:1204
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1204
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/perf_event.h:1204
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1204
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/perf_event.h:1204
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (0)
Location: include/linux/perf_event.h:1200
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/perf_event.h:1200
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1200
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/perf_event.h:1200
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1200
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/perf_event.h:1200
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (0)
Location: include/linux/perf_event.h:1190
Inline: True
```
```
In arch/x86/events/amd/core.c (0)
Location: include/linux/perf_event.h:1190
Inline: True
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1190
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/perf_event.h:1190
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1190
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/linux/perf_event.h:1190
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006f3b)
Location: include/linux/perf_event.h:1218
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff81008b29)
Location: include/linux/perf_event.h:1218
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100d23c)
Location: include/linux/perf_event.h:1218
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ec62)
Location: include/linux/perf_event.h:1218
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
```
```
In kernel/events/core.c (ffffffff811d8ec4)
Location: include/linux/perf_event.h:1218
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:_free_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff811e411e)
Location: include/linux/perf_event.h:1218
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006dfb)
Location: include/linux/perf_event.h:1223
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff81008a49)
Location: include/linux/perf_event.h:1223
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100d589)
Location: include/linux/perf_event.h:1223
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f132)
Location: include/linux/perf_event.h:1223
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
```
```
In kernel/events/core.c (ffffffff811e93ac)
Location: include/linux/perf_event.h:1223
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:_free_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff811f457e)
Location: include/linux/perf_event.h:1223
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007055)
Location: include/linux/perf_event.h:1266
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff81008e59)
Location: include/linux/perf_event.h:1266
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100de2b)
Location: include/linux/perf_event.h:1266
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fa7a)
Location: include/linux/perf_event.h:1266
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff812026ef)
Location: include/linux/perf_event.h:1266
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:_free_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff8120c276)
Location: include/linux/perf_event.h:1266
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810070d5)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff810091bd)
Location: include/linux/perf_event.h:1280
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100e46b)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8101015a)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff8120f51c)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:_free_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff81219576)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
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
In arch/x86/events/core.c (ffffffff81008143)
Location: include/linux/perf_event.h:1349
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff8100a58d)
Location: include/linux/perf_event.h:1349
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100f550)
Location: include/linux/perf_event.h:1349
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8101162b)
Location: include/linux/perf_event.h:1349
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff8123a734)
Location: include/linux/perf_event.h:1349
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff81245386)
Location: include/linux/perf_event.h:1349
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
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
In arch/x86/events/core.c (ffffffff810071f3)
Location: include/linux/perf_event.h:1365
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff8100940d)
Location: include/linux/perf_event.h:1365
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100eb6b)
Location: include/linux/perf_event.h:1365
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff81010c5b)
Location: include/linux/perf_event.h:1365
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff81243b5d)
Location: include/linux/perf_event.h:1365
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff8124f9d6)
Location: include/linux/perf_event.h:1365
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
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
In arch/x86/events/core.c (ffffffff81007977)
Location: include/linux/perf_event.h:1366
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff81009dcd)
Location: include/linux/perf_event.h:1366
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100ef32)
Location: include/linux/perf_event.h:1366
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff81011c37)
Location: include/linux/perf_event.h:1366
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff81248b1a)
Location: include/linux/perf_event.h:1366
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff812542a6)
Location: include/linux/perf_event.h:1366
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
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
In arch/x86/events/core.c (ffffffff81008387)
Location: include/linux/perf_event.h:1371
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff8100aedd)
Location: include/linux/perf_event.h:1371
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100fa7c)
Location: include/linux/perf_event.h:1371
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff81012acf)
Location: include/linux/perf_event.h:1371
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff8128391e)
Location: include/linux/perf_event.h:1371
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff8128fd16)
Location: include/linux/perf_event.h:1371
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
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
In arch/x86/events/core.c (ffffffff81008e2a)
Location: include/linux/perf_event.h:1413
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff8100a225)
Location: include/linux/perf_event.h:1413
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8101100f)
Location: include/linux/perf_event.h:1413
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8101478a)
Location: include/linux/perf_event.h:1413
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff812d6953)
Location: include/linux/perf_event.h:1413
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff812e4d86)
Location: include/linux/perf_event.h:1413
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
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
In arch/x86/events/core.c (ffffffff8100a186)
Location: include/linux/perf_event.h:1512
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff8100cf16)
Location: include/linux/perf_event.h:1512
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
```
```
In arch/x86/events/amd/lbr.c (ffffffff8100d9de)
Location: include/linux/perf_event.h:1512
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_del
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_add
```
```
In arch/x86/events/intel/core.c (ffffffff81015435)
Location: include/linux/perf_event.h:1512
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff810189ce)
Location: include/linux/perf_event.h:1512
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff8133f720)
Location: include/linux/perf_event.h:1512
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134e596)
Location: include/linux/perf_event.h:1512
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
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
In arch/x86/events/core.c (ffffffff8100999f)
Location: include/linux/perf_event.h:1625
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff8100c6cb)
Location: include/linux/perf_event.h:1625
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_hw_config
  - arch/x86/events/amd/core.c:amd_pmu_hw_config
```
```
In arch/x86/events/amd/lbr.c (ffffffff8100d1ae)
Location: include/linux/perf_event.h:1625
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_del
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_add
```
```
In arch/x86/events/intel/core.c (ffffffff81014c9e)
Location: include/linux/perf_event.h:1625
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff810182e5)
Location: include/linux/perf_event.h:1625
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff81370846)
Location: include/linux/perf_event.h:1625
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137f7b6)
Location: include/linux/perf_event.h:1625
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
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
In arch/x86/events/core.c (ffffffff8100f0bc)
Location: include/linux/perf_event.h:1667
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff81011ec5)
Location: include/linux/perf_event.h:1667
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_hw_config
  - arch/x86/events/amd/core.c:amd_pmu_hw_config
```
```
In arch/x86/events/amd/lbr.c (ffffffff810129ee)
Location: include/linux/perf_event.h:1667
Inline: True
Inline callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_del
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_add
```
```
In arch/x86/events/amd/ibs.c (ffffffff81013222)
Location: include/linux/perf_event.h:1667
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_init
```
```
In arch/x86/events/intel/core.c (ffffffff81019c8e)
Location: include/linux/perf_event.h:1667
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8101de66)
Location: include/linux/perf_event.h:1667
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff81399b46)
Location: include/linux/perf_event.h:1667
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a89d6)
Location: include/linux/perf_event.h:1667
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029747c)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:_free_event
```
```
In kernel/events/hw_breakpoint.c (ffff8000102a4784)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
```
```
In drivers/perf/arm-ccn.c (ffff800010b92554)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_init
```
```
In drivers/perf/arm_pmu.c (ffff800010b9473c)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c76ac)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:_free_event
```
```
In kernel/events/hw_breakpoint.c (c04d3d44)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
```
```
In drivers/perf/arm-ccn.c (c0c7c028)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_init
```
```
In drivers/perf/arm_pmu.c (c0c7de98)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/perf/core-book3s.c (c0000000001271a8)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:power_pmu_event_init
  - arch/powerpc/perf/core-book3s.c:power_pmu_event_init
  - arch/powerpc/perf/core-book3s.c:power_pmu_del
  - arch/powerpc/perf/core-book3s.c:power_pmu_add
```
```
In arch/powerpc/perf/hv-24x7.c (c00000000012e2f4)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/powerpc/perf/hv-24x7.c:h_24x7_event_init
```
```
In arch/powerpc/perf/hv-gpci.c (c0000000001303b0)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/powerpc/perf/hv-gpci.c:h_gpci_event_init
```
```
In kernel/events/core.c (c000000000341b10)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:_free_event
```
```
In kernel/events/hw_breakpoint.c (c000000000356fa4)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c5ebc)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:_free_event
```
</details>
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
In arch/x86/events/core.c (ffffffff810070d5)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff810091bd)
Location: include/linux/perf_event.h:1280
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100e46b)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8101015a)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff81207b3c)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:_free_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff81211bc6)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
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
In arch/x86/events/core.c (ffffffff810057f5)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff8100794d)
Location: include/linux/perf_event.h:1280
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100d0cb)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8100eefa)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff811fac6c)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:_free_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff81204956)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
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
In arch/x86/events/core.c (ffffffff81007095)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff8100917d)
Location: include/linux/perf_event.h:1280
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100e42b)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8101011a)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff8120590c)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:_free_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff8120f966)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
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
In arch/x86/events/core.c (ffffffff810071f5)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
```
```
In arch/x86/events/amd/core.c (ffffffff810092dd)
Location: include/linux/perf_event.h:1280
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100e5fb)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8101032a)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
```
```
In kernel/events/core.c (ffffffff8121477c)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - kernel/events/core.c:perf_uprobe_event_init
  - kernel/events/core.c:perf_kprobe_event_init
  - kernel/events/core.c:perf_tp_event_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:_free_event
```
```
In kernel/events/hw_breakpoint.c (ffffffff8121e876)
Location: include/linux/perf_event.h:1280
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:hw_breakpoint_event_init
```
</details>
</li>
</ul>

## Differences
