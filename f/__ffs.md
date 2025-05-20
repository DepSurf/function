# Function: <code>__ffs</code>

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
In arch/x86/events/intel/pt.c (ffffffff81013651)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81f6b80e)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81f6bed5)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ae43b)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_show_task
```
```
In kernel/sched/rt.c (ffffffff810c001a)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/generic-chip.c (ffffffff810df6e1)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
```
```
In kernel/trace/trace_output.c (ffffffff811537b9)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_ctxwake_raw
  - kernel/trace/trace_output.c:trace_ctxwake_raw
  - kernel/trace/trace_output.c:trace_ctxwake_print
  - kernel/trace/trace_output.c:trace_ctxwake_print
  - kernel/trace/trace_output.c:trace_ctxwake_hex
  - kernel/trace/trace_output.c:trace_ctxwake_hex
```
```
In mm/filemap.c (ffffffff8118d29a)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_tag
```
```
In mm/page_alloc.c (ffffffff81f86dc6)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/shmem.c (ffffffff811a8a34)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
```
```
In mm/nobootmem.c (ffffffff81f8ab27)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - mm/nobootmem.c:__free_memory_core
```
```
In fs/fs-writeback.c (ffffffff8123a67d)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In security/keys/keyring.c (ffffffff81330d06)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/radix-tree.c (ffffffff813ee5c6)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
```
```
In lib/clz_ctz.c (ffffffff813fddb1)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzsi2
  - lib/clz_ctz.c:__ctzdi2
```
```
In lib/find_bit.c (ffffffff813fdedb)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
```
```
In lib/assoc_array.c (ffffffff81405572)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/gpio/gpio-intel-mid.c (ffffffff81429b2d)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/gpio/gpio-intel-mid.c:intel_mid_irq_handler
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8142a5b4)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
```
```
In drivers/pci/setup-bus.c (ffffffff8143f44a)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/iommu/iommu.c (ffffffff8152a712)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/iommu/amd_iommu.c (ffffffff8152ea35)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:amd_iommu_map
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8158875f)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff81593a59)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff815cb26a)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81646f6e)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In drivers/md/dm-stripe.c (ffffffff816a7fbe)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/clk/clk-divider.c (ffffffff816e8fcb)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/ras/ras.c (ffffffff816f3b1f)
Location: arch/x86/include/asm/bitops.h:346
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
In arch/x86/events/intel/pt.c (ffffffff810141ae)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81f93b34)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81f9422d)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b0deb)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_show_task
```
```
In kernel/sched/rt.c (ffffffff810c3fd6)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/generic-chip.c (ffffffff810e5051)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
```
```
In kernel/trace/trace_output.c (ffffffff8115d874)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_ctxwake_hex
  - kernel/trace/trace_output.c:trace_ctxwake_hex
  - kernel/trace/trace_output.c:trace_ctxwake_raw
  - kernel/trace/trace_output.c:trace_ctxwake_raw
  - kernel/trace/trace_output.c:trace_ctxwake_print
  - kernel/trace/trace_output.c:trace_ctxwake_print
```
```
In mm/filemap.c (ffffffff811a08cc)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_tag
```
```
In mm/page_alloc.c (ffffffff81fb0b99)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/shmem.c (ffffffff811bfa55)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
```
```
In mm/nobootmem.c (ffffffff81fb476d)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - mm/nobootmem.c:__free_memory_core
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812627a9)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In security/keys/keyring.c (ffffffff81365a86)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/radix-tree.c (ffffffff81434d14)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/gcd.c (ffffffff81441934)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - lib/gcd.c:gcd
  - lib/gcd.c:gcd
  - lib/gcd.c:gcd
```
```
In lib/clz_ctz.c (ffffffff81445471)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff8144554b)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
```
```
In lib/assoc_array.c (ffffffff8144d125)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814753d2)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
```
```
In drivers/pci/setup-bus.c (ffffffff8148b319)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/iommu/iommu.c (ffffffff8157df41)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/iommu/amd_iommu.c (ffffffff81582ab6)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_unmap_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/mfd/twl4030-irq.c (ffffffff815dd7e2)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff815e88f9)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81623a8a)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816aadcf)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/md/dm-stripe.c (ffffffff8170847f)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/clk/clk-divider.c (ffffffff8174d3fa)
Location: arch/x86/include/asm/bitops.h:346
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/ras/ras.c (ffffffff81757fad)
Location: arch/x86/include/asm/bitops.h:346
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
In arch/x86/events/intel/pt.c (ffffffff8101432e)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81fcf140)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81fcf839)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b7091)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_show_task
```
```
In kernel/sched/rt.c (ffffffff810ca03b)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/generic-chip.c (ffffffff810eb961)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/trace/trace_output.c (ffffffff811682e4)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_ctxwake_hex
  - kernel/trace/trace_output.c:trace_ctxwake_hex
  - kernel/trace/trace_output.c:trace_ctxwake_raw
  - kernel/trace/trace_output.c:trace_ctxwake_raw
  - kernel/trace/trace_output.c:trace_ctxwake_print
  - kernel/trace/trace_output.c:trace_ctxwake_print
```
```
In mm/filemap.c (ffffffff811b04b8)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_tag
```
```
In mm/page_alloc.c (ffffffff81fecea8)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/page-writeback.c (ffffffff811be236)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811cff3c)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In mm/nobootmem.c (ffffffff81ff115e)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/nobootmem.c:__free_memory_core
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81275bfe)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In security/keys/keyring.c (ffffffff8137c2a6)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/radix-tree.c (ffffffff81451189)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:__radix_tree_next_slot
```
```
In lib/gcd.c (ffffffff8145eb44)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/gcd.c:gcd
  - lib/gcd.c:gcd
  - lib/gcd.c:gcd
```
```
In lib/clz_ctz.c (ffffffff81463c61)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff81463d3b)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
```
```
In lib/assoc_array.c (ffffffff8146bae5)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814979a2)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
```
```
In drivers/pci/setup-bus.c (ffffffff814acb09)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/clk/clk-divider.c (ffffffff81535c6a)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iommu.c (ffffffff815aa4e1)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/iommu/amd_iommu.c (ffffffff815aed96)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_unmap_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8160a472)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff81615709)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8165460a)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d8f0f)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/hwmon/hwmon.c (ffffffff8171440c)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/md/dm-stripe.c (ffffffff8173a34f)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/ras/ras.c (ffffffff8178458b)
Location: arch/x86/include/asm/bitops.h:359
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
In arch/x86/events/intel/pt.c (ffffffff8101294c)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff820afb85)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff820b0298)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b33b9)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810c4c2d)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/generic-chip.c (ffffffff810eb1f1)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In kernel/trace/trace_output.c (ffffffff8116b424)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_ctxwake_hex
  - kernel/trace/trace_output.c:trace_ctxwake_hex
  - kernel/trace/trace_output.c:trace_ctxwake_raw
  - kernel/trace/trace_output.c:trace_ctxwake_raw
  - kernel/trace/trace_output.c:trace_ctxwake_print
  - kernel/trace/trace_output.c:trace_ctxwake_print
```
```
In mm/filemap.c (ffffffff811b7640)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_tag
```
```
In mm/page_alloc.c (ffffffff820ceb16)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/page-writeback.c (ffffffff811c642d)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811d9697)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In mm/nobootmem.c (ffffffff820d38a4)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - mm/nobootmem.c:free_all_bootmem
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81282f84)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In security/keys/keyring.c (ffffffff8138ff46)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/gcd.c (ffffffff81463ea4)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/gcd.c:gcd
  - lib/gcd.c:gcd
  - lib/gcd.c:gcd
```
```
In lib/clz_ctz.c (ffffffff81468d11)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff81468ddb)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
  - lib/find_bit.c:_find_next_bit
