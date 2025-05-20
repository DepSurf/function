# Function: <code>kzalloc_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100808d)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008ad8)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100c7b8)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:allocate_shared_regs
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d23c)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff810103e4)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff810143ac)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/rapl.c (ffffffff81014dfa)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:rapl_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015848)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810554f8)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056bfa)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In kernel/workqueue.c (ffffffff810985f8)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_worker
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/smpboot.c (ffffffff810a3bae)
Location: include/linux/slab.h:611
Inline: True
```
```
In kernel/sched/core.c (ffffffff810af203)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/sched/fair.c (ffffffff810beb3b)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/irq/irqdesc.c (ffffffff810da0d6)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff810e0b19)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/trace/ring_buffer.c (ffffffff811482a1)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/events/core.c (ffffffff8117ad64)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In kernel/events/ring_buffer.c (ffffffff81185af3)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff811902a8)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffffffff811cd838)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/nobootmem.c (ffffffff81208f0c)
Location: include/linux/slab.h:611
Inline: True
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
  - mm/nobootmem.c:__alloc_bootmem_low_node
```
```
In mm/memblock.c (ffffffff81f8b208)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - mm/memblock.c:memblock_virt_alloc_internal
```
```
In mm/sparse.c (ffffffff8181953d)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff811fad30)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
Direct callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In block/elevator.c (ffffffff813b3cd6)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff813bdd06)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff813c3b43)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-tag.c (ffffffff813c73cd)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_alloc
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-cpumap.c (ffffffff813c8796)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_make_queue_map
```
```
In block/genhd.c (ffffffff813cb4d6)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
  - block/genhd.c:alloc_disk_node
