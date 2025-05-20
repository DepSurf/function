# Function: <code>perf_sample_data_init</code>

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
In arch/x86/events/core.c (ffffffff810072e5)
Location: include/linux/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100925a)
Location: include/linux/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100c450)
Location: include/linux/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f7d8)
Location: include/linux/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff810111a4)
Location: include/linux/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81012751)
Location: include/linux/perf_event.h:808
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff81166f14)
Location: include/linux/perf_event.h:808
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff81183ab3)
Location: include/linux/perf_event.h:808
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
  - kernel/events/core.c:perf_bp_event
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
In arch/x86/events/core.c (ffffffff81007442)
Location: include/linux/perf_event.h:920
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009729)
Location: include/linux/perf_event.h:920
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100c68c)
Location: include/linux/perf_event.h:920
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f239)
Location: include/linux/perf_event.h:920
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff81010adb)
Location: include/linux/perf_event.h:920
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81012140)
Location: include/linux/perf_event.h:920
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff81174598)
Location: include/linux/perf_event.h:920
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff8118ab49)
Location: include/linux/perf_event.h:920
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81007442)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009769)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100c767)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f2f9)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff81010c8b)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81012270)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff8117fc69)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff8119a869)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81007155)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009432)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100c4d5)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100da39)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff8100f2bc)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810107d8)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff81182b02)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff811a33f5)
Location: include/linux/perf_event.h:943
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81007588)
Location: include/linux/perf_event.h:930
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009b62)
Location: include/linux/perf_event.h:930
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100ca7e)
Location: include/linux/perf_event.h:930
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e1a9)
Location: include/linux/perf_event.h:930
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff8100fa5c)
Location: include/linux/perf_event.h:930
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81010dd8)
Location: include/linux/perf_event.h:930
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff811904e5)
Location: include/linux/perf_event.h:930
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff811b73bb)
Location: include/linux/perf_event.h:930
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81007bae)
Location: include/linux/perf_event.h:949
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a020)
Location: include/linux/perf_event.h:949
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100d1e4)
Location: include/linux/perf_event.h:949
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ea10)
Location: include/linux/perf_event.h:949
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff810103ba)
Location: include/linux/perf_event.h:949
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff8101183c)
Location: include/linux/perf_event.h:949
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff811a5548)
Location: include/linux/perf_event.h:949
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff811d6a94)
Location: include/linux/perf_event.h:949
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81007a8e)
Location: include/linux/perf_event.h:954
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009f50)
Location: include/linux/perf_event.h:954
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100d532)
Location: include/linux/perf_event.h:954
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8100eee0)
Location: include/linux/perf_event.h:954
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff8101099a)
Location: include/linux/perf_event.h:954
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81011ebc)
Location: include/linux/perf_event.h:954
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff811b365c)
Location: include/linux/perf_event.h:954
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff811e70ce)
Location: include/linux/perf_event.h:954
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81007d53)
Location: include/linux/perf_event.h:970
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a42c)
Location: include/linux/perf_event.h:970
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100ddd9)
Location: include/linux/perf_event.h:970
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f92a)
Location: include/linux/perf_event.h:970
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff81011b5b)
Location: include/linux/perf_event.h:970
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81013233)
Location: include/linux/perf_event.h:970
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff811c2abe)
Location: include/linux/perf_event.h:970
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff811fe700)
Location: include/linux/perf_event.h:970
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81007f73)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a9ec)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100e419)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8101000a)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff8101231b)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810139e3)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff811ce22e)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff8120b890)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81008fd3)
Location: include/linux/perf_event.h:1033
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100bc60)
Location: include/linux/perf_event.h:1033
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100f4f8)
Location: include/linux/perf_event.h:1033
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff810114ac)
Location: include/linux/perf_event.h:1033
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff8101378b)
Location: include/linux/perf_event.h:1033
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81015013)
Location: include/linux/perf_event.h:1033
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8101f891)
Location: include/linux/perf_event.h:1033
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff811ea0a7)
Location: include/linux/perf_event.h:1033
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff81237066)
Location: include/linux/perf_event.h:1033
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81008083)
Location: include/linux/perf_event.h:1044
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ac10)
Location: include/linux/perf_event.h:1044
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100eb13)
Location: include/linux/perf_event.h:1044
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff81010adc)
Location: include/linux/perf_event.h:1044
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff8101333b)
Location: include/linux/perf_event.h:1044
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810154b3)
Location: include/linux/perf_event.h:1044
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81020331)
Location: include/linux/perf_event.h:1044
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff811e71c3)
Location: include/linux/perf_event.h:1044
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff81240c66)
Location: include/linux/perf_event.h:1044
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff810088f3)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100b5a0)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100eedd)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff81011a9c)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff8101455f)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff8101672f)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102270e)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff811e8495)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff81244a16)
Location: include/linux/perf_event.h:1045
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81009723)
Location: include/linux/perf_event.h:1039
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ba90)
Location: include/linux/perf_event.h:1039
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100fa27)
Location: include/linux/perf_event.h:1039
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8101296c)
Location: include/linux/perf_event.h:1039
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff810158e9)
Location: include/linux/perf_event.h:1039
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810181ef)
Location: include/linux/perf_event.h:1039
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81026582)
Location: include/linux/perf_event.h:1039
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff81219115)
Location: include/linux/perf_event.h:1039
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff8127f9b6)
Location: include/linux/perf_event.h:1039
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81008dd9)
Location: include/linux/perf_event.h:1053
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/core.c (ffffffff8100af8b)
Location: include/linux/perf_event.h:1053
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c6ae)
Location: include/linux/perf_event.h:1053
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff81010fbc)
Location: include/linux/perf_event.h:1053
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8101465b)
Location: include/linux/perf_event.h:1053
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff810179b9)
Location: include/linux/perf_event.h:1053
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff8101a338)
Location: include/linux/perf_event.h:1053
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102a612)
Location: include/linux/perf_event.h:1053
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff812576e0)
Location: include/linux/perf_event.h:1053
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff812d4a0b)
Location: include/linux/perf_event.h:1053
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff8100a181)
Location: include/linux/perf_event.h:1151
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/core.c (ffffffff8100cef7)
Location: include/linux/perf_event.h:1151
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100f72b)
Location: include/linux/perf_event.h:1151
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff81015675)
Location: include/linux/perf_event.h:1151
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff81018866)
Location: include/linux/perf_event.h:1151
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff8101bc59)
Location: include/linux/perf_event.h:1151
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e478)
Location: include/linux/perf_event.h:1151
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81031202)
Location: include/linux/perf_event.h:1151
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff812a70e0)
Location: include/linux/perf_event.h:1151
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff8133cff7)
Location: include/linux/perf_event.h:1151
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81009988)
Location: include/linux/perf_event.h:1199
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/core.c (ffffffff8100c6a8)
Location: include/linux/perf_event.h:1199
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100ed0b)
Location: include/linux/perf_event.h:1199
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff81014edd)
Location: include/linux/perf_event.h:1199
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8101814e)
Location: include/linux/perf_event.h:1199
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff8101b91a)
Location: include/linux/perf_event.h:1199
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e167)
Location: include/linux/perf_event.h:1199
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8103122f)
Location: include/linux/perf_event.h:1199
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff812c92ab)
Location: include/linux/perf_event.h:1199
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff8136e167)
Location: include/linux/perf_event.h:1199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff8100f0a5)
Location: include/linux/perf_event.h:1215
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/core.c (ffffffff81011ea2)
Location: include/linux/perf_event.h:1215
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8101444b)
Location: include/linux/perf_event.h:1215
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff81019e98)
Location: include/linux/perf_event.h:1215
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8101dcce)
Location: include/linux/perf_event.h:1215
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff8102149a)
Location: include/linux/perf_event.h:1215
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81024237)
Location: include/linux/perf_event.h:1215
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81037524)
Location: include/linux/perf_event.h:1215
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff812e62eb)
Location: include/linux/perf_event.h:1215
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff81397297)
Location: include/linux/perf_event.h:1215
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/arm64/kernel/perf_event.c (ffff8000100a4904)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffff80001024db74)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffff80001029aa48)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/arm/kernel/perf_event_v7.c (c031880c)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/arm/kernel/perf_event_v7.c:armv7pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (c04811ec)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (c04c5004)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/powerpc/perf/core-book3s.c (c000000000128b6c)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:record_and_restart
```
```
In kernel/trace/bpf_trace.c (c0000000002ea3d8)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (c000000000342a94)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In kernel/events/core.c (ffffffe0001c6830)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81007f73)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a9ec)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100e419)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8101000a)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff8101231b)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810139e3)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff811c684e)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff81203eb0)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81006763)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff81009310)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100d079)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8100edaa)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff810111f7)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81012bce)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff811b962e)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff811f6c40)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81007f33)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a9ac)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100e3d9)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ffca)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff810122db)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff810139a3)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff811c461e)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff81201c80)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
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
In arch/x86/events/core.c (ffffffff81008093)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100a93c)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/core.c (ffffffff8100e5a9)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (ffffffff810101da)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/knc.c (ffffffff810124fb)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/p4.c (ffffffff81013bc3)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
```
In kernel/trace/bpf_trace.c (ffffffff811d1f3e)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
```
```
In kernel/events/core.c (ffffffff81211350)
Location: include/linux/perf_event.h:984
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
</details>
</li>
</ul>

## Differences
