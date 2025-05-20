# Function: <code>local_add</code>

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
In arch/x86/events/core.c (ffffffff810059d5)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008292)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100914d)
Location: arch/x86/include/asm/local.h:30
Inline: True
```
```
In arch/x86/events/msr.c (ffffffff81009d90)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_del
```
```
In arch/x86/events/amd/iommu.c (ffffffff81009f7f)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/intel/bts.c (ffffffff8100c9c0)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/cstate.c (ffffffff8100ee6b)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/cstate.c:cstate_pmu_event_update
```
```
In arch/x86/events/intel/pt.c (ffffffff81013587)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/rapl.c (ffffffff810149c0)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:rapl_event_update
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016a13)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff8114750c)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
```
```
In kernel/events/core.c (ffffffff811787bc)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff81185586)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_end
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
In arch/x86/events/core.c (ffffffff81005c68)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff810084e6)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009474)
Location: arch/x86/include/asm/local.h:30
Inline: True
```
```
In arch/x86/events/msr.c (ffffffff81009ff6)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100a134)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/intel/bts.c (ffffffff8100cc23)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/pt.c (ffffffff81012f6a)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015c96)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff81152871)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff81188c26)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff81197974)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In arch/x86/events/core.c (ffffffff81005ba8)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008506)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff810094b4)
Location: arch/x86/include/asm/local.h:30
Inline: True
```
```
In arch/x86/events/msr.c (ffffffff8100a036)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100a174)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ccf3)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/pt.c (ffffffff8101305a)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015e69)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff8115c8a7)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff81198006)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff811a7364)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In arch/x86/events/core.c (ffffffff81005946)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff810081b6)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff810091a1)
Location: arch/x86/include/asm/local.h:30
Inline: True
```
```
In arch/x86/events/amd/iommu.c (ffffffff81009e49)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8100a4e1)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ccb9)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/pt.c (ffffffff810115ba)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014319)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff8115f90f)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff8119fb36)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff811aeb24)
Location: arch/x86/include/asm/local.h:30
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_skip
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In arch/x86/events/core.c (ffffffff81005ca6)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008636)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100944b)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100a329)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8100a9c1)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d259)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/pt.c (ffffffff81011cfa)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014b4f)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff8116c9cf)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff811b3526)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff811c26d3)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In arch/x86/events/core.c (ffffffff81006439)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008de2)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009b4b)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100aa38)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8100b152)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d9c6)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e7cb)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff810126cd)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015693)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff8117b9ea)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff811d2c93)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff811e2a2c)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In arch/x86/events/core.c (ffffffff81006389)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008d02)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009a7b)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100a968)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8100b0b2)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100de96)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ec9b)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81012dcd)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015da8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff81188b6d)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff811e2fa3)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff811f2e9c)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In arch/x86/events/core.c (ffffffff8100659a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009192)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009f5b)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100ae18)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8100b582)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100e767)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f593)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff8101415d)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff810173b6)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff811962d7)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff811fa173)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff8120ab91)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In arch/x86/events/core.c (ffffffff8100662a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009592)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a34b)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b228)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8100b992)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ec37)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc68)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff8101485e)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017d66)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff811a1ca7)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff81207243)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff81217e71)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In arch/x86/events/core.c (ffffffff8100778a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100a742)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b8a2)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100c4f4)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8100cc9f)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ffe7)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff810112c8)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81015e27)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019916)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff811b7bfa)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/events/core.c (ffffffff81230733)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff8124380b)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In drivers/net/loopback.c (ffffffff8187eb91)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8188ec1f)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
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
In arch/x86/events/core.c (ffffffff81006846)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff810095a2)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a8a2)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b454)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8100bbef)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100bd42)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f547)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff810108f8)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff810162c7)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019f86)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff811b57ba)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/events/core.c (ffffffff8123a393)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff8124de8f)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In block/blk-iocost.c (ffffffff815906ad)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
```
```
In drivers/net/loopback.c (ffffffff8188d111)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
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
In arch/x86/events/core.c (ffffffff81006997)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009f72)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b172)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100bdcd)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/msr.c (ffffffff8100c57f)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100c6d2)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In arch/x86/events/intel/bts.c (ffffffff8101059a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff81011898)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff810175b7)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101b306)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff811b70a3)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/events/core.c (ffffffff8123ebc3)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff812527cf)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In block/blk-iocost.c (ffffffff8159745b)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
```
```
In drivers/net/loopback.c (ffffffff8186fa51)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In net/ipv6/seg6_local.c (ffffffff81b7d78e)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input
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
In arch/x86/events/core.c (ffffffff8100708a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b35f)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100c2cd)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/msr.c (ffffffff8100caaf)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100df72)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In arch/x86/events/intel/bts.c (ffffffff810112d8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff81012761)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101a1c8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101dc62)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/seccomp.c (ffffffff811cde0c)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/trace/ring_buffer.c (ffffffff811e128d)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/bpf_trace.c (ffffffff812182f6)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff81252396)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff8125eedb)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff8126bde3)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8126d9a0)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff812764e0)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In kernel/events/core.c (ffffffff812795d3)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff8128e08e)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In block/blk-iocost.c (ffffffff815feab6)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
```
```
In drivers/net/loopback.c (ffffffff8190001d)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff8190f0e4)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81915778)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff8191eb1c)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81a917c7)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81aa1de9)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81acfe9d)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81ad1a37)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/ptp_classifier.c (ffffffff81aec7bd)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81aedc9e)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/core/skmsg.c (ffffffff81b073d7)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81b2c089)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b539ab)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8842b)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1b455)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81c48156)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e715)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81c56b94)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In arch/x86/events/core.c (ffffffff8100656a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100bd20)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100d015)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8100d8ae)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff8100f3a2)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In arch/x86/events/intel/bts.c (ffffffff81012a58)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff81014359)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101c6ba)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff810206ea)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/seccomp.c (ffffffff81201d38)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In kernel/trace/ring_buffer.c (ffffffff81217faf)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/bpf_trace.c (ffffffff81257581)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/bpf/syscall.c (ffffffff812779ef)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff8129a16d)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff812a949f)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff812bac2c)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff812bc11a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff812c5f3a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
```
```
In kernel/events/core.c (ffffffff812cc678)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff812e2f48)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In block/blk-iocost.c (ffffffff816b2329)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
```
```
In drivers/net/loopback.c (ffffffff81a51a47)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81a63cbf)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6ae56)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81a73d82)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/core/gen_stats.c (ffffffff81c029ec)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81c0796d)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81c1a041)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/filter.c (ffffffff81c4d657)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81c4f2de)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/ptp_classifier.c (ffffffff81c6f1e8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81c7078e)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81c8be8f)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/sched/sch_generic.c (ffffffff81c9484a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81ca42a8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81ca84a9)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/bpf/test_run.c (ffffffff81cb6693)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce1500)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d195e0)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81db7bed)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81de7656)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def01d)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df5f6a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In arch/x86/events/core.c (ffffffff81005eef)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ed30)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/amd/iommu.c (ffffffff81010145)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff81010aee)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81012d52)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In arch/x86/events/intel/bts.c (ffffffff81016a58)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff81018519)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81020a4a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102502a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/seccomp.c (ffffffff8124a10a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff81261611)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/bpf_trace.c (ffffffff812a6f61)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:kprobe_multi_link_handler
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b8213)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff812cdd7f)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff812f60d7)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff813082a4)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff8131e010)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8131f508)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff8132b4ba)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
```
```
In kernel/events/core.c (ffffffff813344c8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff8134b5a8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In block/blk-iocost.c (ffffffff81771859)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
```
```
In drivers/spi/spi.c (ffffffff81bcf540)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/loopback.c (ffffffff81bdac87)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81bf2e9e)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfdc31)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81c07f93)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/core/gen_stats.c (ffffffff81db1eac)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81db73f4)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81dcb0a4)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/filter.c (ffffffff81e02567)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81e04472)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/drop_monitor.c (ffffffff81e25ed8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/core/ptp_classifier.c (ffffffff81e26fa8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81e28782)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/devlink.c (ffffffff81e2aae3)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_stats_read
  - net/core/devlink.c:devlink_trap_stats_read
```
```
In net/core/skmsg.c (ffffffff81e483c6)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/sched/sch_generic.c (ffffffff81e5030a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81e60c18)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81e652c9)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/bpf/test_run.c (ffffffff81e74b78)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea24f0)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81edff60)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0df27)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv6/udp.c (ffffffff81f87a4d)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81fba5d6)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc30ad)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fca4c6)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/8021q/vlan_core.c (ffffffff81fcea90)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In arch/x86/events/core.c (ffffffff81005696)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100e310)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100f805)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff810101ae)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81012322)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In arch/x86/events/intel/bts.c (ffffffff810163f8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff81017df9)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81020b0a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81024f22)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/seccomp.c (ffffffff81261424)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff81278676)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/bpf_trace.c (ffffffff812c8840)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812db83a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff812f5310)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff81323e87)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff813375d5)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
```
```
In kernel/bpf/devmap.c (ffffffff8134de00)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff8134f3eb)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff8135b6da)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
```
```
In kernel/events/core.c (ffffffff81365211)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff8137c5f8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In block/blk-iocost.c (ffffffff817b0b41)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1a94d)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_event_update
```
```
In drivers/spi/spi.c (ffffffff81c271b0)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/loopback.c (ffffffff81c3172b)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/tun.c (ffffffff81c4a085)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/virtio_net.c (ffffffff81c4f79b)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c63270)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d686)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/core/gen_stats.c (ffffffff81e2247c)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81e27ab4)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81e3bc2e)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/filter.c (ffffffff81e74917)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81e76cc3)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/drop_monitor.c (ffffffff81e9b478)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/core/ptp_classifier.c (ffffffff81e9c52f)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81e9dda3)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81ea3b8b)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/sched/sch_generic.c (ffffffff81eabab0)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81ebcc68)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81ec1209)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/bpf/test_run.c (ffffffff81ed0948)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_bpf_link.c (ffffffff81eea919)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f00d0f)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f3f39f)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6dbd7)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv6/udp.c (ffffffff81fe7eda)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff8201ad09)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8202401a)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202b318)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/devlink/leftover.c (ffffffff8202ea03)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_trap_report
  - net/devlink/leftover.c:devlink_trap_report
  - net/devlink/leftover.c:devlink_trap_stats_read
  - net/devlink/leftover.c:devlink_trap_stats_read