```
```
In block/partition-generic.c (ffffffff813cd480)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff813d7a33)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff813d9406)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:blk_throtl_init
```
```
In block/deadline-iosched.c (ffffffff813dcbed)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_init_queue
```
```
In block/cfq-iosched.c (ffffffff813df423)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_pd_alloc
```
```
In lib/genalloc.c (ffffffff814075c0)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/scsi/scsi_lib.c (ffffffff815aecf6)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_request
```
```
In drivers/md/dm-stats.c (ffffffff816ad0f5)
Location: include/linux/slab.h:611
Inline: True
```
```
In arch/x86/pci/acpi.c (ffffffff816f8efc)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
```
In net/core/sysctl_net_core.c (ffffffff81713440)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81717db9)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
```
```
In net/core/flow.c (ffffffff81734de2)
Location: include/linux/slab.h:611
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81741857)
Location: include/linux/slab.h:611
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
**Symbols:**

```
ffffffff81208f0c-ffffffff81208f1e: kzalloc_node.constprop.7 (STB_LOCAL)
ffffffff811fad30-ffffffff811fad42: kzalloc_node.constprop.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810082de)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008c29)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100caf9)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d406)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fdcd)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff810142ef)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014c68)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055798)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056e62)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In kernel/workqueue.c (ffffffff8109efd5)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff810a72ce)
Location: include/linux/slab.h:645
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b1a01)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/sched/fair.c (ffffffff810c242b)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/irq/irqdesc.c (ffffffff810df5d8)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff810e6bab)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff81150721)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff81196ecc)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff81197ace)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff811a42b5)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffffffff811ea90a)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/nobootmem.c (ffffffff8122ec64)
Location: include/linux/slab.h:645
Inline: True
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
```
```
In mm/memblock.c (ffffffff81fb4f0b)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - mm/memblock.c:memblock_virt_alloc_internal
```
```
In mm/sparse.c (ffffffff81893089)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff81fb7d41)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In block/elevator.c (ffffffff813f78d6)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff81401c66)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff814081b2)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In block/blk-mq-tag.c (ffffffff8140ba4e)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-cpumap.c (ffffffff8140c9f6)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_make_queue_map
```
```
In block/genhd.c (ffffffff8140f836)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (ffffffff814118bd)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff8141d733)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff81421e56)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/deadline-iosched.c (ffffffff8142283d)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_init_queue
```
```
In block/cfq-iosched.c (ffffffff81425971)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_pd_alloc
```
```
In lib/genalloc.c (ffffffff8144f42f)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In drivers/scsi/scsi_lib.c (ffffffff81606f56)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_request
```
```
In drivers/md/dm.c (ffffffff81704bfb)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-stats.c (ffffffff8170d692)
Location: include/linux/slab.h:645
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff8170fe74)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In arch/x86/pci/acpi.c (ffffffff8175dc09)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
```
In net/core/sysctl_net_core.c (ffffffff8177b0a1)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff8177ffb7)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
```
```
In net/core/flow.c (ffffffff817a0f62)
Location: include/linux/slab.h:645
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff817ae6e7)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
**Symbols:**

```
ffffffff8122ec64-ffffffff8122ec76: kzalloc_node.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810082fe)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008c69)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100cbc9)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d4c3)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ff44)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff810144c4)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014e48)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff8104328b)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81057de6)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059c12)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In kernel/workqueue.c (ffffffff810a3ecd)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff810acde8)
Location: include/linux/slab.h:645
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b7d24)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810c84d0)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/irq/irqdesc.c (ffffffff810e5d1b)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff810ed59b)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff8115b881)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff811a68dc)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff811a74be)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff811b4615)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffffffff811fbb8a)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/nobootmem.c (ffffffff812411bf)
Location: include/linux/slab.h:645
Inline: True
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
```
```
In mm/memblock.c (ffffffff81ff18f2)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - mm/memblock.c:memblock_virt_alloc_internal
```
```
In mm/sparse.c (ffffffff818c78d9)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff818c9080)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In block/elevator.c (ffffffff81411236)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff8141b8d6)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff81423173)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In block/blk-mq-tag.c (ffffffff8142616e)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff8142abc6)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (ffffffff8142cc4d)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff81438cf3)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff8143cfb6)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/deadline-iosched.c (ffffffff8143d95d)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_init_queue
```
```
In block/cfq-iosched.c (ffffffff81444731)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_pd_alloc
```
```
In lib/genalloc.c (ffffffff8146ddef)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In lib/sbitmap.c (ffffffff814820fb)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/lightnvm/core.c (ffffffff815c2be8)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/scsi/scsi_lib.c (ffffffff816366c6)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_request
```
```
In drivers/md/dm.c (ffffffff81736aab)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-stats.c (ffffffff8173f6f2)
Location: include/linux/slab.h:645
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff81741e54)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In arch/x86/pci/acpi.c (ffffffff8178a13d)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
```
In net/core/sysctl_net_core.c (ffffffff817a86fe)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff817ad6e1)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
```
```
In net/core/flow.c (ffffffff817cfb73)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_cpu_up_prep
```
```
In net/sched/sch_generic.c (ffffffff817ddd77)
Location: include/linux/slab.h:645
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
**Symbols:**

```
ffffffff810b0830-ffffffff810b0842: kzalloc_node.constprop.91 (STB_LOCAL)
ffffffff812411bf-ffffffff812411d1: kzalloc_node.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007fcf)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff810089a8)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100c929)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d33b)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e580)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81012b15)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff810133c8)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810415b2)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81057566)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810592a2)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In kernel/workqueue.c (ffffffff810a0f5f)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff810a99d8)
Location: include/linux/slab.h:675
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b467a)
Location: include/linux/slab.h:675
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810c21af)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/topology.c (ffffffff810cc63f)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/irqdesc.c (ffffffff810e533b)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff810ecf57)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff8115e7c1)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff811ae022)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff811aec60)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff811bb225)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffffffff812068a7)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/nobootmem.c (ffffffff812095eb)
Location: include/linux/slab.h:675
Inline: True
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
```
```
In mm/memblock.c (ffffffff820d3c6e)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - mm/memblock.c:memblock_virt_alloc_internal
```
```
In mm/sparse.c (ffffffff818ff039)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff8190062b)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In block/elevator.c (ffffffff8141ed36)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff814298f6)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff814331bf)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-mq-tag.c (ffffffff81433ece)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff81438de6)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (ffffffff81439f6c)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff814464e6)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff8144c2e6)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/deadline-iosched.c (ffffffff8144cd7d)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_init_queue
```
```
In block/cfq-iosched.c (ffffffff81453c21)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_pd_alloc
```
```
In lib/genalloc.c (ffffffff814734bf)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In lib/sbitmap.c (ffffffff8148b379)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/lightnvm/core.c (ffffffff815d84f8)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/md/dm.c (ffffffff8174fe96)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-rq.c (ffffffff8175b914)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In arch/x86/pci/acpi.c (ffffffff817a926d)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
```
In net/core/sysctl_net_core.c (ffffffff817c6d82)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff817cc2c6)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
```
```
In net/core/flow.c (ffffffff817eef83)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_cpu_up_prep
```
```
In net/sched/sch_generic.c (ffffffff817fd397)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff8210e960)
Location: include/linux/slab.h:675
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff810b467a-ffffffff810b468c: kzalloc_node.constprop.85 (STB_LOCAL)
ffffffff812095eb-ffffffff812095fd: kzalloc_node.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100844f)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008bc8)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100cec9)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d8db)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100efe9)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81012be5)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81013bf8)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81044a15)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105bfdb)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105d782)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81060680)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In kernel/workqueue.c (ffffffff810a77b4)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff810b0268)
Location: include/linux/slab.h:697
Inline: True
```
```
In kernel/sched/core.c (ffffffff810bb94a)
Location: include/linux/slab.h:697
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810c9887)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/topology.c (ffffffff810d333a)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/irqdesc.c (ffffffff810ed59a)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff810f5359)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff8116b7c1)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/bpf/cpumap.c (ffffffff811aff0d)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/bpf/sockmap.c (ffffffff811b11f6)
Location: include/linux/slab.h:697
Inline: True
```
```
In kernel/events/core.c (ffffffff811c1b82)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff811c27f0)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mempool.c (ffffffff811cfe35)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffffffff8121f597)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/nobootmem.c (ffffffff8122273b)
Location: include/linux/slab.h:697
Inline: True
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
```
```
In mm/memblock.c (ffffffff826dc68e)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - mm/memblock.c:memblock_virt_alloc_internal
```
```
In mm/sparse.c (ffffffff819891b2)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff8198a621)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In block/elevator.c (ffffffff81449816)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff81454ad6)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff8145ed87)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-mq-tag.c (ffffffff8145fbfe)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff81464dd0)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (ffffffff81465f8c)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff814730b6)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff814789e6)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/deadline-iosched.c (ffffffff8147947d)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_init_queue
```
```
In block/cfq-iosched.c (ffffffff8147d181)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_pd_alloc
```
```
In lib/genalloc.c (ffffffff814a084f)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In lib/sbitmap.c (ffffffff814c7499)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/lightnvm/core.c (ffffffff8163f178)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/md/dm.c (ffffffff817c2076)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff817cdb54)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In arch/x86/pci/acpi.c (ffffffff8182071d)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
```
In net/core/sysctl_net_core.c (ffffffff81840950)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff8184598c)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
```
```
In net/sched/sch_generic.c (ffffffff8187ae00)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff82718d17)
Location: include/linux/slab.h:697
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff810bb94a-ffffffff810bb95c: kzalloc_node.constprop.83 (STB_LOCAL)
ffffffff8122273b-ffffffff8122274d: kzalloc_node.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008c10)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009301)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100d60a)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
```
```
In arch/x86/events/intel/bts.c (ffffffff8100e06c)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f8af)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81013530)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff810145fa)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81046cdb)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105eef3)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81060907)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81063750)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In kernel/workqueue.c (ffffffff810ae378)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff810b7065)
Location: include/linux/slab.h:716
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c2eef)
Location: include/linux/slab.h:716
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810d19fe)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/topology.c (ffffffff810dafff)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/irqdesc.c (ffffffff810f5955)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff810fd725)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff8117ac53)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/bpf/cpumap.c (ffffffff811ca743)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/bpf/sockmap.c (ffffffff811cd26b)
Location: include/linux/slab.h:716
Inline: True
```
```
In kernel/events/core.c (ffffffff811e1f2b)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/mempool.c (ffffffff811f1125)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffffffff81241ff3)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/nobootmem.c (ffffffff812446cb)
Location: include/linux/slab.h:716
Inline: True
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
```
```
In mm/memblock.c (ffffffff82706b88)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - mm/memblock.c:memblock_virt_alloc_internal
```
```
In mm/sparse.c (ffffffff819e5b0f)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff8270a060)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In block/elevator.c (ffffffff8147c1b5)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff81487f15)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff81491673)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814934fb)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff81498710)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (ffffffff81499966)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff814a7485)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff814ad0a5)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/deadline-iosched.c (ffffffff814adb02)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_init_queue
```
```
In block/cfq-iosched.c (ffffffff814b4108)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_pd_alloc
```
```
In lib/genalloc.c (ffffffff814d59c0)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_add_virt
```
```
In lib/sbitmap.c (ffffffff814f8c50)
Location: include/linux/slab.h:716
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff8167a535)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a61bb)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffffffff8180a7c5)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff81816944)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In arch/x86/pci/acpi.c (ffffffff8186a992)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
```
In net/core/sysctl_net_core.c (ffffffff8188b065)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff8188ef92)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
```
```
In net/core/page_pool.c (ffffffff818bd895)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/sched/sch_generic.c (ffffffff818cd1af)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff82743497)
Location: include/linux/slab.h:716
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff810c2eef-ffffffff810c2f01: kzalloc_node.constprop.78 (STB_LOCAL)
ffffffff812446cb-ffffffff812446dd: kzalloc_node.constprop.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008b30)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008fc9)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100d9cb)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100e53c)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ff04)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff810137a0)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014a5a)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055cec)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810648d3)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81065ad7)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81069450)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In kernel/workqueue.c (ffffffff810b74d2)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff810c01f5)
Location: include/linux/slab.h:751
Inline: True
```
```
In kernel/sched/core.c (ffffffff810cc1a1)
Location: include/linux/slab.h:751
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810db350)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/topology.c (ffffffff810e4baf)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/irqdesc.c (ffffffff811010e5)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff81108b75)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff811876c3)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/bpf/cpumap.c (ffffffff811de075)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff811f239b)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/mempool.c (ffffffff81202f85)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffffffff8125671c)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (ffffffff828bdd34)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff81a20ee6)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff828c11ed)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In block/elevator.c (ffffffff8149a2d5)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff814a1ef5)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff814ab108)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814ad52b)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff814b2860)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (ffffffff814b3bd6)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff814c1575)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff814c7435)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/mq-deadline.c (ffffffff814c8054)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In lib/sbitmap.c (ffffffff8150d08e)
Location: include/linux/slab.h:751
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff81699115)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817cc318)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffffffff818367c5)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff81842235)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff818ac0a5)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff818b2cfa)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (ffffffff818e4be5)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff818e6265)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff818f850f)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff828fd78d)
Location: include/linux/slab.h:751
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff810cc1a1-ffffffff810cc1b3: kzalloc_node.constprop.78 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810090d0)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009459)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100e29e)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ee04)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81010fd3)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81014bf4)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015ef9)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058f4a)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067fb9)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069285)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cca0)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In kernel/workqueue.c (ffffffff810bc87c)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff810c6315)
Location: include/linux/slab.h:757
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d4561)
Location: include/linux/slab.h:757
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810e27a2)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/topology.c (ffffffff810ebb4f)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (ffffffff811098e5)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff8111215c)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff81194bd9)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/bpf/cpumap.c (ffffffff811f3711)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff8120a062)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/mempool.c (ffffffff8121a385)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffffffff8126a206)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (ffffffff828d71b0)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff81a914a8)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff828da56e)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In block/elevator.c (ffffffff814c83b5)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff814cffb5)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff814d94ad)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814db7aa)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff814e0cf1)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (ffffffff814e2167)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff814efd39)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff814f5c95)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/mq-deadline.c (ffffffff814f68f4)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In lib/sbitmap.c (ffffffff8153b79d)
Location: include/linux/slab.h:757
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816d1b95)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8180c50a)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffffffff81879385)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff81885095)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff818f7960)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff818ff9ee)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (ffffffff81934435)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81935c05)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81957cbf)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff8291a308)
Location: include/linux/slab.h:757
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff810d4561-ffffffff810d4573: kzalloc_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009480)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009859)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100e8de)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ef5f)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff810116b3)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81015544)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff810168a9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105981a)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810688f9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069c05)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd223)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e400)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81097e94)
Location: include/linux/slab.h:699
Inline: True
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828ca07d)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/workqueue.c (ffffffff810c35cc)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff810cf3e5)
Location: include/linux/slab.h:699
Inline: True
```
```
In kernel/sched/core.c (ffffffff810deb69)
Location: include/linux/slab.h:699
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810ece52)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (ffffffff810f012e)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/topology.c (ffffffff810f7516)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (ffffffff81115cb5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff8111e3dc)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff811a0699)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/bpf/cpumap.c (ffffffff812004b1)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff812173d2)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/mempool.c (ffffffff81227cf5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffffffff81279116)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (ffffffff828df612)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff81ac87d5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff828e2a15)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In block/elevator.c (ffffffff814e14b5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff814e9355)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff814f286d)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814f4bda)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff814fa121)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (ffffffff814fb527)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff815091e9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff8150f3d5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (ffffffff81510175)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffffffff815147a4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In lib/sbitmap.c (ffffffff8155c5ad)
Location: include/linux/slab.h:699
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816f5a85)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183d4fc)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffffffff818ab1c5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff818b7015)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff819296e0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81931d0e)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (ffffffff81967065)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81968cc5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff8198e15f)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff82924177)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff81097e94-ffffffff81097ea6: kzalloc_node.constprop.0 (STB_LOCAL)
ffffffff810deb69-ffffffff810deb7b: kzalloc_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100a459)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_alloc_nb
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100abc9)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100fbe6)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff810104c5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81011203)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
```
In arch/x86/events/intel/pt.c (ffffffff81016ce0)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018025)
Location: include/linux/slab.h:678
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ec86)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106fe95)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81070ee5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1789)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810756a1)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109d50c)
Location: include/linux/slab.h:678
Inline: True
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:summarize_uvhub_sockets
  - arch/x86/platform/uv/tlb_uv.c:make_per_cpu_thp
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff82cec9c9)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/workqueue.c (ffffffff810cae9c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:create_worker
```
```
In kernel/smpboot.c (ffffffff810d9255)
Location: include/linux/slab.h:678
Inline: True
```
```
In kernel/sched/core.c (ffffffff810e6dde)
Location: include/linux/slab.h:678
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810f6d5f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/topology.c (ffffffff811011d8)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:build_group_from_child_sched_domain
```
```
In kernel/irq/irqdesc.c (ffffffff811217b5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff8112b0bc)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff811b6c79)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/bpf/cpumap.c (ffffffff81227f25)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/events/core.c (ffffffff8123199b)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/mempool.c (ffffffff812548f5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create
```
```
In mm/backing-dev.c (ffffffff81277d25)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/vmalloc.c (ffffffff812aa0e6)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (ffffffff82cfcb3c)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff81bc11d5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff82cffaf5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:alloc_mem_cgroup_per_node_info
```
```
In fs/io-wq.c (ffffffff8138b5b7)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
```
```
In block/elevator.c (ffffffff8153fee5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff81548325)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff81551667)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff815555aa)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff8155afdf)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partitions/core.c (ffffffff8155d491)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff8156a4f5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff81570445)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (ffffffff815712b5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffffffff81575624)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In lib/sbitmap.c (ffffffff815e5e19)
Location: include/linux/slab.h:678
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff817ae585)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190ee3f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffffffff8197b395)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff819879b5)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff819fd66f)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81a05af3)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (ffffffff81a3a525)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81a3ca85)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81a65ddf)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b818b2)
Location: include/linux/slab.h:678
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff8109d50c-ffffffff8109d51e: kzalloc_node.constprop.0 (STB_LOCAL)
ffffffff810e6dde-ffffffff810e6df0: kzalloc_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810092d9)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_alloc_nb
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009b59)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100f2f6)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100fa25)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81010833)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
```
In arch/x86/events/intel/pt.c (ffffffff81017180)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018566)
Location: include/linux/slab.h:691
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d1bf)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810712e9)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810722f5)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fce530)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075ce1)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff82fd9023)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/workqueue.c (ffffffff810c5fcc)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:create_worker
```
```
In kernel/smpboot.c (ffffffff810d43f5)
Location: include/linux/slab.h:691
Inline: True
```
```
In kernel/sched/core.c (ffffffff81bdc614)
Location: include/linux/slab.h:691
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810f4f3f)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/topology.c (ffffffff810ffd38)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:build_group_from_child_sched_domain
```
```
In kernel/irq/irqdesc.c (ffffffff8111d8e5)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff81126b4c)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff811b4819)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff8123b60b)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In mm/mempool.c (ffffffff8125f35f)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create
```
```
In mm/backing-dev.c (ffffffff81282338)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/vmalloc.c (ffffffff812b5226)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (ffffffff82fe9565)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff81c3a227)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff82fec4ba)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:alloc_mem_cgroup_per_node_info
```
```
In fs/io-wq.c (ffffffff8139c7a6)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
```
```
In crypto/api.c (ffffffff8153bf28)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - crypto/api.c:crypto_create_tfm_node
```
```
In block/elevator.c (ffffffff8155c685)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff81564092)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff8156d7a7)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff81571deb)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff8157726f)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/blk-cgroup.c (ffffffff81584f73)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff8158b295)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (0)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffffffff81592434)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In lib/sbitmap.c (ffffffff8160a1c9)
Location: include/linux/slab.h:691
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff817c3118)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci.c (ffffffff8190caf0)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8191699f)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffffffff8197fbb5)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff8198b945)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff819fd2ab)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81a072f3)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (ffffffff81a3cab5)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81a3e614)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81a6defa)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c3312f)
Location: include/linux/slab.h:691
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff81bdc614-ffffffff81bdc626: kzalloc_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009ce7)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100a539)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8101030b)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff81010a75)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff810117d3)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
```
In arch/x86/events/intel/pt.c (ffffffff810190f4)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019896)
Location: include/linux/slab.h:695
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d92f)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81071b75)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072df5)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d8fcb)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810767c0)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff831e38a0)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/workqueue.c (ffffffff810c790a)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff810d6035)
Location: include/linux/slab.h:695
Inline: True
```
```
In kernel/sched/core.c (ffffffff81bce6cc)
Location: include/linux/slab.h:695
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810f702f)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/topology.c (ffffffff81101938)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (ffffffff8111daa5)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff81126b8c)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff811b3bd9)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff81251e32)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff812530d5)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In mm/mempool.c (ffffffff81263ebf)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create
```
```
In mm/backing-dev.c (ffffffff81287448)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/vmalloc.c (ffffffff812ba616)
Location: include/linux/slab.h:695
Inline: True
```
```
In mm/memblock.c (ffffffff831f3c0f)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff81c2daa7)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff831f6cea)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In fs/io-wq.c (ffffffff813a386a)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
```
```
In crypto/api.c (ffffffff81544618)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - crypto/api.c:crypto_create_tfm_node
```
```
In block/elevator.c (ffffffff81564f15)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff8156c802)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff81574797)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff81579dfb)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff8157e8a3)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/blk-cgroup.c (ffffffff8158bb03)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff81592115)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (ffffffff8159327c)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffffffff81599114)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In lib/sbitmap.c (ffffffff815ed4ce)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/lightnvm/core.c (ffffffff817a64b8)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci.c (ffffffff818f0050)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818f9e1f)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffffffff81963d35)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff81970035)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff819e3b1c)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff819e72ff)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - net/core/dev.c:expand_xps_map
```
```
In net/core/page_pool.c (ffffffff81a23895)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81a4c7fa)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81a56774)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c25436)
Location: include/linux/slab.h:695
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff81bce6cc-ffffffff81bce6de: kzalloc_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100adb8)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff81010e7e)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8101176f)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8101262a)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
```
In arch/x86/events/intel/pt.c (ffffffff8101a017)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101c176)
Location: include/linux/slab.h:730
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066ffe)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107d975)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107f055)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc493)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083ef6)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff832c732b)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/workqueue.c (ffffffff810da676)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff810e928f)
Location: include/linux/slab.h:730
Inline: True
```
```
In kernel/sched/core.c (ffffffff81ca5b7f)
Location: include/linux/slab.h:730
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff8111139a)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/topology.c (ffffffff8111dc37)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (ffffffff8113deb5)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff811470fc)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff811ddb8b)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff8128d661)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff8128e9d3)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In mm/mempool.c (ffffffff812a04ef)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create
```
```
In mm/backing-dev.c (ffffffff812c6dc8)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/vmalloc.c (ffffffff812fcc16)
Location: include/linux/slab.h:730
Inline: True
```
```
In mm/memblock.c (ffffffff832d9f55)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff81d4c39c)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff832dd889)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In fs/io-wq.c (ffffffff813f2da5)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
```
```
In crypto/api.c (ffffffff815a4db8)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - crypto/api.c:crypto_create_tfm_node
```
```
In block/elevator.c (ffffffff815c9295)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff815d0cd2)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff815d8cb7)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff815df16b)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff815e3db7)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/blk-cgroup.c (ffffffff815f0e9a)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff815f9005)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (ffffffff815fa52c)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffffffff81601669)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_sched
```
```
In lib/sbitmap.c (ffffffff8165a2ea)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/usb/host/xhci.c (ffffffff8198cce0)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81998aaf)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffffffff81a0bce5)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff81a18945)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff81a940e2)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81a97cc4)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - net/core/dev.c:expand_xps_map
```
```
In net/core/page_pool.c (ffffffff81ad7ec5)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81b05f9a)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81b0f574)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff81d417e5)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff81ca5b7f-ffffffff81ca5b91: kzalloc_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100a4c0)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8101261f)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff81012f87)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81014220)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
```
In arch/x86/events/intel/pt.c (ffffffff8101be87)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101e946)
Location: include/linux/slab.h:742
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073c6f)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8108d1ae)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8108ea11)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346ddb7)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81093f42)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8347a142)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/workqueue.c (ffffffff810f3dd3)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff8110405a)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/sched/core.c (ffffffff81e554b3)
Location: include/linux/slab.h:742
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff8112d5be)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/build_utility.c (ffffffff8113fde8)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (ffffffff811614b5)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff8116b96c)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff81214cdb)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff812e23d2)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff812e38b4)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In mm/mempool.c (ffffffff812f7b14)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create
```
```
In mm/backing-dev.c (ffffffff813242b8)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/vmalloc.c (ffffffff81363de1)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (ffffffff8348ef78)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff81f1beb5)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff834930c0)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff813d70b8)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In crypto/api.c (ffffffff8164b547)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - crypto/api.c:crypto_create_tfm_node
```
```
In block/elevator.c (ffffffff81674525)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff8167c58f)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff81686732)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff8168d7ec)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff81693083)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/blk-ia-ranges.c (ffffffff8169fcb7)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
```
```
In block/blk-cgroup.c (ffffffff816a2dea)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff816aaf75)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (ffffffff816ac8ba)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffffffff816b41bb)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_sched
```
```
In io_uring/io-wq.c (ffffffff816db906)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:create_io_worker
```
```
In lib/sbitmap.c (ffffffff81772adc)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/usb/host/xhci.c (ffffffff81ae8ee0)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af5aa1)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffffffff81b741d5)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff81b81735)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff81c0a49e)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81c0f255)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - net/core/dev.c:expand_xps_map
```
```
In net/core/page_pool.c (ffffffff81c58db5)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81c8b305)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81c96747)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff81f0e146)
Location: include/linux/slab.h:742
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff81e554b3-ffffffff81e554cd: kzalloc_node.constprop.0 (STB_LOCAL)
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
In arch/x86/events/amd/core.c (ffffffff8100c02b)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8101659f)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff81016fc7)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff810183d0)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
```
In arch/x86/events/intel/pt.c (ffffffff810201c7)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81022ec6)
Location: include/linux/slab.h:729
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108401c)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a17ce)
Location: include/linux/slab.h:729
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a3201)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e93bb2)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a95fb)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff83ea476a)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/workqueue.c (ffffffff81116020)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff8112980a)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/sched/fair.c (ffffffff81157379)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/build_utility.c (ffffffff8116bdf5)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (ffffffff81194b35)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff811a0b3c)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/trace/ring_buffer.c (ffffffff8125e39b)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff8134a953)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff8134bf64)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In mm/mempool.c (ffffffff813614c4)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create
```
```
In mm/backing-dev.c (ffffffff81398bc8)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/vmalloc.c (ffffffff813dfef1)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (ffffffff83ec143b)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff820c3e45)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff83ec701a)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff8145cf18)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In crypto/api.c (ffffffff81704be7)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - crypto/api.c:crypto_create_tfm_node
```
```
In block/elevator.c (ffffffff81730265)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff81738e31)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff81744ff2)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff8174bffc)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff817527e5)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/blk-ia-ranges.c (ffffffff8175e747)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
```
```
In block/blk-cgroup.c (ffffffff817613b5)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff8176995e)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (ffffffff8176b3ba)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffffffff8177382b)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_sched
```
```
In io_uring/io-wq.c (ffffffff817a79df)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:create_io_worker
```
```
In lib/sbitmap.c (ffffffff818a3c94)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/usb/host/xhci.c (ffffffff81c75190)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c83366)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm-table.c (ffffffff81d1258a)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff81d1fb25)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff81dba53c)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81dbefa5)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - net/core/dev.c:expand_xps_map
```
```
In net/core/page_pool.c (ffffffff81e0ecb5)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81e47705)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81e52377)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe51a)
Location: include/linux/slab.h:729
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
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
In arch/x86/events/amd/core.c (ffffffff8100b7cf)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff81015edc)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff81016967)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81017cb0)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
```
In arch/x86/events/intel/pt.c (ffffffff8101ff17)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81022ba6)
Location: include/linux/slab.h:712
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810865bc)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a47bc)
Location: include/linux/slab.h:712
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a6291)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b765f)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810accf2)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff836c8aea)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/workqueue.c (ffffffff81122dc0)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff81136caa)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/sched/fair.c (ffffffff811673c1)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/build_utility.c (ffffffff8117c355)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (ffffffff811a62e0)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff811b29ef)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/trace/ring_buffer.c (ffffffff8127557b)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff8137b993)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff8137cfb4)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In mm/mempool.c (ffffffff81393884)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create
```
```
In mm/backing-dev.c (ffffffff813cbb28)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/vmalloc.c (ffffffff81414c31)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (ffffffff836e6c4b)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff82147bf5)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff836ebff3)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff81492f68)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In crypto/api.c (ffffffff8173e000)
Location: include/linux/slab.h:712
Inline: True
```
```
In block/elevator.c (ffffffff8176c495)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff81775511)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff81780f62)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff8178871c)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff8178e9a5)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/blk-ia-ranges.c (ffffffff8179d65f)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
```
```
In block/blk-cgroup.c (ffffffff8179fb63)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff817a8a03)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (ffffffff817aa4a5)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffffffff817b26db)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_sched
```
```
In lib/sbitmap.c (ffffffff818e6174)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/usb/host/xhci.c (ffffffff81cdc2b0)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ceb158)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm-table.c (ffffffff81d7b94a)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff81d88d15)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff81e2ac98)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81e2ec75)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - net/core/dev.c:expand_xps_map
```
```
In net/core/page_pool.c (ffffffff81e82335)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81ea1b78)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81eadbe7)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f37a)
Location: include/linux/slab.h:712
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
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
In arch/x86/events/amd/core.c (ffffffff81010f57)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8101b9cb)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8101c4a7)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8101d804)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
```
In arch/x86/events/intel/pt.c (ffffffff81025fd7)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81028cd6)
Location: include/linux/slab.h:720
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d4b7)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810ab81c)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810ad2c1)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e7f7d)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b38e2)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff838f9726)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/workqueue.c (ffffffff8112cdee)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff81141d35)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/sched/fair.c (ffffffff8117416e)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/build_utility.c (ffffffff8118a035)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (ffffffff811b5dc9)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff811c27f5)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:__irq_domain_create
```
```
In kernel/trace/ring_buffer.c (ffffffff8128fc2b)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/events/core.c (ffffffff813a4bb2)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff813a6214)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In mm/mempool.c (ffffffff813bd559)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create
```
```
In mm/shrinker.c (ffffffff813e3c60)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - mm/shrinker.c:expand_one_shrinker_info
  - mm/shrinker.c:alloc_shrinker_info
```
```
In mm/backing-dev.c (ffffffff813f6478)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/vmalloc.c (ffffffff814416a1)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (ffffffff839191fb)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff8222a4c5)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff8391efd0)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In mm/hugetlb_cgroup.c (ffffffff814c296a)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In crypto/api.c (ffffffff8177ee60)
Location: include/linux/slab.h:720
Inline: True
```
```
In block/elevator.c (ffffffff817ae6b3)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff817b77b3)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff817c3792)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff817cade6)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff817d1265)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/blk-ia-ranges.c (ffffffff817e10af)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
```
```
In block/blk-cgroup.c (ffffffff817e3668)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff817ec77e)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (ffffffff817ee255)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffffffff817f64f9)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_sched
```
```
In lib/sbitmap.c (ffffffff8192d171)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In drivers/usb/host/xhci.c (ffffffff81d912d0)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9d172)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_interrupter
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm-table.c (ffffffff81e328e4)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff81e40453)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff81ee8aa8)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81eed7c5)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - net/core/dev.c:expand_xps_map
```
```
In net/core/page_pool.c (ffffffff81f43350)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81f65dfc)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81f70677)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ee4aa)
Location: include/linux/slab.h:720
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
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
In kernel/workqueue.c (ffff800010121274)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffff80001012f230)
Location: include/linux/slab.h:699
Inline: True
```
```
In kernel/sched/fair.c (ffff80001014d4d4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (ffff8000101517cc)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/topology.c (ffff80001015b86c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (ffff80001017748c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffff800010183ba8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffff800010219ec0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/bpf/cpumap.c (ffff80001028879c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffff8000102a1688)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/mempool.c (ffff8000102b5330)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffff80001030fa3c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (ffff8000114585c8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffff800010d9c4d4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffff80001145bcac)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In block/elevator.c (ffff8000105de05c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffff8000105e741c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffff8000105f20a4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffff8000105f4a2c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffff8000105fbc88)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (ffff8000105fd51c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffff80001060bee8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffff800010613080)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (ffff80001061399c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffff8000106190c8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In lib/sbitmap.c (ffff800010669528)
Location: include/linux/slab.h:699
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010674678)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
```
```
In drivers/lightnvm/core.c (ffff8000108dee78)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a7b498)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffff800010b014a8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffff800010b0f0a8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffff800010bc5c58)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffff800010bca708)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (ffff800010c0c718)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffff800010c0f79c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffff800010c39994)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffff8000114b51d4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
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
In kernel/workqueue.c (c03750e8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/smpboot.c (c037f18c)
Location: include/linux/slab.h:699
Inline: True
```
```
In kernel/sched/fair.c (c039b0f4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (c039ead8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/topology.c (c03a82c4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (c03c9378)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (c03d2e1c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (c04573c8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/bpf/cpumap.c (c04b7d30)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (c04d17cc)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/mempool.c (c04e2634)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (c052c03c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (c1532558)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/memcontrol.c (c1534230)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In block/elevator.c (c078b180)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (c0793fc0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (c07a0684)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (c07a6d40)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (c07a8420)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (c07b78d4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (c07bd9a4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (c07bfcec)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (c07c3f44)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In lib/sbitmap.c (c081220c)
Location: include/linux/slab.h:699
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081c1cc)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
```
```
In drivers/lightnvm/core.c (c09cdd48)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci-mem.c (c0b4ecc4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (c0be0c14)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (c0bed3fc)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (c0ce0f24)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (c0cea614)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (c0d24db8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (c0d26458)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (c0d4bcd0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (c15ba488)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/powerpc/sysdev/xive/common.c (c0000000000be1c8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_prepare_cpu
```
```
In arch/powerpc/platforms/powernv/pci.c (c0000000000d0f5c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_table_alloc
```
```
In arch/powerpc/platforms/powernv/pci-ioda-tce.c (c0000000000dbbfc)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_pci_link_table_and_group
```
```
In arch/powerpc/platforms/pseries/iommu.c (c0000000000f0604)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/iommu.c:iommu_pseries_alloc_group
  - arch/powerpc/platforms/pseries/iommu.c:iommu_pseries_alloc_group
```
```
In kernel/workqueue.c (c00000000016a820)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (c0000000001789cc)
Location: include/linux/slab.h:699
Inline: True
```
```
In kernel/sched/fair.c (c0000000001a02f4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (c0000000001a4ff4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/topology.c (c0000000001aff50)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (c0000000001d1024)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (c0000000001de3b4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (c00000000029bfa0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/bpf/cpumap.c (c000000000333c7c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (c000000000353ad0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/mempool.c (c00000000036c804)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (c0000000003e0ce4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (c000000001381e1c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (c000000000417de8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (c00000000045bab4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
Direct callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In block/elevator.c (c0000000007704b4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (c00000000077bdb4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (c0000000007891e4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (c00000000078c3d8)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (c000000000795018)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (c000000000796e04)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (c0000000007a8cec)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (c0000000007b16a4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (c0000000007b2b0c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (c0000000007b8e28)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In lib/sbitmap.c (c00000000081f974)
Location: include/linux/slab.h:699
Inline: True
```
```
In drivers/lightnvm/core.c (c00000000097309c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci-mem.c (c000000000b53140)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (c000000000bf07e0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (c000000000c02418)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (c000000000ca0908)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (c000000000cad698)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (c000000000cf7e04)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (c000000000cfa570)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (c000000000d327c0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (c0000000013c71a0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
c00000000044fbb0-c00000000044fbe4: kzalloc_node.constprop.0 (STB_LOCAL)
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
In kernel/workqueue.c (ffffffe0000da242)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/smpboot.c (ffffffe0000e2f34)
Location: include/linux/slab.h:699
Inline: True
```
```
In kernel/sched/fair.c (ffffffe0000f6790)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (ffffffe0000f99dc)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/topology.c (ffffffe000100a80)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/irqdesc.c (ffffffe0001124be)
Location: include/linux/slab.h:699
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffe00011adb6)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffe000177c2a)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/bpf/cpumap.c (ffffffe0001bc912)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffe0001d096c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/mempool.c (ffffffe0001da36c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffffffe00021803c)
Location: include/linux/slab.h:699
Inline: True
```
```
In mm/memblock.c (ffffffe000016cdc)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffe0008c4644)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffe00001954a)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In block/elevator.c (ffffffe0004210b2)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffe00042826a)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffe000430a02)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffe000432926)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffe000437d06)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (ffffffe000439126)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffe000444dac)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffe00044a59a)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (ffffffe00044b6d4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffffffe00044f15e)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In lib/sbitmap.c (ffffffe000494888)
Location: include/linux/slab.h:699
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffe000575428)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000692a2c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffffffe0006f1478)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffe0006fc230)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffe000752088)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffe00075a7ca)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (ffffffe000789acc)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffe00078b314)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffe0007aad22)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffe000043f1c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009480)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009859)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100e8de)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ef5f)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff810116b3)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81015544)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff810168a9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105939a)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810683e9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810696f5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d3a0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In kernel/workqueue.c (ffffffff810bd93c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff810c9765)
Location: include/linux/slab.h:699
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d8d59)
Location: include/linux/slab.h:699
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810e6fb2)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/topology.c (ffffffff810f0916)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (ffffffff8110e295)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff811169bc)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff81198cb9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/bpf/cpumap.c (ffffffff811f8ad1)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff8120fa22)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/mempool.c (ffffffff81220345)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffffffff81271766)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (ffffffff828c84c6)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff81a67645)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff828cb8c9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In block/elevator.c (ffffffff814d9a95)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff814e1935)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff814eae4d)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814ed1ba)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff814f2701)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (ffffffff814f3b07)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff815017c9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff815079b5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (ffffffff81508755)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffffffff8150cd84)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In lib/sbitmap.c (ffffffff81554b9d)
Location: include/linux/slab.h:699
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816bb275)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/nvme/host/core.c (ffffffff81746dea)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
```
```
In drivers/nvme/host/pci.c (ffffffff8174e192)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_probe
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f58ac)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffffffff81851045)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff8185ce95)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff818c96e0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff818d1d0e)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (ffffffff81907035)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81908c95)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff8192dfcf)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff82908e7b)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff810d8d59-ffffffff810d8d6b: kzalloc_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007c10)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81007ff9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100d5de)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100dcbf)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81010453)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81014814)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015cd9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810495ba)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058759)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059a55)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d720)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In kernel/workqueue.c (ffffffff810ac16c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff810b7f85)
Location: include/linux/slab.h:699
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c7764)
Location: include/linux/slab.h:699
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810d6152)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (ffffffff810d94ee)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/topology.c (ffffffff810e0986)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (ffffffff810feff5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff811076ac)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff8118c4f9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/bpf/cpumap.c (ffffffff811eb821)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff812027b2)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/mempool.c (ffffffff812134f5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffffffff812636d6)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (ffffffff828c0beb)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff81a24105)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff828c3fee)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In block/elevator.c (ffffffff814ca445)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff814d22c5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff814db39d)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814dd70a)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff814e2c31)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (ffffffff814e4017)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff814f1cd9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff814f7e65)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (ffffffff814f8c05)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffffffff814fd1b4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In lib/sbitmap.c (ffffffff81544e1d)
Location: include/linux/slab.h:699
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff81728a69)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
```
```
In drivers/nvme/host/pci.c (ffffffff8172e032)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_probe
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817baa4c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffffffff81818655)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff81824465)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff81883620)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff8188bb9e)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (ffffffff818c0e45)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff818c2aa5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff818e7acf)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff829011c9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff810c7764-ffffffff810c7776: kzalloc_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009440)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009819)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100e89e)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ef1f)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81011673)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81015504)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016869)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810597ca)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068899)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069ba5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d850)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In kernel/workqueue.c (ffffffff810bce9c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff810c8c95)
Location: include/linux/slab.h:699
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d5099)
Location: include/linux/slab.h:699
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810e3382)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (ffffffff810e665e)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/topology.c (ffffffff810eda46)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (ffffffff8110c185)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff811148ac)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff81196a89)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/bpf/cpumap.c (ffffffff811f68a1)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff8120d7c2)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/mempool.c (ffffffff8121e0e5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffffffff8126f506)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (ffffffff828db246)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff81ad3a55)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff828de649)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In block/elevator.c (ffffffff814d5b25)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff814dd9c5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff814e6edd)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff814e924a)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff814ee791)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (ffffffff814efb97)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff814fd859)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff81503a45)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (ffffffff815047e5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffffffff81508e14)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In lib/sbitmap.c (ffffffff815508dd)
Location: include/linux/slab.h:699
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816e9745)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183237c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffffffff818a0675)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff818ac4c5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff8191a6e0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81922d0e)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (ffffffff81958065)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81959cc5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff8197f15f)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff8291e775)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff810d5099-ffffffff810d50ab: kzalloc_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810095a0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009979)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100ea6e)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f0ef)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81011883)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81015744)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016aa9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ac6a)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81069fe9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b325)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828be250)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106fad0)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81099354)
Location: include/linux/slab.h:699
Inline: True
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828cb0ba)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/workqueue.c (ffffffff810c521c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
```
```
In kernel/smpboot.c (ffffffff810d1205)
Location: include/linux/slab.h:699
Inline: True
```
```
In kernel/sched/core.c (ffffffff810e0948)
Location: include/linux/slab.h:699
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff810eef62)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/topology.c (ffffffff810f8a86)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/irqdesc.c (ffffffff811178b5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (ffffffff8111fedc)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/trace/ring_buffer.c (ffffffff811a4699)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/bpf/cpumap.c (ffffffff812054d1)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff8121c662)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In mm/mempool.c (ffffffff8122d155)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/vmalloc.c (ffffffff8127ef26)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/memblock.c (ffffffff828e0667)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/sparse.c (ffffffff81adff48)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffff828e3a60)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In block/elevator.c (ffffffff814ee995)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffff814f6825)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffff814ffe82)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (ffffffff8150220a)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffff81507831)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (ffffffff81508c27)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffff81516e19)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff8151cff5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (ffffffff8151dd95)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (ffffffff815225b4)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In lib/sbitmap.c (ffffffff8156a71d)
Location: include/linux/slab.h:699
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff81703f85)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184c55c)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (ffffffff818bc8b5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
```
```
In drivers/md/dm-rq.c (ffffffff818c8715)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (ffffffff8193b92a)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff8194413e)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (ffffffff8197a175)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff8197bee5)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff819a16bf)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv6/seg6_hmac.c (ffffffff829251d9)
Location: include/linux/slab.h:699
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff81099354-ffffffff81099366: kzalloc_node.constprop.0 (STB_LOCAL)
ffffffff810e0948-ffffffff810e095a: kzalloc_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
