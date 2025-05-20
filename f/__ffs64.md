# Function: <code>__ffs64</code>

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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81f6b80e)
Location: include/linux/bitops.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In lib/clz_ctz.c (ffffffff813fde01)
Location: include/linux/bitops.h:202
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ras/ras.c (ffffffff816f3b1f)
Location: include/linux/bitops.h:202
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81f93b34)
Location: include/linux/bitops.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In lib/clz_ctz.c (ffffffff81445471)
Location: include/linux/bitops.h:202
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ras/ras.c (ffffffff81757fad)
Location: include/linux/bitops.h:202
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81fcf140)
Location: include/linux/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In lib/clz_ctz.c (ffffffff81463c61)
Location: include/linux/bitops.h:218
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ras/ras.c (ffffffff8178458b)
Location: include/linux/bitops.h:218
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff820afb85)
Location: include/linux/bitops.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In lib/clz_ctz.c (ffffffff81468d11)
Location: include/linux/bitops.h:218
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ras/ras.c (ffffffff817a3c82)
Location: include/linux/bitops.h:218
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff826b6391)
Location: include/linux/bitops.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In lib/clz_ctz.c (ffffffff81494fc1)
Location: include/linux/bitops.h:220
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ras/ras.c (ffffffff8181ae16)
Location: include/linux/bitops.h:220
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff826e00d0)
Location: include/linux/bitops.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In lib/clz_ctz.c (ffffffff814ca2f0)
Location: include/linux/bitops.h:220
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-core.c (ffffffff8170ea44)
Location: include/linux/bitops.h:220
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ras/ras.c (ffffffff8186513e)
Location: include/linux/bitops.h:220
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff82896090)
Location: include/linux/bitops.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In lib/clz_ctz.c (ffffffff814df010)
Location: include/linux/bitops.h:201
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-core.c (ffffffff81730ed4)
Location: include/linux/bitops.h:201
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff828ea994)
Location: include/linux/bitops.h:201
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/ras/ras.c (ffffffff81884d0e)
Location: include/linux/bitops.h:201
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff828adc3d)
Location: include/linux/bitops.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff8108e219)
Location: include/linux/bitops.h:201
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In lib/clz_ctz.c (ffffffff8150aec0)
Location: include/linux/bitops.h:201
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-core.c (ffffffff8176c67e)
Location: include/linux/bitops.h:201
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff829053cd)
Location: include/linux/bitops.h:201
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/ras/ras.c (ffffffff818cf40f)
Location: include/linux/bitops.h:201
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff828b0f81)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff8108ee79)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In lib/clz_ctz.c (ffffffff81528ce0)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-core.c (ffffffff817906ee)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8290ee08)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/ras/ras.c (ffffffff819017ff)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff82cd5f77)
Location: include/linux/bitops.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:print_mtrr_state
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff81095229)
Location: include/linux/bitops.h:223
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In lib/clz_ctz.c (ffffffff8158c5b0)
Location: include/linux/bitops.h:223
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-sata.c (ffffffff8186786d)
Location: include/linux/bitops.h:223
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff82d22a55)
Location: include/linux/bitops.h:223
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/ras/ras.c (ffffffff819d8a37)
Location: include/linux/bitops.h:223
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff82fc1f3a)
Location: include/linux/bitops.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:print_mtrr_state
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810944e1)
Location: include/linux/bitops.h:221
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In lib/clz_ctz.c (ffffffff815a9020)
Location: include/linux/bitops.h:221
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-sata.c (ffffffff8187667d)
Location: include/linux/bitops.h:221
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8301084e)
Location: include/linux/bitops.h:221
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/ras/ras.c (ffffffff819d7de7)
Location: include/linux/bitops.h:221
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff831cc56a)
Location: include/linux/bitops.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:print_mtrr_state
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff81094e48)
Location: include/linux/bitops.h:221
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In lib/clz_ctz.c (ffffffff815b3c60)
Location: include/linux/bitops.h:221
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-sata.c (ffffffff81858ead)
Location: include/linux/bitops.h:221
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8321b829)
Location: include/linux/bitops.h:221
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/ras/ras.c (ffffffff819bdf57)
Location: include/linux/bitops.h:221
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff832ade29)
Location: include/linux/bitops.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:print_mtrr_state
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810a4dd5)
Location: include/linux/bitops.h:222
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In lib/clz_ctz.c (ffffffff81619e50)
Location: include/linux/bitops.h:222
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-sata.c (ffffffff818e7925)
Location: include/linux/bitops.h:222
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8330545e)
Location: include/linux/bitops.h:222
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/ras/ras.c (ffffffff81a6d507)
Location: include/linux/bitops.h:222
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8345ed6a)
Location: include/linux/bitops.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:print_mtrr_state
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810b96af)
Location: include/linux/bitops.h:188
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In kernel/trace/trace_events_hist.c (ffffffff8124b8fe)
Location: include/linux/bitops.h:188
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:div_by_power_of_two
  - kernel/trace/trace_events_hist.c:hist_field_div