```
```
In net/8021q/vlan_core.c (ffffffff8204a3f8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In arch/x86/events/core.c (ffffffff8100ad8e)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/ibs.c (ffffffff81013a53)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_event_update
```
```
In arch/x86/events/amd/iommu.c (ffffffff81014f45)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8101596c)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/core.c (ffffffff81017c42)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:__icl_update_topdown_event
```
```
In arch/x86/events/intel/bts.c (ffffffff8101bf38)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8101d969)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff81026bfa)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102b082)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/seccomp.c (ffffffff8127b624)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/ring_buffer.c (ffffffff81293195)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_handle_head_page
  - kernel/trace/ring_buffer.c:rb_remove_pages
```
```
In kernel/trace/bpf_trace.c (ffffffff812e5848)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:uprobe_prog_run
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
  - kernel/trace/bpf_trace.c:trace_call_bpf
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f9922)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/bpf/syscall.c (ffffffff81314107)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
```
```
In kernel/bpf/bpf_iter.c (ffffffff81347e17)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
```
```
In kernel/bpf/trampoline.c (ffffffff8135d415)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
```
```
In kernel/bpf/devmap.c (ffffffff8137530c)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff81376a59)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/cgroup.c (ffffffff8138436a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_current
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
```
```
In kernel/events/core.c (ffffffff8138e231)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_del
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff813a583b)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In block/blk-iocost.c (ffffffff817f4951)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b7047d)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_event_update
```
```
In drivers/spi/spi.c (ffffffff81cdae60)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/loopback.c (ffffffff81ce45ab)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/netkit.c (ffffffff81ce5387)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/netkit.c:netkit_xmit
```
```
In drivers/net/tun.c (ffffffff81cffa11)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/virtio_net.c (ffffffff81d0c6b0)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:free_old_xmit_skbs
  - drivers/net/virtio_net.c:free_old_xmit_skbs
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d19c90)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
```
In drivers/net/xen-netfront.c (ffffffff81d21fd6)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/core/gen_stats.c (ffffffff81ee03bc)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81ee5a64)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff81efa16a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:tc_run
  - net/core/dev.c:tc_run
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
```
```
In net/core/filter.c (ffffffff81f340d7)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/filter.c:bpf_run_sk_reuseport
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81f36c83)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/drop_monitor.c (ffffffff81f5dbe8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
```
```
In net/core/ptp_classifier.c (ffffffff81f5ecbf)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/ptp_classifier.c:ptp_classify_raw
```
```
In net/core/lwt_bpf.c (ffffffff81f60523)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/core/skmsg.c (ffffffff81f6648b)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/sched/sch_generic.c (ffffffff81f6e550)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
  - net/sched/sch_generic.c:pfifo_fast_dequeue
```
```
In net/sched/act_api.c (ffffffff81f7fe68)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
  - net/sched/act_api.c:tcf_action_update_stats
```
```
In net/sched/sch_fifo.c (ffffffff81f84509)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_dequeue_head
  - net/sched/sch_fifo.c:qdisc_dequeue_head
```
```
In net/bpf/test_run.c (ffffffff81f942a8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:__bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_bpf_link.c (ffffffff81fae6c9)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/netfilter/nf_bpf_link.c:nf_hook_run_bpf
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc4ed8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:bpf_sk_lookup_run_v4
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034364)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv6/seg6_local.c (ffffffff820e9cc9)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_input_core
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3133)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:bpf_sk_lookup_run_v6
```
```
In net/packet/af_packet.c (ffffffff820fadeb)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/devlink/trap.c (ffffffff82114833)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_trap_report
  - net/devlink/trap.c:devlink_trap_report
  - net/devlink/trap.c:devlink_trap_stats_read
  - net/devlink/trap.c:devlink_trap_stats_read
```
```
In net/8021q/vlan_core.c (ffffffff8211c864)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/perf/core-book3s.c (c000000000128a70)
Location: arch/powerpc/include/asm/local.h:57
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:record_and_restart
  - arch/powerpc/perf/core-book3s.c:freeze_limited_counters
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012b9ac)
Location: arch/powerpc/include/asm/local.h:57
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:imc_event_update
```
```
In arch/powerpc/perf/hv-24x7.c (c00000000012ddc4)
Location: arch/powerpc/include/asm/local.h:57
Inline: True
Inline callers:
  - arch/powerpc/perf/hv-24x7.c:update_event_count
```
```
In arch/powerpc/perf/hv-gpci.c (c0000000001304d8)
Location: arch/powerpc/include/asm/local.h:57
Inline: True
Inline callers:
  - arch/powerpc/perf/hv-gpci.c:h_gpci_event_update
```
```
In kernel/trace/ring_buffer.c (c00000000029ef58)
Location: arch/powerpc/include/asm/local.h:57
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (c00000000033e59c)
Location: arch/powerpc/include/asm/local.h:57
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_update
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (c000000000354a60)
Location: arch/powerpc/include/asm/local.h:57
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
</details>
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
In arch/x86/events/core.c (ffffffff8100662a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009592)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a34b)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b228)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8100b992)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ec37)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc68)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff8101485e)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017d66)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff8119a2c7)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff811ff863)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff812104c1)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In arch/x86/events/core.c (ffffffff81004d3c)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100828e)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff81008e67)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/amd/iommu.c (ffffffff81009bb8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8100a387)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d997)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e9e1)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81013b3e)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff810171b6)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff8118d347)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff811f25b3)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff81203251)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In arch/x86/events/core.c (ffffffff810065ea)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009552)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a30b)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b1e8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8100b952)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ebf7)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc28)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff8101481e)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017d26)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff81198097)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff811fd633)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff8120e261)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
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
In arch/x86/events/core.c (ffffffff8100674a)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_perf_event_update
```
```
In arch/x86/events/amd/uncore.c (ffffffff810096b2)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_read
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a46b)
Location: arch/x86/include/asm/local.h:31
Inline: True
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b3c8)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:perf_iommu_read
```
```
In arch/x86/events/msr.c (ffffffff8100bb32)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_event_update
  - arch/x86/events/msr.c:msr_event_update
```
```
In arch/x86/events/intel/bts.c (ffffffff8100edc7)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_update
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fe38)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
```
In arch/x86/events/intel/pt.c (ffffffff81014a5e)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_update_head
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017f66)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_perf_event_update
```
```
In kernel/trace/ring_buffer.c (ffffffff811a5cc7)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (ffffffff8120c393)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffffffff8121d160)
Location: arch/x86/include/asm/local.h:31
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
</details>
</li>
</ul>

## Differences