```
```
In lib/assoc_array.c (ffffffff81471209)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814a165f)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
```
```
In drivers/pci/setup-bus.c (ffffffff814b6e60)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/clk/clk-divider.c (ffffffff81548fc4)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iommu.c (ffffffff815c0171)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c684b)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8161e572)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff81629689)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81668c61)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (ffffffff8168f610)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816ed3cf)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/hwmon/hwmon.c (ffffffff8172c8f6)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/md/dm-stripe.c (ffffffff81753e2f)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/ras/ras.c (ffffffff817a3c82)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
```
In lib/idr.c (ffffffff818ece63)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/idr.c:ida_get_new_above
```
```
In lib/radix-tree.c (ffffffff818f2caf)
Location: arch/x86/include/asm/bitops.h:359
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:__radix_tree_next_slot
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
In arch/x86/events/intel/lbr.c (ffffffff8101061e)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
```
In arch/x86/events/intel/pt.c (ffffffff81012a1c)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff826b6391)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff826b6aa4)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810cc2e3)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/generic-chip.c (ffffffff810f3751)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In mm/filemap.c (ffffffff811cbcf8)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page_alloc.c (ffffffff826d7531)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/page-writeback.c (ffffffff811db24d)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811ee953)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In mm/percpu.c (ffffffff811f8149)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In mm/nobootmem.c (ffffffff826dc2c4)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - mm/nobootmem.c:free_all_bootmem
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a5ae3)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In security/keys/keyring.c (ffffffff813b5479)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/gcd.c (ffffffff8148fe10)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - lib/gcd.c:gcd
  - lib/gcd.c:gcd
  - lib/gcd.c:gcd
```
```
In lib/clz_ctz.c (ffffffff81494fc1)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff81495098)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
  - lib/find_bit.c:_find_next_bit
```
```
In lib/assoc_array.c (ffffffff8149d9d9)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814e0022)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
```
```
In drivers/pci/setup-bus.c (ffffffff814f6fb0)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/clk/clk-divider.c (ffffffff815ac541)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iommu.c (ffffffff81626831)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/iommu/iova.c (ffffffff81629773)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162d5eb)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81686db2)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff81691fa9)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff816d2311)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (ffffffff816f90a0)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81759bb6)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/hwmon/hwmon.c (ffffffff8179e0b8)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/md/dm-stripe.c (ffffffff817c5fdf)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In drivers/ras/ras.c (ffffffff8181ae16)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
```
In lib/idr.c (ffffffff81972e83)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - lib/idr.c:ida_get_new_above
```
```
In lib/radix-tree.c (ffffffff81979119)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free_cmn
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:__radix_tree_next_slot
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
In arch/x86/events/intel/lbr.c (ffffffff81011299)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
```
In arch/x86/events/intel/pt.c (ffffffff826d269e)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff826e00d0)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff826e02cd)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In kernel/sched/rt.c (ffffffff810d4002)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/generic-chip.c (ffffffff810fb92e)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81115e2a)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In mm/filemap.c (ffffffff811ecab9)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page_alloc.c (ffffffff8270196c)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/page-writeback.c (ffffffff811fc4e4)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (0)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
```
```
In mm/percpu.c (ffffffff812193f0)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
```
```
In mm/nobootmem.c (ffffffff82706782)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - mm/nobootmem.c:free_all_bootmem
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
```
```
In mm/memfd.c (ffffffff81294430)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/fs-writeback.c (ffffffff812cc6ab)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In security/keys/keyring.c (ffffffff813e5cce)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/gcd.c (ffffffff814c4c00)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - lib/gcd.c:gcd
  - lib/gcd.c:gcd
  - lib/gcd.c:gcd