```
```
In lib/clz_ctz.c (ffffffff816e7320)
Location: include/linux/bitops.h:188
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-sata.c (ffffffff81a390da)
Location: include/linux/bitops.h:188
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff834be57a)
Location: include/linux/bitops.h:188
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/ras/ras.c (ffffffff81bde659)
Location: include/linux/bitops.h:188
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff83e80136)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:print_mtrr_state
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810d530f)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In kernel/trace/trace_events_hist.c (ffffffff8129d387)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
```
```
In lib/clz_ctz.c (ffffffff817d6ba0)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-sata.c (ffffffff81bbe15d)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff83efc412)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/ras/ras.c (ffffffff81d89a66)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/mm/mem_encrypt.c (ffffffff810d87ff)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In kernel/trace/trace_events_hist.c (ffffffff812baed0)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
```
```
In lib/clz_ctz.c (ffffffff81815bb0)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-sata.c (ffffffff81c159c9)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff83722212)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/ras/ras.c (ffffffff81df8066)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/mm/mem_encrypt.c (ffffffff810e107f)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In kernel/trace/trace_events_hist.c (ffffffff812d7520)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
```
```
In lib/clz_ctz.c (ffffffff8185ac90)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-sata.c (ffffffff81c6ab9e)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff83956042)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/ras/ras.c (ffffffff81eae776)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/arm64/kernel/insn.c (ffff800010096438)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:aarch64_encode_immediate
  - arch/arm64/kernel/insn.c:aarch64_encode_immediate
```
```
In lib/clz_ctz.c (ffff800010633618)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/pci/controller/pcie-rcar.c (ffff8000107212f4)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
```
```
In drivers/ata/libata-core.c (ffff80001099a360)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
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
In drivers/pci/controller/pcie-rcar.c (c08ae638)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
```
```
In drivers/ata/libata-core.c (c0a6a51c)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
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
In lib/clz_ctz.c (c0000000007d8900)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-core.c (c000000000a5d7dc)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/clz_ctz.c (ffffffe000461622)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-core.c (ffffffe0005fac88)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8289efa0)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff8108de39)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In lib/clz_ctz.c (ffffffff815212c0)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-core.c (ffffffff8175582e)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8289716d)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff8107c949)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In lib/clz_ctz.c (ffffffff815115b0)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-core.c (ffffffff817356ce)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff828b1f63)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff8108dde9)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In lib/clz_ctz.c (ffffffff8151d350)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-core.c (ffffffff8178556e)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/ras/ras.c (ffffffff818f221f)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff828b1f91)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810901c9)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In lib/clz_ctz.c (ffffffff81536bc0)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
```
```
In drivers/ata/libata-core.c (ffffffff8179f39e)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8290fe6a)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/ras/ras.c (ffffffff8191329f)
Location: include/linux/bitops.h:208
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
</details>
</li>
</ul>

## Differences
