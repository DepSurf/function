# Function: <code>kernel_ip</code>

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
In arch/x86/events/amd/ibs.c (0)
Location: arch/x86/events/perf_event.h:769
Inline: True
```
```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/perf_event.h:769
Inline: True
```
```
In arch/x86/events/intel/lbr.c (0)
Location: arch/x86/events/perf_event.h:769
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
In arch/x86/events/amd/ibs.c (0)
Location: arch/x86/events/perf_event.h:778
Inline: True
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f09b)
Location: arch/x86/events/perf_event.h:778
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (0)
Location: arch/x86/events/perf_event.h:778
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/perf_event.h:778
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
In arch/x86/events/amd/ibs.c (0)
Location: arch/x86/events/perf_event.h:781
Inline: True
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f15b)
Location: arch/x86/events/perf_event.h:781
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (0)
Location: arch/x86/events/perf_event.h:781
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/perf_event.h:781
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
In arch/x86/events/amd/ibs.c (0)
Location: arch/x86/events/perf_event.h:786
Inline: True
```
```
In arch/x86/events/intel/ds.c (ffffffff8100d8ab)
Location: arch/x86/events/perf_event.h:786
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (0)
Location: arch/x86/events/perf_event.h:786
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/perf_event.h:786
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
In arch/x86/events/amd/ibs.c (0)
Location: arch/x86/events/perf_event.h:796
Inline: True
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e02b)
Location: arch/x86/events/perf_event.h:796
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (0)
Location: arch/x86/events/perf_event.h:796
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/perf_event.h:796
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
In arch/x86/events/amd/ibs.c (ffffffff8100a2c6)
Location: arch/x86/events/perf_event.h:799
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ebb8)
Location: arch/x86/events/perf_event.h:799
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff810104e2)
Location: arch/x86/events/perf_event.h:799
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/events/intel/pt.c (ffffffff81012a86)
Location: arch/x86/events/perf_event.h:799
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
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
In arch/x86/events/amd/ibs.c (ffffffff8100a1f6)
Location: arch/x86/events/perf_event.h:817
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f088)
Location: arch/x86/events/perf_event.h:817
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff81010ac2)
Location: arch/x86/events/perf_event.h:817
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/events/intel/pt.c (ffffffff81013186)
Location: arch/x86/events/perf_event.h:817
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
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
In arch/x86/events/amd/ibs.c (ffffffff8100a6e3)
Location: arch/x86/events/perf_event.h:854
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f991)
Location: arch/x86/events/perf_event.h:854
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff81011c82)
Location: arch/x86/events/perf_event.h:854
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/events/intel/pt.c (ffffffff81014540)
Location: arch/x86/events/perf_event.h:854
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
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
In arch/x86/events/amd/ibs.c (ffffffff8100aca1)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81010071)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff81012442)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/events/intel/pt.c (ffffffff81014ec0)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
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
In arch/x86/events/amd/ibs.c (ffffffff8100beeb)
Location: arch/x86/events/perf_event.h:895
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81011512)
Location: arch/x86/events/perf_event.h:895
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff810138b9)
Location: arch/x86/events/perf_event.h:895
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/events/intel/pt.c (ffffffff81016784)
Location: arch/x86/events/perf_event.h:895
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
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
In arch/x86/events/amd/ibs.c (ffffffff8100ae89)
Location: arch/x86/events/perf_event.h:1026
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81010b42)
Location: arch/x86/events/perf_event.h:1026
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff810139f9)
Location: arch/x86/events/perf_event.h:1026
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/events/intel/pt.c (ffffffff81016c24)
Location: arch/x86/events/perf_event.h:1026
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
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
In arch/x86/events/amd/ibs.c (ffffffff8100b824)
Location: arch/x86/events/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81011b02)
Location: arch/x86/events/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff81014bb8)
Location: arch/x86/events/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/events/intel/pt.c (ffffffff81017f04)
Location: arch/x86/events/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
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
In arch/x86/events/amd/ibs.c (ffffffff8100bd2b)
Location: arch/x86/events/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff810129d2)
Location: arch/x86/events/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff81015f8d)
Location: arch/x86/events/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/events/intel/pt.c (ffffffff8101b031)
Location: arch/x86/events/perf_event.h:1155
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
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
In arch/x86/events/amd/brs.c (0)
Location: arch/x86/events/perf_event.h:1181
Inline: True
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100cada)
Location: arch/x86/events/perf_event.h:1181
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff810146c2)
Location: arch/x86/events/perf_event.h:1181
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff810180bc)
Location: arch/x86/events/perf_event.h:1181
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
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
In arch/x86/events/utils.c (ffffffff8100b10f)
Location: arch/x86/events/perf_event.h:1187
Inline: True
Inline callers:
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/utils.c:get_branch_type
```
```
In arch/x86/events/amd/brs.c (0)
Location: arch/x86/events/perf_event.h:1187
Inline: True
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100fb26)
Location: arch/x86/events/perf_event.h:1187
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8101889a)
Location: arch/x86/events/perf_event.h:1187
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101bf75)
Location: arch/x86/events/perf_event.h:1187
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
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
In arch/x86/events/utils.c (ffffffff8100a8df)
Location: arch/x86/events/perf_event.h:1192
Inline: True
Inline callers:
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/utils.c:get_branch_type
```
```
In arch/x86/events/amd/brs.c (0)
Location: arch/x86/events/perf_event.h:1192
Inline: True
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100f0b9)
Location: arch/x86/events/perf_event.h:1192
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8101817b)
Location: arch/x86/events/perf_event.h:1192
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101bc35)
Location: arch/x86/events/perf_event.h:1192
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
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
In arch/x86/events/utils.c (ffffffff8101004f)
Location: arch/x86/events/perf_event.h:1207
Inline: True
Inline callers:
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/utils.c:get_branch_type
```
```
In arch/x86/events/amd/brs.c (0)
Location: arch/x86/events/perf_event.h:1207
Inline: True
```
```
In arch/x86/events/amd/ibs.c (ffffffff810147f9)
Location: arch/x86/events/perf_event.h:1207
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8101dcfb)
Location: arch/x86/events/perf_event.h:1207
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff810217b5)
Location: arch/x86/events/perf_event.h:1207
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
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
In arch/x86/events/amd/ibs.c (ffffffff8100aca1)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81010071)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff81012442)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/events/intel/pt.c (ffffffff81014ec0)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
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
In arch/x86/events/amd/ibs.c (ffffffff810095d9)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ee11)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff81011372)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/events/intel/pt.c (ffffffff81014190)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
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
In arch/x86/events/amd/ibs.c (ffffffff8100ac61)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81010031)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff81012402)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/events/intel/pt.c (ffffffff81014e80)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
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
In arch/x86/events/amd/ibs.c (ffffffff8100abf1)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81010241)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_adaptive_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:setup_pebs_fixed_sample_data
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
  - arch/x86/events/intel/ds.c:intel_pmu_drain_bts_buffer
```
```
In arch/x86/events/intel/lbr.c (ffffffff81012622)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/events/intel/pt.c (ffffffff810150c0)
Location: arch/x86/events/perf_event.h:886
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
```
</details>
</li>
</ul>

## Differences