```
```
In lib/clz_ctz.c (ffffffff814ca2f0)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff814ca446)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
```
In lib/assoc_array.c (ffffffff814d32c1)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8150f3c2)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_irq_handler
```
```
In drivers/pci/setup-bus.c (ffffffff81527b49)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/clk/clk-divider.c (ffffffff815e46c2)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iommu.c (ffffffff8166144c)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/iommu/iova.c (ffffffff81664455)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff816680bb)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816c2eea)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff816ce0d4)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8170ea44)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (ffffffff81736216)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8179a12d)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/hwmon/hwmon.c (ffffffff817e5475)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/md/dm-stripe.c (ffffffff8180eecd)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
```
```
In drivers/ras/ras.c (ffffffff8186513e)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
```
In lib/idr.c (ffffffff819cf44b)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - lib/idr.c:ida_get_new_above
```
```
In lib/radix-tree.c (ffffffff819d58f9)
Location: arch/x86/include/asm/bitops.h:363
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:__radix_tree_next_slot
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
In arch/x86/events/intel/lbr.c (ffffffff810118f9)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
```
In arch/x86/events/intel/pt.c (ffffffff828889ae)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff82896090)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff8289628d)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In kernel/sched/rt.c (ffffffff810ddca2)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/generic-chip.c (ffffffff811070fe)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8112125a)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In mm/filemap.c (ffffffff811fdfb3)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - mm/filemap.c:find_get_entries_tag
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page_alloc.c (ffffffff828b966e)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/page-writeback.c (ffffffff8120eb35)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In mm/percpu.c (ffffffff8122c350)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In mm/memblock.c (ffffffff828be5e9)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memfd.c (ffffffff812a90d1)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/fs-writeback.c (ffffffff812e183e)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8130ee5d)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In security/keys/keyring.c (ffffffff814004ae)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/gcd.c (ffffffff814d92f0)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - lib/gcd.c:gcd
  - lib/gcd.c:gcd
  - lib/gcd.c:gcd
```
```
In lib/clz_ctz.c (ffffffff814df010)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff814df166)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
```
In lib/assoc_array.c (ffffffff814e7c21)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/pci/setup-bus.c (ffffffff8153d9ce)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/clk/clk-divider.c (ffffffff815feab2)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iommu.c (ffffffff8167f950)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/iommu/iova.c (ffffffff816825e5)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff816863fb)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816e42da)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff816ef6f4)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81730ed4)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (ffffffff81759236)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817c055d)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff828ea994)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/hwmon/hwmon.c (ffffffff81810f0e)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/md/dm-stripe.c (ffffffff8183aead)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In drivers/ras/ras.c (ffffffff81884d0e)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In lib/radix-tree.c (ffffffff81a0db4e)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/xarray.c (ffffffff81a17974)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
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
In arch/x86/events/intel/lbr.c (ffffffff810120aa)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
```
In arch/x86/events/intel/pt.c (ffffffff8289fb45)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff828adc3d)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828ade37)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff8108e219)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In kernel/sched/rt.c (ffffffff810e4ca9)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/generic-chip.c (ffffffff811106db)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8112ba7b)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In mm/filemap.c (ffffffff812151ba)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff8121e735)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
```
```
In mm/percpu.c (ffffffff8123e759)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/page_alloc.c (ffffffff828d675e)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/memblock.c (ffffffff828d77b6)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memfd.c (ffffffff812c5593)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff812ffdb7)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81334b44)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In security/keys/keyring.c (ffffffff8142c765)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/clz_ctz.c (ffffffff8150aec0)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff8150af81)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
```
In lib/math/gcd.c (ffffffff815106a0)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffff815145b7)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/pci/setup-bus.c (ffffffff8156d064)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/clk/clk-divider.c (ffffffff8163119c)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iommu.c (ffffffff816b6d34)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
```
In drivers/iommu/iova.c (ffffffff816b9e05)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bdcbb)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8171d96a)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff81728e25)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8176c67e)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (ffffffff81795ca0)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817ff9fb)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff829053cd)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/hwmon/hwmon.c (ffffffff81852d96)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
```
```
In drivers/md/dm-stripe.c (ffffffff8187da58)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
```
```
In drivers/ras/ras.c (ffffffff818cf40f)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
```
```
In lib/radix-tree.c (ffffffff81a7d48b)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/xarray.c (ffffffff81a875dc)
Location: arch/x86/include/asm/bitops.h:234
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
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
In arch/x86/events/intel/lbr.c (ffffffff81012868)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
```
In arch/x86/events/intel/pt.c (ffffffff828a2c17)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff828b0f81)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b117b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff8108ee79)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In kernel/sched/rt.c (ffffffff810ee14d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/generic-chip.c (ffffffff8111c93b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81137b1b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In mm/filemap.c (ffffffff8122306c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff8122c1d5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/percpu.c (ffffffff8124cbb9)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/page_alloc.c (ffffffff828debef)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/memblock.c (ffffffff828dfc27)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memfd.c (ffffffff812d6f99)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff813125bd)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8134871c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In security/keys/keyring.c (ffffffff814464b5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/clz_ctz.c (ffffffff81528ce0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff81528da1)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
```
In lib/math/gcd.c (ffffffff8152e5a0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffff81534ff7)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/pci/setup-bus.c (ffffffff8158e044)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/clk/clk-divider.c (ffffffff81652ecc)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iommu.c (ffffffff816d98c2)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
```
In drivers/iommu/iova.c (ffffffff816dcc05)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e0eaf)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81741c3a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff8174d075)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff817906ee)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (ffffffff817b9710)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d54c5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183085b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8290ee08)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/hwmon/hwmon.c (ffffffff81884951)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/md/dm-stripe.c (ffffffff818af838)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/ras/ras.c (ffffffff819017ff)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/radix-tree.c (ffffffff81ab47c1)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/xarray.c (ffffffff81abe87c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
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
In arch/x86/events/intel/lbr.c (ffffffff81013cea)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
```
In arch/x86/events/intel/pt.c (ffffffff8101674e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff82cd5f77)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:print_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff82cd62eb)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff81095229)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In kernel/sched/rt.c (ffffffff810f7b11)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
```
```
In kernel/irq/generic-chip.c (ffffffff81128a4b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81146783)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In mm/filemap.c (ffffffff81250967)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff81259295)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/percpu.c (ffffffff8127ae98)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/page_alloc.c (ffffffff82cfbfd2)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/memblock.c (ffffffff82cfc938)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memblock.c:free_low_memory_core_early
```
```
In mm/memfd.c (ffffffff8130c120)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8134bda3)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8138e12d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In security/keys/keyring.c (ffffffff81497935)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/clz_ctz.c (ffffffff8158c5b0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff8158c671)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
```
```
In lib/math/gcd.c (ffffffff81592480)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffff815990ed)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/lz4/lz4_compress.c (ffffffff815a5706)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/radix-tree.c (ffffffff815ef0b8)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/xarray.c (ffffffff815fbe64)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
```
```
In drivers/gpio/gpio-msic.c (ffffffff8161925a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/gpio/gpio-msic.c:msic_bus_sync_unlock
```
```
In drivers/pci/setup-bus.c (ffffffff81635cc7)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/clk/clk-divider.c (ffffffff81702b0e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iommu.c (ffffffff8178e862)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
```
```
In drivers/iommu/dma-iommu.c (ffffffff81792ade)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/iommu/iova.c (ffffffff81793bc5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/iommu/amd/iommu.c (ffffffff81795f5f)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_unmap_page
  - drivers/iommu/amd/iommu.c:iommu_map_page
  - drivers/iommu/amd/iommu.c:fetch_pte
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817ff75a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff8180b143)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
```
In drivers/ata/libata-sata.c (ffffffff8186786d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (ffffffff81880bea)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a03da)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81901c0d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff82d22a55)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/hwmon/hwmon.c (ffffffff81953169)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_genattrs
```
```
In drivers/md/dm-stripe.c (ffffffff8197fabc)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/ras/ras.c (ffffffff819d8a37)
Location: arch/x86/include/asm/bitops.h:233
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
In arch/x86/events/intel/lbr.c (ffffffff81013a4a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
```
In arch/x86/events/intel/pt.c (ffffffff81016bee)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043f53)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_supervisor_to_kernel
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff82fc1f3a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:print_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff82fc22ae)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810944e1)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In kernel/sched/rt.c (ffffffff810f5d11)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
```
```
In kernel/irq/generic-chip.c (ffffffff8112434b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81143173)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In mm/filemap.c (ffffffff8125b414)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff81263881)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/percpu.c (ffffffff812858a8)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/page_alloc.c (ffffffff82fe89f2)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/memblock.c (ffffffff82fe9361)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memblock.c:free_low_memory_core_early
```
```
In mm/memfd.c (ffffffff81317fe0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff81358fc9)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8139f89a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In security/keys/keyring.c (ffffffff814b53a5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/clz_ctz.c (ffffffff815a9020)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff815a90e1)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
```
```
In lib/math/gcd.c (ffffffff815aefd9)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffff815b4aed)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/lz4/lz4_compress.c (ffffffff815c1286)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_continue
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize_generic
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/radix-tree.c (ffffffff81613808)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/xarray.c (ffffffff81620a04)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
```
```
In drivers/gpio/gpio-msic.c (ffffffff8163fa8a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/gpio/gpio-msic.c:msic_bus_sync_unlock
```
```
In drivers/pci/setup-bus.c (ffffffff8165ad87)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/clk/clk-divider.c (ffffffff8171fc0e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a467f)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_unmap_page
  - drivers/iommu/amd/iommu.c:iommu_map_page
  - drivers/iommu/amd/iommu.c:fetch_pte
```
```
In drivers/iommu/iommu.c (ffffffff817baaa2)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
```
```
In drivers/iommu/dma-iommu.c (ffffffff817bdb2e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/iommu/iova.c (ffffffff817c0155)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/mfd/twl4030-irq.c (ffffffff818109fa)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff8181a8c2)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
```
In drivers/ata/libata-sata.c (ffffffff8187667d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (ffffffff8188f31a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818aedbc)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_populate_bitmap_full
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8190a4d9)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8301084e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/hwmon/hwmon.c (ffffffff81957fd9)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_genattrs
```
```
In drivers/md/dm-stripe.c (ffffffff81983eac)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/ras/ras.c (ffffffff819d7de7)
Location: arch/x86/include/asm/bitops.h:233
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
In arch/x86/events/core.c (ffffffff81008c1c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
```
```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff831bc762)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/events/intel/knc.c (ffffffff8101451c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/lbr.c (ffffffff81014c2a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
```
In arch/x86/events/intel/p4.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff810190c8)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101b3fc)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810206d9)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff831bf825)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/topology.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045c53)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_supervisor_to_kernel
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054b85)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff831cc56a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:print_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff831cc8e5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065720)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff81094e48)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/reboot.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810f8071)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/topology.c (ffffffff81bceb4c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/sched/stats.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/debug.c (ffffffff811064f5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/debug.c:sd_flags_show
  - kernel/sched/debug.c:sd_flags_show
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/power/poweroff.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/resend.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/generic-chip.c (ffffffff8112469b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/migration.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff81130a14)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/time/timer.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81143beb)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In kernel/time/clocksource.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81175409)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/cgroup/rdma.c (ffffffff8117a8d0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff81208f1b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/events/core.c (ffffffff8123fe05)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/core.c:perf_output_sample_regs
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/oom_kill.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/page-writeback.c (ffffffff81268505)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/vmscan.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/mmzone.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/percpu.c (ffffffff8128a0f3)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/compaction.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/list_lru.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/page_alloc.c (ffffffff831f329c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/memblock.c (ffffffff831f42c4)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81c2d03e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/frontswap.c (ffffffff812d33ac)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81c326b4)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/memfd.c (ffffffff8131e1d0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dcache.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8135fb2d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/buffer.c (ffffffff81371077)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/io-wq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In fs/dax.c (ffffffff813a6645)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In security/keys/keyring.c (ffffffff814bb245)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In security/selinux/ss/ebitmap.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In security/selinux/ss/mls.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In block/blk-mq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In block/blk-mq-cpumap.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/clz_ctz.c (ffffffff815b3c60)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff815b3d21)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/find_bit.c:_find_first_bit
  - lib/find_bit.c:_find_next_bit
```
```
In lib/math/gcd.c (ffffffff815b9d89)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffff815bf931)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/pldmfw/pldmfw.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/radix-tree.c (ffffffff815f6d4c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/vsprintf.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/xarray.c (ffffffff81602f44)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
```
```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff816125ed)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81622ea4)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/pci/search.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pci/setup-bus.c (ffffffff8163d2d5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/pci/pcie/rcec.c (ffffffff816427eb)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff81beb198)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165eca5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/acpi/sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pnp/manager.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pnp/support.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pnp/interface.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff81700e5d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/dma/dmaengine.c (ffffffff8170568c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/xen/events/events_2l.c (ffffffff81719d67)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a6ae)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/char/hpet.c (ffffffff81775d9b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/char/hpet.c:hpet_timer_set_irq
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178c2c3)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_page
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
```
```
In drivers/iommu/intel/iommu.c (ffffffff81793ef5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8179d3b1)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a0d6e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
```
In drivers/iommu/iova.c (ffffffff817a32c5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/cacheinfo.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/base/node.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817f517a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff817fdfe2)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
```
In drivers/nvdimm/core.c (ffffffff818008b9)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/core.c:commands_show
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81804553)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:commands_show
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff818329cc)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/ata/libata-sata.c (ffffffff81858ead)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/net/phy/phy-c45.c (ffffffff81871c5b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818914b4)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818d837a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818eea91)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/usb/host/xhci-hub.c (ffffffff8190475f)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81907fa7)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8321b829)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/input/input.c (ffffffff81914198)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
```
```
In drivers/input/ff-core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/input/misc/uinput.c (ffffffff81920cce)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81932242)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
```
```
In drivers/hwmon/hwmon.c (ffffffff8193bc14)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_genattrs
```
```
In drivers/md/dm-stripe.c (ffffffff8196829c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/opp/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/ras/ras.c (ffffffff819bdf57)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
```
In net/core/dev.c (ffffffff819e7af0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down_reason
  - net/core/dev.c:dev_change_proto_down_reason
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/core/devlink.c (ffffffff81a4a313)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_reload_stats_update
  - net/core/devlink.c:__devlink_reload_stats_update
```
```
In net/ethtool/ioctl.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/ncsi/ncsi-manage.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
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
In arch/x86/events/core.c (ffffffff81009a98)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
```
```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8329ca84)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/events/intel/knc.c (ffffffff8101589c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/lbr.c (ffffffff81016033)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
```
In arch/x86/events/intel/p4.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101afec)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101dd74)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102432d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8329fd52)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/topology.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105d4d5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff832ade29)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:print_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff832ae8eb)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106f81e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810a4dd5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/reboot.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/rt.c (ffffffff811136d5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/topology.c (ffffffff81ca7110)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/sched/stats.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/debug.c (ffffffff811241a5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/debug.c:sd_flags_show
  - kernel/sched/debug.c:sd_flags_show
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/isolation.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/power/poweroff.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/resend.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/generic-chip.c (ffffffff81144cbe)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/migration.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff81152627)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/time/timer.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff811672bc)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In kernel/time/clocksource.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8119c95b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/cgroup/rdma.c (ffffffff811a2220)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff8123ca26)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/events/core.c (ffffffff8127a6a5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/core.c:perf_output_sample_regs
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/oom_kill.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/page-writeback.c (ffffffff812a6339)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/vmscan.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/mmzone.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/percpu.c (ffffffff812c9bd3)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/compaction.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/list_lru.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/page_alloc.c (ffffffff832d9396)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/memblock.c (ffffffff832da699)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81d4b912)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/frontswap.c (ffffffff81318e2c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81d50fb6)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/memfd.c (ffffffff8136b58c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dcache.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813ae3c5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff813c0a8a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/io-wq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In fs/dax.c (ffffffff813f60b5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In security/keys/keyring.c (ffffffff81513a75)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In security/selinux/ss/ebitmap.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In security/selinux/ss/mls.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In block/blk-mq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In block/blk-mq-cpumap.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/clz_ctz.c (ffffffff81619e50)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff81619f11)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/find_bit.c:_find_first_bit
  - lib/find_bit.c:_find_next_bit
```
```
In lib/math/gcd.c (ffffffff816206ea)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffff81627261)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/ubsan.c (ffffffff81cdea4b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
```
```
In lib/pldmfw/pldmfw.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/radix-tree.c (ffffffff8166446f)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/vsprintf.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/xarray.c (ffffffff81671402)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
```
```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff816817ed)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81692605)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/pci/search.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pci/setup-bus.c (ffffffff816add62)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/pci/pcie/rcec.c (ffffffff816b34ed)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff816b65fc)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/pcie/aer.c:__aer_print_error
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d1865)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/acpi/sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pnp/manager.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pnp/support.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pnp/interface.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff8177b691)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/dma/dmaengine.c (ffffffff81780f76)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/xen/events/events_2l.c (ffffffff8179805c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
```
In drivers/xen/events/events_fifo.c (ffffffff81798e50)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/regulator/irq_helpers.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/char/hpet.c (ffffffff817fbb0b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/char/hpet.c:hpet_timer_set_irq
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180e8a2)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff818135c3)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_page
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
  - drivers/iommu/amd/io_pgtable.c:first_pte_l7
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181a9d5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap_pages
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81826086)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_pgsize
  - drivers/iommu/iommu.c:iommu_pgsize
```
```
In drivers/iommu/dma-iommu.c (ffffffff81829dc2)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/iommu/iova.c (ffffffff8182cb95)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8182eb13)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
```
```
In drivers/base/cacheinfo.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/base/node.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8187e21e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff81887e54)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
```
In drivers/nvdimm/core.c (ffffffff8188acb9)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/core.c:commands_show
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e6d3)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:commands_show
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff818bea1c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/ata/libata-sata.c (ffffffff818e7925)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/net/phy/phy-c45.c (ffffffff819027f6)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81924f16)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_populate_bitmap
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8197318a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8198b29e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/usb/host/xhci-hub.c (ffffffff819a4e6d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-trace.c (ffffffff819a87d6)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8330545e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/input/input.c (ffffffff819b62b5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
```
```
In drivers/input/ff-core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/input/misc/uinput.c (ffffffff819c3a61)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d5589)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
```
```
In drivers/hwmon/hwmon.c (ffffffff819e0468)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_genattrs
```
```
In drivers/md/dm-stripe.c (ffffffff81a106ac)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/opp/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/ras/ras.c (ffffffff81a6d507)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
```
In net/core/dev.c (ffffffff81a98f01)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down_reason
  - net/core/dev.c:dev_change_proto_down_reason
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/core/devlink.c (ffffffff81b02373)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_reload_stats_update
  - net/core/devlink.c:__devlink_reload_stats_update
