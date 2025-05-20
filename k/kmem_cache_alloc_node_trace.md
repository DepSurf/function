# Function: <code>kmem_cache_alloc_node_trace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811eb1a0)
Location: mm/slub.c:2610
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/rapl.c:rapl_cpu_prepare
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - kernel/workqueue.c:alloc_worker
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/callchain.c:get_callchain_buffers
  - mm/mempool.c:mempool_create_node
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/genalloc.c:gen_pool_create
  - drivers/scsi/scsi_lib.c:scsi_init_request
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - net/core/dev.c:netif_set_xps_queue
```
**Symbols:**

```
ffffffff811eb1a0-ffffffff811eb3a3: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120b630)
Location: mm/slub.c:2739
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_addr_filter
  - mm/mempool.c:mempool_create_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/genalloc.c:gen_pool_create
  - drivers/char/random.c:rand_initialize
  - drivers/scsi/scsi_lib.c:scsi_init_request
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - net/core/dev.c:netif_set_xps_queue
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff8120b630-ffffffff8120b7fa: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121d660)
Location: mm/slub.c:2761
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_addr_filter
  - mm/mempool.c:mempool_create_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/genalloc.c:gen_pool_create
  - drivers/char/random.c:rand_initialize
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/scsi/scsi_lib.c:scsi_init_request
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - net/core/dev.c:netif_set_xps_queue
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff8121d660-ffffffff8121d82a: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812282a0)
Location: mm/slub.c:2758
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/mempool.c:mempool_create_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/genalloc.c:gen_pool_create
  - drivers/char/random.c:rand_initialize
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - net/core/dev.c:netif_set_xps_queue
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff812282a0-ffffffff8122846c: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81244710)
Location: mm/slub.c:2771
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/mempool.c:mempool_create_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/genalloc.c:gen_pool_create
  - drivers/char/random.c:rand_initialize
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - net/core/dev.c:netif_set_xps_queue
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff81244710-ffffffff812448da: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81266c50)
Location: mm/slub.c:2754
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/mempool.c:mempool_create_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/genalloc.c:gen_pool_create
  - drivers/char/random.c:do_numa_crng_init
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - net/core/dev.c:netif_set_xps_queue
  - net/core/page_pool.c:page_pool_create
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff81266c50-ffffffff81266e50: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127b960)
Location: mm/slub.c:2804
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/mempool.c:mempool_create_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/mq-deadline.c:dd_init_queue
  - lib/genalloc.c:gen_pool_create
  - drivers/char/random.c:do_numa_crng_init
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - net/core/page_pool.c:page_pool_create
  - net/core/skmsg.c:sk_psock_init
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff8127b960-ffffffff8127bb59: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81297410)
Location: mm/slub.c:2816
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
  - mm/mempool.c:mempool_create_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/mq-deadline.c:dd_init_queue
  - lib/genalloc.c:gen_pool_create
  - drivers/char/random.c:do_numa_crng_init
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - net/core/page_pool.c:page_pool_create
  - net/core/skmsg.c:sk_psock_init
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff81297410-ffffffff81297662: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a7210)
Location: mm/slub.c:2812
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
  - mm/mempool.c:mempool_create_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/mq-deadline.c:dd_init_queue
  - lib/genalloc.c:gen_pool_create
  - drivers/char/random.c:do_numa_crng_init
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - net/core/page_pool.c:page_pool_create
  - net/core/skmsg.c:sk_psock_init
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff812a7210-ffffffff812a7462: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812dc190)
Location: mm/slub.c:2870
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_alloc_nb
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
  - arch/x86/platform/uv/tlb_uv.c:pq_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:create_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/mempool.c:mempool_create
  - mm/backing-dev.c:bdi_alloc
  - mm/vmalloc.c:__get_vm_area_node
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:alloc_mem_cgroup_per_node_info
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/mq-deadline.c:dd_init_queue
  - drivers/char/random.c:do_numa_crng_init
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - net/core/page_pool.c:page_pool_create
  - net/core/skmsg.c:sk_psock_init
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff812dc190-ffffffff812dc40c: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e8740)
Location: mm/slub.c:2938
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_alloc_nb
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:create_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/mempool.c:mempool_create
  - mm/backing-dev.c:bdi_alloc
  - mm/vmalloc.c:__get_vm_area_node
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:alloc_mem_cgroup_per_node_info
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/mq-deadline.c:dd_init_queue
  - drivers/char/random.c:do_numa_crng_init
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - net/core/page_pool.c:page_pool_create
  - net/core/skmsg.c:sk_psock_init
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff812e8740-ffffffff812e8964: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812efd70)
Location: mm/slub.c:2960
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/mempool.c:mempool_create
  - mm/backing-dev.c:bdi_alloc
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/mq-deadline.c:dd_init_queue
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/char/random.c:do_numa_crng_init
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - net/core/page_pool.c:page_pool_create
  - net/core/skmsg.c:sk_psock_init
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff812efd70-ffffffff812effc0: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81339cc0)
Location: mm/slub.c:3259
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/mempool.c:mempool_create
  - mm/backing-dev.c:bdi_alloc
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/mq-deadline.c:dd_init_sched
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/char/random.c:do_numa_crng_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - net/core/page_pool.c:page_pool_create
  - net/core/skmsg.c:sk_psock_init
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff81339cc0-ffffffff81339fa5: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a9a50)
Location: mm/slub.c:3303
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:alloc_worker
  - kernel/smpboot.c:__smpboot_create_thread
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/mempool.c:mempool_create
  - mm/backing-dev.c:bdi_alloc
  - mm/vmalloc.c:__get_vm_area_node
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/mq-deadline.c:dd_init_sched
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:create_io_worker
  - lib/sbitmap.c:sbitmap_queue_init_node
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - net/core/page_pool.c:page_pool_create
  - net/core/skmsg.c:sk_psock_init
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff813a9a50-ffffffff813a9d7e: kmem_cache_alloc_node_trace (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010348610)
Location: mm/slub.c:2812
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
  - mm/mempool.c:mempool_create_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/mq-deadline.c:dd_init_queue
  - lib/genalloc.c:gen_pool_create
  - drivers/char/random.c:do_numa_crng_init
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - net/core/page_pool.c:page_pool_create
  - net/core/skmsg.c:sk_psock_init
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffff800010348610-ffff8000103488a8: kmem_cache_alloc_node_trace (STB_GLOBAL)
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
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/smpboot.c (c037f18c)
Location: include/linux/slab.h:440
Inline: True
```
```
In kernel/sched/fair.c (c039b0f4)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (c039ead8)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/topology.c (c03a82c4)
Location: include/linux/slab.h:440
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
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/irqdomain.c (c03d2e1c)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/taskstats.c (c044b990)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (c04573c8)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In kernel/bpf/local_storage.c (c04b063c)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
```
In kernel/bpf/devmap.c (c04b6a48)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
```
```
In kernel/bpf/cpumap.c (c04b7d30)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (c04d17cc)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In mm/mempool.c (c04e2634)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/util.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In mm/backing-dev.c (c0504128)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
```
```
In mm/vmalloc.c (c052c03c)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/memblock.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In mm/zswap.c (c0541348)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/dmapool.c (c0542ce8)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_create
```
```
In mm/memcontrol.c (c1534230)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In block/elevator.c (c078b180)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (c0793fd4)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (c079e20c)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In block/blk-mq-tag.c (c07a0684)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (c07a6d40)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (c07a8420)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (c07b78d4)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (c07bd9a4)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In block/mq-deadline.c (c07c3f44)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In block/blk-zoned.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In lib/genalloc.c (c07ea454)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_create
```
```
In lib/sbitmap.c (c081220c)
Location: include/linux/slab.h:440
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In drivers/lightnvm/core.c (c09cdd48)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci-mem.c (c0b4ecc4)
Location: include/linux/slab.h:440
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
```
```
In drivers/md/dm.c (c0be0c14)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-rq.c (c0bed3fc)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In net/core/page_pool.c (c0d24db8)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (c0d26458)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In net/ipv4/tcp.c (c0d7e81c)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/slab.h:440
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000426d20)
Location: mm/slub.c:2812
Inline: False
Direct callers:
  - arch/powerpc/sysdev/xive/common.c:xive_prepare_cpu
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_table_alloc
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_pci_link_table_and_group
  - arch/powerpc/platforms/pseries/iommu.c:iommu_pseries_alloc_group
  - arch/powerpc/platforms/pseries/iommu.c:iommu_pseries_alloc_group
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
  - mm/mempool.c:mempool_create_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/mq-deadline.c:dd_init_queue
  - lib/genalloc.c:gen_pool_create
  - drivers/char/random.c:do_numa_crng_init
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - net/core/page_pool.c:page_pool_create
  - net/core/skmsg.c:sk_psock_init
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
c000000000426d20-c0000000004270d8: kmem_cache_alloc_node_trace (STB_GLOBAL)
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
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/smpboot.c (ffffffe0000e2f34)
Location: include/linux/slab.h:440
Inline: True
```
```
In kernel/sched/fair.c (ffffffe0000f6798)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (ffffffe0000f99e4)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/topology.c (ffffffe000100a80)
Location: include/linux/slab.h:440
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
Location: include/linux/slab.h:440
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffe00011adb6)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
```
In kernel/taskstats.c (ffffffe00016e14e)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffe000177c2a)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffe0001b5f56)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
```
In kernel/bpf/devmap.c (ffffffe0001bb6be)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
```
```
In kernel/bpf/cpumap.c (ffffffe0001bc91a)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffe0001d096c)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In mm/mempool.c (ffffffe0001da370)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create_node
```
```
In mm/util.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In mm/backing-dev.c (ffffffe0001f7092)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
```
```
In mm/vmalloc.c (ffffffe000218ab4)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/memblock.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In mm/zswap.c (ffffffe000229cda)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/dmapool.c (ffffffe00022b574)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_create
```
```
In mm/sparse.c (ffffffe0008c4644)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/memcontrol.c (ffffffe00001954a)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In block/elevator.c (ffffffe0004210b2)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/elevator.c:elevator_alloc
```
```
In block/blk-flush.c (ffffffe000428278)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In block/blk-mq-tag.c (ffffffe000432926)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/genhd.c (ffffffe000437d06)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
```
```
In block/partition-generic.c (ffffffe000439126)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/blk-cgroup.c (ffffffe000444dac)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffe00044a59a)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-iocost.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In block/mq-deadline.c (ffffffe00044f15e)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_queue
```
```
In block/blk-zoned.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In lib/genalloc.c (ffffffe0004707a6)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_create
```
```
In lib/sbitmap.c (ffffffe0004948b0)
Location: include/linux/slab.h:440
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffe000575428)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000692a30)
Location: include/linux/slab.h:440
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
```
```
In drivers/md/dm.c (ffffffe0006f1478)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-rq.c (ffffffe0006fc230)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In net/core/page_pool.c (ffffffe000789acc)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffe00078b314)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/slab.h:440
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d4934)
Location: include/linux/slab.h:440
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/slab.h:440
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129f7f0)
Location: mm/slub.c:2812
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
  - mm/mempool.c:mempool_create_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/mq-deadline.c:dd_init_queue
  - lib/genalloc.c:gen_pool_create
  - drivers/char/random.c:do_numa_crng_init
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - net/core/page_pool.c:page_pool_create
  - net/core/skmsg.c:sk_psock_init
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff8129f7f0-ffffffff8129fa42: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81291310)
Location: mm/slub.c:2812
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
  - mm/mempool.c:mempool_create_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/mq-deadline.c:dd_init_queue
  - lib/genalloc.c:gen_pool_create
  - drivers/char/random.c:do_numa_crng_init
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - net/core/page_pool.c:page_pool_create
  - net/core/skmsg.c:sk_psock_init
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff81291310-ffffffff81291562: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129d600)
Location: mm/slub.c:2812
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
  - mm/mempool.c:mempool_create_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/mq-deadline.c:dd_init_queue
  - lib/genalloc.c:gen_pool_create
  - drivers/char/random.c:do_numa_crng_init
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - net/core/page_pool.c:page_pool_create
  - net/core/skmsg.c:sk_psock_init
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff8129d600-ffffffff8129d852: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *kmem_cache_alloc_node_trace(struct kmem_cache *s, gfp_t gfpflags, int node, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ad4e0)
Location: mm/slub.c:2812
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_worker
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
  - mm/mempool.c:mempool_create_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/dmapool.c:dma_pool_create
  - mm/sparse.c:sparse_index_alloc
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
  - block/mq-deadline.c:dd_init_queue
  - lib/genalloc.c:gen_pool_create
  - drivers/char/random.c:do_numa_crng_init
  - drivers/lightnvm/core.c:nvm_alloc_dev
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - net/core/page_pool.c:page_pool_create
  - net/core/skmsg.c:sk_psock_init
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff812ad4e0-ffffffff812ad737: kmem_cache_alloc_node_trace (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