```
```
In net/ethtool/ioctl.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/ncsi/ncsi-manage.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/power/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
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
In arch/x86/events/core.c (ffffffff81009195)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:perf_clear_dirty_counters
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
  - arch/x86/events/core.c:__perf_sched_find_counter
```
```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/events/amd/ibs.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8344b540)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_arch_events_quirk
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
```
```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/events/intel/knc.c (ffffffff8101796a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
```
```
In arch/x86/events/intel/lbr.c (ffffffff81018135)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
```
In arch/x86/events/intel/p4.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/events/intel/pt.c (ffffffff8101d5e0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
```
```
In arch/x86/events/intel/uncore.c (ffffffff81020816)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102810d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8344eb8d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_arch_events_quirk
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81056654)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:xfeature_get_offset
  - arch/x86/kernel/fpu/xstate.c:xfeature_get_offset
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/amd.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/hygon.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81069a23)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
  - arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8345ed6a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:print_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff8345f8f7)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/kernel/cpu/resctrl/core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107d0c5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/apic/msi.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810b96af)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/reboot.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff81138415)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
```
In kernel/sched/build_utility.c (ffffffff8347d734)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sd_flags_show
  - kernel/sched/build_utility.c:sd_flags_show
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/power/snapshot.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/power/poweroff.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/resend.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/chip.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/generic-chip.c (ffffffff81168f6e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/irq_sim.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/migration.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/cpuhotplug.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/irq/matrix.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff8117aa47)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/time/timer.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8119ac5c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In kernel/time/clocksource.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/tick-broadcast.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811ccc26)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_release
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_can_fork
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_propagate_control
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/cgroup/rdma.c (ffffffff811d2c89)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/trace/pid_list.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff8124b8fe)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:div_by_power_of_two
  - kernel/trace/trace_events_hist.c:hist_field_div
```
```
In kernel/bpf/verifier.c (ffffffff8127fdb2)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/events/core.c (ffffffff812cdede)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample_regs
  - kernel/events/core.c:perf_output_sample_regs
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/watch_queue.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/oom_kill.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/page-writeback.c (ffffffff812fc7c2)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/readahead.c (ffffffff81301ca0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
```
```
In mm/vmscan.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/mmzone.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/percpu.c (ffffffff81328150)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/compaction.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/list_lru.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/page_alloc.c (ffffffff8348e2af)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
  - mm/page_alloc.c:split_free_page
```
```
In mm/memblock.c (ffffffff8348f7af)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81f1b224)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81f211d8)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:altmap_alloc_block_buf
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/kfence/core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/memfd.c (ffffffff813e95ff)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/dcache.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In fs/fs-writeback.c (ffffffff814326e6)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff81445a26)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
```
In fs/dax.c (ffffffff81469c8c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In security/keys/keyring.c (ffffffff815a5f75)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In security/selinux/ss/ebitmap.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In security/selinux/ss/mls.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In security/landlock/fs.c (ffffffff8163af33)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:collect_domain_accesses
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
```
```
In block/blk-mq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In block/blk-mq-tag.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In block/blk-mq-cpumap.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In io_uring/io-wq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/clz_ctz.c (ffffffff816e7320)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff816e7436)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/find_bit.c:_find_first_and_bit
  - lib/find_bit.c:_find_first_bit
  - lib/find_bit.c:_find_next_bit
```
```
In lib/math/gcd.c (ffffffff816ee7da)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffff816f7d71)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/genalloc.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/ubsan.c (ffffffff81ea4f43)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
```
```
In lib/pldmfw/pldmfw.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/nmi_backtrace.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/radix-tree.c (ffffffff8177e78f)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/vsprintf.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/xarray.c (ffffffff8178ae8a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
```
```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179c7db)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff817b3092)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
```
```
In drivers/pci/pci-driver.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pci/search.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pci/setup-bus.c (ffffffff817d1205)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/pci/pcie/rcec.c (ffffffff817d68db)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pci/pcie/aer.c (ffffffff817da05e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:__aer_print_error
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa92c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
```
In drivers/acpi/sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/acpi/numa/hmat.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pnp/manager.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pnp/support.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/pnp/interface.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff818b1f5e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/dma/dmaengine.c (ffffffff818b7798)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
```
```
In drivers/dma/lgm/lgm-dma.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/xen/events/events_2l.c (ffffffff818d1380)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d2013)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/regulator/irq_helpers.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/tty/n_tty.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/char/hpet.c (ffffffff8193a943)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/char/hpet.c:hpet_timer_set_irq
```
```
In drivers/iommu/amd/iommu.c (ffffffff8194fb7b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff819545dd)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_page
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
  - drivers/iommu/amd/io_pgtable.c:first_pte_l7
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195b115)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap_pages
  - drivers/iommu/intel/iommu.c:intel_iommu_map_pages
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81966338)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_pgsize
  - drivers/iommu/iommu.c:iommu_pgsize
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196a212)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/iommu/iova.c (ffffffff8196de35)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8196ff08)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
```
```
In drivers/base/cacheinfo.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/base/node.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/mfd/twl4030-irq.c (ffffffff819c66fe)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff819d0ebd)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
```
In drivers/nvdimm/core.c (ffffffff819d43ea)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:commands_show
  - drivers/nvdimm/core.c:commands_show
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7d33)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:commands_show
  - drivers/nvdimm/dimm_devs.c:commands_show
```
```
In drivers/nvdimm/nd_perf.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/scsi/scsi_debugfs.c (ffffffff81a0ae0a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
```
```
In drivers/ata/libata-sata.c (ffffffff81a390da)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/net/phy/phy-c45.c (ffffffff81a54863)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7ab2f)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_populate_bitmap
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81acea3b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae6b51)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81b0283d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
```
```
In drivers/usb/host/xhci-trace.c (ffffffff81b072e8)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
  - drivers/usb/host/xhci-trace.c:xhci_decode_ctrl_ctx
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff834be57a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_map_pci_mmio
```
```
In drivers/input/input.c (ffffffff81b15a88)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_estimate_events_per_packet
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
  - drivers/input/input.c:input_dev_toggle
```
```
In drivers/input/ff-core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/input/misc/uinput.c (ffffffff81b2451a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b37fa1)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_handle_tx_abort
```
```
In drivers/hwmon/hwmon.c (ffffffff81b4514f)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_genattrs
```
```
In drivers/md/dm-stripe.c (ffffffff81b78918)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/opp/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/cpufreq/speedstep-centrino.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/devfreq/governor_passive.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/ras/ras.c (ffffffff81bde659)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
```
In net/core/dev.c (ffffffff81c1dfdf)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_proto_down_reason
  - net/core/dev.c:dev_change_proto_down_reason
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/core/devlink.c (ffffffff81c85dc5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_reload_stats_update
  - net/core/devlink.c:__devlink_reload_stats_update
```
```
In net/ethtool/ioctl.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/ncsi/ncsi-manage.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In net/mctp/route.c (ffffffff81e3a7a1)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
```
```
In arch/x86/power/cpu.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:aarch64_encode_immediate
  - arch/arm64/kernel/insn.c:aarch64_encode_immediate
```
```
In arch/arm64/kernel/module-plts.c (ffff8000100a2b14)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In arch/arm64/kernel/hw_breakpoint.c (ffff8000100a58ec)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - arch/arm64/kernel/hw_breakpoint.c:watchpoint_handler
  - arch/arm64/kernel/hw_breakpoint.c:arch_bp_generic_fields
```
```
In virt/kvm/arm/arm.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In virt/kvm/arm/mmu.c (ffff8000100cc19c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_arch_mmu_enable_log_dirty_pt_masked
```
```
In virt/kvm/arm/vgic/vgic-mmio-v2.c (ffff8000100e38a0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-mmio-v2.c:vgic_mmio_write_target
```
```
In virt/kvm/arm/hyp/vgic-v3-sr.c (ffff800010dac23c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_write_eoir
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_write_eoir
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_get_highest_active_priority
```
```
In kernel/signal.c (ffff80001010b808)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/rt.c (ffff80001014ee0c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/manage.c (ffff80001017b79c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/generic-chip.c (ffff800010180d48)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In kernel/time/hrtimer.c (ffff8000101a10ec)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In mm/filemap.c (ffff8000102b0530)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffff8000102ba960)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/backing-dev.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In mm/percpu.c (ffff8000102e21b8)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/page_alloc.c (ffff800011457950)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/memblock.c (ffff800011458db0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memfd.c (ffff80001037bfbc)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffff8000103c790c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffff80001040972c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/binfmt_elf.c (ffff800010420278)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffff800010421b44)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_psinfo
```
```
In fs/squashfs/super.c (ffff8000104dd3ac)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In security/keys/keyring.c (ffff80001052f978)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In block/blk-flush.c (ffff8000105e7144)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/clz_ctz.c (ffff800010633618)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffff800010633754)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
```
In lib/math/gcd.c (ffff80001063aafc)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/irqchip/qcom-irq-combiner.c (ffff80001067ba70)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_handle_irq
```
```
In drivers/pinctrl/core.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/pinctrl/pinmux.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff80001069add0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069cacc)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (ffff8000106b7860)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106ce3b0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:gpio_irq_handler
```
```
In drivers/gpio/gpio-stmpe.c (ffff8000106d47e0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq
```
```
In drivers/gpio/gpio-tc3589x.c (ffff8000106d5558)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
```
```
In drivers/pci/setup-bus.c (ffff8000106f3394)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071aefc)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/pci/controller/pcie-rcar.c (ffff8000107212f4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
```
```
In drivers/clk/clk-divider.c (ffff8000107c38d8)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/clk/renesas/rcar-gen3-cpg.c (ffff8000107eafc0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-gen3-cpg.c:cpg_z_clk_recalc_rate
```
```
In drivers/iommu/iommu.c (ffff8000108c5704)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca6bc)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb06c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/iommu/iova.c (ffff8000108cd2fc)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d62d8)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev
```
```
In drivers/mfd/stmpe.c (ffff80001092f3c0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/stmpe.c:stmpe_set_altfunc
```
```
In drivers/mfd/tc3589x.c (ffff800010930b00)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq
```
```
In drivers/mfd/twl4030-irq.c (ffff80001093d670)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffff80001094b788)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/ata/libata-core.c (ffff80001099a360)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a6b74c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/hwmon/hwmon.c (ffff800010ad1528)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/md/md-bitmap.c (ffff800010af9330)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/md/dm-stripe.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/mailbox/ti-msgmgr.c (ffff800010b7d094)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_startup
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_last_tx_done
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_peek_data
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_rx_interrupt
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In net/ipv4/devinet.c (ffff800010ca85f0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffff800010cb44bc)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In lib/idr.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In lib/radix-tree.c (ffff800010d8ecd0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/xarray.c (ffff800010d99b88)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
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
In arch/arm/kernel/process.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In arch/arm/probes/kprobes/actions-common.c (c0ea0cf0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - arch/arm/probes/kprobes/actions-common.c:simulate_ldm1stm1
```
```
In arch/arm/mach-omap2/omap_hwmod.c (c0337840)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In arch/arm/mach-omap2/prm2xxx_3xxx.c (c03406f4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_clkdm_read_wkdep
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_read_mem_retst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_read_mem_pwrst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_set_mem_retst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_pwrdm_set_mem_onst
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_deassert_hardreset
  - arch/arm/mach-omap2/prm2xxx_3xxx.c:omap2_prm_is_hardreset_asserted
```
```
In arch/arm/mach-omap2/prm3xxx.c (c0340dbc)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm3xxx.c:omap3_pwrdm_read_prev_mem_pwrst
```
```
In arch/arm/mach-omap2/cm3xxx.c (c034141c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_disable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_clk_enable
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_allow_idle
  - arch/arm/mach-omap2/cm3xxx.c:omap3xxx_clkdm_read_sleepdep
```
```
In arch/arm/mach-omap2/cminst44xx.c (c0341ba4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cminst44xx.c:omap4_clkdm_read_wkup_sleep_dep
```
```
In arch/arm/mach-omap2/prm44xx.c (c034285c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_read_mem_retst
  - arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_read_mem_pwrst
  - arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_set_mem_retst
  - arch/arm/mach-omap2/prm44xx.c:omap4_pwrdm_set_mem_onst
```
```
In arch/arm/mach-omap2/prm33xx.c (c034371c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_mem_retst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_mem_pwrst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_mem_retst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_mem_onst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_read_logic_retst
  - arch/arm/mach-omap2/prm33xx.c:am33xx_pwrdm_set_logic_retst
```
```
In arch/arm/mach-omap2/cm33xx.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In arch/arm/mach-omap2/vc.c (c1517204)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - arch/arm/mach-omap2/vc.c:omap_vc_init_channel
  - arch/arm/mach-omap2/vc.c:omap_vc_init_channel
  - arch/arm/mach-omap2/vc.c:omap_vc_init_channel
  - arch/arm/mach-omap2/vc.c:omap_vc_init_channel
  - arch/arm/mach-omap2/vc.c:omap_vc_init_channel
  - arch/arm/mach-omap2/vc.c:omap_vc_init_channel
```
```
In arch/arm/mach-omap2/vp.c (c0344840)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - arch/arm/mach-omap2/vp.c:omap_vp_update_errorgain
  - arch/arm/mach-omap2/vp.c:omap_vp_init
  - arch/arm/mach-omap2/vp.c:_vp_set_init_voltage
```
```
In arch/arm/mach-omap2/powerdomains3xxx_data.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In kernel/signal.c (c0364970)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In kernel/sched/rt.c (c039d254)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/manage.c (c03ccaa4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/generic-chip.c (c03d0f44)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In kernel/time/hrtimer.c (c03ead24)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In mm/backing-dev.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In mm/percpu.c (c05064dc)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/memblock.c (c1532d1c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In fs/binfmt_elf.c (c05e64c4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_psinfo
```
```
In fs/binfmt_elf_fdpic.c (c05e9748)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:fill_psinfo
```
```
In fs/squashfs/super.c (c069eea0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In security/keys/keyring.c (c06e7c70)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In block/blk-flush.c (c0793dc8)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/clz_ctz.c (c07d9a80)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (c07d9c04)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
```
```
In lib/math/gcd.c (c07e0bf4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (c07e739c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/irqchip/exynos-combiner.c (c08139dc)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/irqchip/exynos-combiner.c:combiner_handle_cascade_irq
```
```
In drivers/irqchip/irq-gic.c (c0815c80)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_migrate_target
  - drivers/irqchip/irq-gic.c:gic_get_cpu_id
```
```
In drivers/bus/omap_l3_smx.c (c0825d4c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/bus/omap_l3_smx.c:omap3_l3_app_irq
```
```
In drivers/bus/omap_l3_noc.c (c0825fb0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/bus/omap_l3_noc.c:l3_interrupt_handler
  - drivers/bus/omap_l3_noc.c:l3_interrupt_handler
```
```
In drivers/pinctrl/core.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/pinctrl/pinmux.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c0838918)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
```
```
In drivers/pinctrl/pinctrl-single.c (c08401c8)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
```
In drivers/pinctrl/aspeed/pinmux-aspeed.c (c0847638)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pinctrl/aspeed/pinmux-aspeed.c:aspeed_sig_desc_eval
  - drivers/pinctrl/aspeed/pinmux-aspeed.c:aspeed_sig_desc_eval
```
```
In drivers/pinctrl/aspeed/pinctrl-aspeed-g6.c (c0847828)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pinctrl/aspeed/pinctrl-aspeed-g6.c:aspeed_g6_sig_expr_set
```
```
In drivers/pinctrl/ti/pinctrl-ti-iodelay.c (c08568b4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_pinconf_group_set
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_pinconf_group_set
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_pinconf_group_set
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_pinconf_group_set
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (c0858518)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
```
```
In drivers/gpio/gpio-omap.c (c086d274)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_handler
```
```
In drivers/gpio/gpio-stmpe.c (c086fc20)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq
```
```
In drivers/gpio/gpio-tc3589x.c (c0870838)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
```
```
In drivers/pci/setup-bus.c (c088dde4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/pci/endpoint/pci-epc-core.c (c08a4c80)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/pci/controller/pcie-rcar.c (c08ae63c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
```
```
In drivers/clk/clk-divider.c (c08ef8d4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/clk/ti/divider.c (c09167b4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/clk/ti/divider.c:ti_clk_divider_set_rate
```
```
In drivers/clk/ti/apll.c (c0917604)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/clk/ti/apll.c:omap2_apll_set_autoidle
  - drivers/clk/ti/apll.c:omap2_apll_enable
  - drivers/clk/ti/apll.c:omap2_apll_recalc
  - drivers/clk/ti/apll.c:dra7_apll_is_enabled
  - drivers/clk/ti/apll.c:dra7_apll_disable
  - drivers/clk/ti/apll.c:dra7_apll_enable
  - drivers/clk/ti/apll.c:dra7_apll_enable
  - drivers/clk/ti/apll.c:dra7_apll_enable
```
```
In drivers/clk/ti/clkt_dpll.c (c0917a48)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/clk/ti/clkt_dpll.c:omap2_get_dpll_rate
  - drivers/clk/ti/clkt_dpll.c:omap2_get_dpll_rate
  - drivers/clk/ti/clkt_dpll.c:omap2_get_dpll_rate
  - drivers/clk/ti/clkt_dpll.c:omap2_get_dpll_rate
  - drivers/clk/ti/clkt_dpll.c:omap2_init_dpll_parent
  - drivers/clk/ti/clkt_dpll.c:omap2_init_dpll_parent
```
```
In drivers/clk/ti/dpll3xxx.c (c0919980)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/clk/ti/dpll3xxx.c:omap3_noncore_dpll_restore_context
  - drivers/clk/ti/dpll3xxx.c:omap3_noncore_dpll_restore_context
  - drivers/clk/ti/dpll3xxx.c:omap3_noncore_dpll_restore_context
  - drivers/clk/ti/dpll3xxx.c:omap3_noncore_dpll_save_context
  - drivers/clk/ti/dpll3xxx.c:omap3_noncore_dpll_save_context
  - drivers/clk/ti/dpll3xxx.c:omap3_noncore_dpll_save_context
  - drivers/clk/ti/dpll3xxx.c:omap3_core_dpll_restore_context
  - drivers/clk/ti/dpll3xxx.c:omap3_core_dpll_restore_context
  - drivers/clk/ti/dpll3xxx.c:omap3_clkoutx2_recalc
  - drivers/clk/ti/dpll3xxx.c:omap3_dpll_allow_idle
  - drivers/clk/ti/dpll3xxx.c:omap3_dpll_autoidle_read
  - drivers/clk/ti/dpll3xxx.c:omap3_noncore_dpll_program
  - drivers/clk/ti/dpll3xxx.c:omap3_noncore_dpll_program
  - drivers/clk/ti/dpll3xxx.c:omap3_noncore_dpll_program
  - drivers/clk/ti/dpll3xxx.c:omap3_noncore_dpll_program
  - drivers/clk/ti/dpll3xxx.c:omap3_noncore_dpll_program
  - drivers/clk/ti/dpll3xxx.c:_omap3_wait_dpll_status
  - drivers/clk/ti/dpll3xxx.c:_omap3_dpll_write_clken
```
```
In drivers/dma/ti/edma.c (c092f700)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:dma_irq_handler
  - drivers/dma/ti/edma.c:edma_prep_dma_memcpy
```
```
In drivers/dma/ti/omap-dma.c (c09325e0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_prep_dma_memcpy
```
```
In drivers/regulator/ti-abb-regulator.c (c095620c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_init_table
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
  - drivers/regulator/ti-abb-regulator.c:ti_abb_set_voltage_sel
```
```
In drivers/iommu/iommu.c (c09bc4ec)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:iommu_group_create_direct_mappings
```
```
In drivers/iommu/io-pgtable-arm.c (c09bfcc4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/iommu/exynos-iommu.c (c09c9508)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq
```
```
In drivers/mfd/stmpe.c (c0a10a84)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/stmpe.c:stmpe_set_altfunc
```
```
In drivers/mfd/tc3589x.c (c0a11e0c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq
```
```
In drivers/mfd/twl4030-irq.c (c0a260ac)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (c0a34720)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/ata/libata-core.c (c0a6a4b0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (c0b3e6c4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/hwmon/hwmon.c (c0bb2370)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
```
```
In drivers/md/md-bitmap.c (c0bda448)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/md/dm-stripe.c (c0be4bb4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/opp/ti-opp-supply.c (c0bf7a4c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In sound/core/pcm_native.c (c0c93bac)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_hw_params
  - sound/core/pcm_native.c:snd_pcm_hw_params
  - sound/core/pcm_native.c:snd_pcm_hw_params
```
```
In sound/core/pcm_lib.c (c0c99fc0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:snd_pcm_lib_ioctl
  - sound/core/pcm_lib.c:snd_pcm_hw_param_first
```
```
In sound/core/pcm_iec958.c (c0c9c7c4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - sound/core/pcm_iec958.c:snd_pcm_create_iec958_consumer_hw_params
```
```
In sound/core/pcm_dmaengine.c (c0c9cbb4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - sound/core/pcm_dmaengine.c:snd_hwparams_to_dma_slave_config
```
```
In sound/soc/soc-dapm.c (c0ca903c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:snd_soc_dai_link_event
  - sound/soc/soc-dapm.c:snd_soc_dai_link_event
```
```
In sound/soc/soc-utils.c (c0cadd94)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - sound/soc/soc-utils.c:snd_soc_params_to_frame_size
```
```
In sound/soc/soc-pcm.c (c0cb15b0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - sound/soc/soc-pcm.c:dpcm_show_state
  - sound/soc/soc-pcm.c:dpcm_show_state
  - sound/soc/soc-pcm.c:dpcm_fe_dai_hw_params
  - sound/soc/soc-pcm.c:soc_pcm_hw_params
  - sound/soc/soc-pcm.c:soc_pcm_hw_params
  - sound/soc/soc-pcm.c:soc_pcm_hw_params
```
```
In sound/soc/codecs/sgtl5000.c (c0cbf3b0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - sound/soc/codecs/sgtl5000.c:sgtl5000_pcm_hw_params
```
```
In sound/soc/fsl/fsl_ssi.c (c0cc12e8)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_hw_params
```
```
In net/ipv4/devinet.c (c0db4f18)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (c0dbf8a8)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In lib/idr.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In lib/radix-tree.c (c0e893d4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
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
In arch/powerpc/mm/book3s64/slb.c (c00000000008eaf0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/slb.c:slb_insert_entry
```
```
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a0850)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
```
```
In arch/powerpc/mm/hugetlbpage.c (c000000001357ca0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:add_huge_page_size
  - arch/powerpc/mm/hugetlbpage.c:huge_pte_alloc
```
```
In kernel/signal.c (c000000000153460)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/rt.c (c0000000001a3224)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/manage.c (c0000000001d5f30)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/generic-chip.c (c0000000001dc2c0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In kernel/time/hrtimer.c (c000000000202604)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In mm/filemap.c (c0000000003658d0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (c000000000373488)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/backing-dev.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In mm/percpu.c (c0000000003a21a0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/page_alloc.c (c000000001380f9c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/memblock.c (c0000000013826c8)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memfd.c (c000000000471450)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (c0000000004c90e0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (c000000000514b1c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/binfmt_elf.c (c00000000052f17c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In fs/compat_binfmt_elf.c (c000000000532dac)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In fs/squashfs/super.c (c000000000618dc8)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In security/keys/keyring.c (c00000000067c874)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In block/blk-flush.c (c00000000077b900)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/clz_ctz.c (c0000000007d8900)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (c0000000007d8ac0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
```
In lib/math/gcd.c (c0000000007e1ab8)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (c0000000007ec424)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/pinctrl/core.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/pinctrl/pinmux.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (c0000000008350d4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
```
In drivers/gpio/gpio-stmpe.c (c00000000084b890)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq
```
```
In drivers/gpio/gpio-tc3589x.c (c00000000084ca50)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
```
```
In drivers/pci/setup-bus.c (c0000000008716f4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/pci/endpoint/pci-epc-core.c (c00000000088b640)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/iommu/iommu.c (c00000000096b1dc)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:iommu_group_create_direct_mappings
```
```
In drivers/mfd/stmpe.c (c0000000009cf000)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/stmpe.c:stmpe_set_altfunc
```
```
In drivers/mfd/tc3589x.c (c0000000009d0bd0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq
```
```
In drivers/mfd/twl4030-irq.c (c0000000009e5560)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (c0000000009f7324)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/ata/libata-core.c (c000000000a5d7dc)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3cf98)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/hwmon/hwmon.c (c000000000bb6158)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In drivers/md/md-bitmap.c (c000000000be7510)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/md/dm-stripe.c (c000000000bf70b0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In net/ipv4/devinet.c (c000000000dbd5f4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (c000000000dcc8b4)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
```
In lib/idr.c (0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
```
```
In lib/radix-tree.c (c000000000ed1aa0)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/xarray.c (c000000000edfa9c)
Location: include/asm-generic/bitops/builtin-__ffs.h:11
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
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
In arch/riscv/net/bpf_jit_comp.c (ffffffe0000ba6d6)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - arch/riscv/net/bpf_jit_comp.c:emit_imm
```
```
In kernel/signal.c (ffffffe0000cdd3c)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - kernel/signal.c:next_signal
```
```
In kernel/sched/rt.c (ffffffe0000f7ca6)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/manage.c (ffffffe000114f90)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/generic-chip.c (ffffffe0001190de)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_gc_get_irq_data
```
```
In kernel/time/hrtimer.c (ffffffe00012decc)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__next_base
```
```
In mm/filemap.c (ffffffe0001d60ac)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffe0001ddc8a)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/backing-dev.c (0)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
```
```
In mm/percpu.c (ffffffe0001f8e66)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/page_alloc.c (ffffffe0000163ba)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/memblock.c (ffffffe00001734c)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memfd.c (ffffffe00025257c)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffe00028626c)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffe0002b41a0)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/binfmt_elf.c (ffffffe0002c112c)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
```
```
In fs/squashfs/super.c (ffffffe000351e68)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In security/keys/keyring.c (ffffffe000390e54)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In crypto/algapi.c (ffffffe0003fe9aa)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_xor
```
```
In block/blk-flush.c (ffffffe000427c14)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
```
```
In lib/clz_ctz.c (ffffffe000461622)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffe000461722)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
```
In lib/math/gcd.c (ffffffe000466fb2)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffe00046de3a)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/pinctrl/core.c (0)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
```
```
In drivers/pinctrl/pinmux.c (0)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a0c04)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
```
In drivers/gpio/gpio-stmpe.c (ffffffe0004af852)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq
```
```
In drivers/gpio/gpio-tc3589x.c (ffffffe0004b03f0)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq
```
```
In drivers/pci/setup-bus.c (ffffffe0004c6630)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffe0004e24c2)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/clk/clk-divider.c (ffffffe000511198)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/mfd/stmpe.c (ffffffe0005a5db2)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq
  - drivers/mfd/stmpe.c:stmpe_set_altfunc
```
```
In drivers/mfd/tc3589x.c (ffffffe0005a6fe6)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq
```
```
In drivers/mfd/twl4030-irq.c (ffffffe0005b1618)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffe0005bccaa)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq
```
```
In drivers/ata/libata-core.c (ffffffe0005fac88)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000680a7c)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_frame_skel_link
```
```
In drivers/hwmon/hwmon.c (ffffffe0006cdea6)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffe0006eb592)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In drivers/md/dm-stripe.c (ffffffe0006f52ec)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
```
```
In net/ipv4/devinet.c (ffffffe0008034cc)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffe00080c102)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In lib/idr.c (0)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
```
```
In lib/radix-tree.c (ffffffe0008b749e)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/xarray.c (ffffffe0008c32d4)
Location: include/asm-generic/bitops/__ffs.h:13
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xas_find_marked
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
In arch/x86/events/intel/lbr.c (ffffffff81012868)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
```
In arch/x86/events/intel/pt.c (ffffffff82890c17)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8289efa0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff8289f19a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff8108de39)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In kernel/sched/rt.c (ffffffff810e7e4a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/generic-chip.c (ffffffff81114f1b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff811302cb)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In mm/filemap.c (ffffffff8121b6bc)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff81224825)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/percpu.c (ffffffff81245209)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/page_alloc.c (ffffffff828c7aa3)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/memblock.c (ffffffff828c8adb)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memfd.c (ffffffff812cf579)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8130ab9d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81340cfc)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In security/keys/keyring.c (ffffffff8143ea95)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/clz_ctz.c (ffffffff815212c0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff81521381)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
```
In lib/math/gcd.c (ffffffff81526b80)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffff8152d5d7)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/pci/setup-bus.c (ffffffff81581ec4)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/clk/clk-divider.c (ffffffff81618f2c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iommu.c (ffffffff8169f312)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
```
In drivers/iommu/iova.c (ffffffff816a2655)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a68ff)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/ata/libata-core.c (ffffffff8175582e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (ffffffff8177e1e0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e8c3b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/hwmon/hwmon.c (ffffffff8182a7d1)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/md/dm-stripe.c (ffffffff818556b8)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/radix-tree.c (ffffffff81a53611)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/xarray.c (ffffffff81a5d6cc)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
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
In arch/x86/events/intel/lbr.c (ffffffff81011798)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
```
In arch/x86/events/intel/pt.c (ffffffff8288eafe)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8289716d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff82897367)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff8107c949)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In kernel/sched/rt.c (ffffffff810d749d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/generic-chip.c (ffffffff81105c2b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81122d3b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In mm/filemap.c (ffffffff8120e8ac)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff812179cf)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/percpu.c (ffffffff812381b9)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/page_alloc.c (ffffffff828c01c8)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/memblock.c (ffffffff828c1200)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memfd.c (ffffffff812c01f7)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff812fb7bd)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff813316e0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In security/keys/keyring.c (ffffffff8142f505)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/clz_ctz.c (ffffffff815115b0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff81511671)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
```
In lib/math/gcd.c (ffffffff81516e60)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffff8151d8b7)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/pci/setup-bus.c (ffffffff81570ca4)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/clk/clk-divider.c (ffffffff8160d45c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iommu.c (ffffffff8167cd02)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
```
In drivers/iommu/iova.c (ffffffff81680045)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff816842ef)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/ata/libata-core.c (ffffffff817356ce)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (ffffffff8175df80)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177f575)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/hwmon/hwmon.c (ffffffff817f1e61)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/md/dm-stripe.c (ffffffff8181ccc8)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/radix-tree.c (ffffffff81a10711)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/xarray.c (ffffffff81a1a79c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
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
In arch/x86/events/intel/lbr.c (ffffffff81012828)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
```
In arch/x86/events/intel/pt.c (ffffffff828a3c17)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff828b1f63)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b215d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff8108dde9)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In kernel/sched/rt.c (ffffffff810e467d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/generic-chip.c (ffffffff81112e0b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8112dfeb)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In mm/filemap.c (ffffffff8121945c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff812225c5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/percpu.c (ffffffff81242fa9)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/page_alloc.c (ffffffff828da823)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/memblock.c (ffffffff828db85b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memfd.c (ffffffff812cd389)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8130898d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff8133e7cc)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In security/keys/keyring.c (ffffffff8143ac35)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/clz_ctz.c (ffffffff8151d350)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff8151d411)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
```
In lib/math/gcd.c (ffffffff81522c10)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffff81529667)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/pci/setup-bus.c (ffffffff81581d94)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/clk/clk-divider.c (ffffffff81646d0c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iommu.c (ffffffff816cd582)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
```
In drivers/iommu/iova.c (ffffffff816d08c5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d4b6f)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817350fa)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff81740535)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8178556e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (ffffffff817ae590)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817ca345)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818256db)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/hwmon/hwmon.c (ffffffff81879e01)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/md/dm-stripe.c (ffffffff818a4ce8)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/ras/ras.c (ffffffff818f221f)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/radix-tree.c (ffffffff81abfa01)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/xarray.c (ffffffff81ac9abc)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
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
In arch/x86/events/intel/lbr.c (ffffffff81012a48)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
```
```
In arch/x86/events/intel/pt.c (ffffffff828a3c2b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff828b1f91)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b218b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810901c9)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
  - arch/x86/mm/mem_encrypt.c:force_dma_unencrypted
```
```
In kernel/sched/rt.c (ffffffff810f0b0a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
```
```
In kernel/irq/generic-chip.c (ffffffff8111e64b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8113a96b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_next_event_base
```
```
In mm/filemap.c (ffffffff81228564)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_range_tag
```
```
In mm/page-writeback.c (ffffffff812319a7)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/backing-dev.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In mm/percpu.c (ffffffff81252739)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update
  - mm/percpu.c:pcpu_block_update
```
```
In mm/page_alloc.c (ffffffff828dfc44)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/page_alloc.c:node_map_pfn_alignment
```
```
In mm/memblock.c (ffffffff828e0c7c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memfd.c (ffffffff812de105)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/fs-writeback.c (ffffffff8131a60d)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff81351659)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In security/keys/keyring.c (ffffffff81451d85)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_diff_objects
```
```
In lib/clz_ctz.c (ffffffff81536bc0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/clz_ctz.c:__ctzdi2
  - lib/clz_ctz.c:__ctzsi2
```
```
In lib/find_bit.c (ffffffff81536c81)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_bit
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
```
In lib/math/gcd.c (ffffffff8153c590)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
  - lib/math/gcd.c:gcd
```
```
In lib/assoc_array.c (ffffffff81543047)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
```
In drivers/pci/setup-bus.c (ffffffff8159c244)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
```
```
In drivers/clk/clk-divider.c (ffffffff8166129c)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iommu.c (ffffffff816e7a92)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
```
```
In drivers/iommu/iova.c (ffffffff816eae55)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
```
```
In drivers/iommu/amd_iommu.c (ffffffff816ef26f)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8175053a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_pih
```
```
In drivers/mfd/tps6586x.c (ffffffff8175b975)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8179f39e)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_complete_multiple
```
```
In drivers/net/phy/phy-c45.c (ffffffff817c8520)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e45e5)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183f05b)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8290fe6a)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
```
In drivers/hwmon/hwmon.c (ffffffff81895801)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/md/dm-stripe.c (ffffffff818c0f28)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_ctr
  - drivers/md/dm-stripe.c:stripe_ctr
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In drivers/ras/ras.c (ffffffff8191329f)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - drivers/ras/ras.c:perf_trace_extlog_mem_event
  - drivers/ras/ras.c:trace_event_raw_event_extlog_mem_event
```
```
In lib/idr.c (0)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
```
```
In lib/radix-tree.c (ffffffff81acbed1)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_next_chunk
```
```
In lib/xarray.c (ffffffff81ad600f)
Location: arch/x86/include/asm/bitops.h:233
Inline: True
Inline callers:
  - lib/xarray.c:xa_extract
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_find_marked
```
</details>
</li>
</ul>

## Differences
