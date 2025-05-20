# Function: <code>__kmalloc_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811ed0d0)
Location: mm/slub.c:3557
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_create_node
  - mm/memblock.c:memblock_virt_alloc_internal
  - security/apparmor/lsm.c:alloc_buffers
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_init_rq_map
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq-tag.c:bt_alloc
  - block/blk-mq-cpumap.c:blk_mq_make_queue_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:throtl_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/genalloc.c:gen_pool_add_virt
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:netif_set_xps_queue
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
**Symbols:**

```
ffffffff811ed0d0-ffffffff811ed3c1: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120a250)
Location: mm/slub.c:3740
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:get_callchain_buffers
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_create_node
  - mm/memblock.c:memblock_virt_alloc_internal
  - security/apparmor/lsm.c:alloc_buffers
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_init_rq_map
  - block/blk-mq-cpumap.c:blk_mq_make_queue_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:throtl_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/genalloc.c:gen_pool_add_virt
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:netif_set_xps_queue
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
**Symbols:**

```
ffffffff8120a250-ffffffff8120a4e9: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121c2c0)
Location: mm/slub.c:3762
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:get_callchain_buffers
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_create_node
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/memblock.c:memblock_virt_alloc_internal
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_init_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-throttle.c:throtl_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/cpumask.c:alloc_cpumask_var_node
  - lib/genalloc.c:gen_pool_add_virt
  - lib/sbitmap.c:sbitmap_init_node
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:netif_set_xps_queue
  - net/core/flow.c:flow_cache_cpu_up_prep
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
**Symbols:**

```
ffffffff8121c2c0-ffffffff8121c559: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812294a0)
Location: mm/slub.c:3767
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:get_callchain_buffers
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_create_node
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/memblock.c:memblock_virt_alloc_internal
  - block/blk-core.c:alloc_request_size
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-throttle.c:throtl_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/genalloc.c:gen_pool_add_virt
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/md/dm.c:dm_create
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:netif_set_xps_queue
  - net/core/flow.c:flow_cache_cpu_up_prep
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - lib/cpumask.c:alloc_cpumask_var_node
```
**Symbols:**

```
ffffffff812294a0-ffffffff81229733: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812455d0)
Location: mm/slub.c:3783
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:get_callchain_buffers
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_create_node
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/memblock.c:memblock_virt_alloc_internal
  - block/blk-core.c:alloc_request_size
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-throttle.c:throtl_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/genalloc.c:gen_pool_add_virt
  - lib/sbitmap.c:sbitmap_init_node
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:netif_set_xps_queue
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - lib/cpumask.c:alloc_cpumask_var_node
```
**Symbols:**

```
ffffffff812455d0-ffffffff8124588a: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812670a0)
Location: mm/slub.c:3774
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:get_callchain_buffers
  - mm/mempool.c:mempool_create_node
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/backing-dev.c:bdi_alloc_node
  - mm/memblock.c:memblock_virt_alloc_internal
  - security/apparmor/lsm.c:apparmor_init
  - block/blk-core.c:alloc_request_size
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-throttle.c:throtl_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - lib/genalloc.c:gen_pool_add_virt
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:netif_set_xps_queue
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - lib/cpumask.c:alloc_cpumask_var_node
```
**Symbols:**

```
ffffffff812670a0-ffffffff8126735e: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127bd80)
Location: mm/slub.c:3824
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:get_callchain_buffers
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/memblock.c:memblock_alloc_internal
  - security/apparmor/lsm.c:alloc_buffers
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/sock_map.c:sock_hash_update_common
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - lib/cpumask.c:alloc_cpumask_var_node
```
**Symbols:**

```
ffffffff8127bd80-ffffffff8127c02d: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812978e0)
Location: mm/slub.c:3831
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/memblock.c:memblock_alloc_internal
  - security/apparmor/lsm.c:apparmor_init
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/sock_map.c:sock_hash_update_common
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - lib/cpumask.c:alloc_cpumask_var_node
```
**Symbols:**

```
ffffffff812978e0-ffffffff81297bf9: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a76e0)
Location: mm/slub.c:3845
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/memblock.c:memblock_alloc_internal
  - security/apparmor/lsm.c:apparmor_init
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/sock_map.c:sock_hash_update_common
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - lib/cpumask.c:alloc_cpumask_var_node
```
**Symbols:**

```
ffffffff812a76e0-ffffffff812a79f9: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812dc680)
Location: mm/slub.c:3922
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:build_group_from_child_sched_domain
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
  - kernel/events/core.c:perf_cgroup_ensure_storage
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/memblock.c:memblock_alloc_internal
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - lib/sbitmap.c:sbitmap_init_node
  - lib/cpumask.c:alloc_cpumask_var_node
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/sock_map.c:sock_hash_alloc_elem
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff812dc680-ffffffff812dc979: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e92d0)
Location: mm/slub.c:4009
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:build_group_from_child_sched_domain
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - kernel/events/core.c:perf_cgroup_ensure_storage
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/memblock.c:memblock_alloc_internal
  - mm/memcontrol.c:memcg_alloc_page_obj_cgroups
  - crypto/api.c:crypto_create_tfm_node
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - lib/sbitmap.c:sbitmap_init_node
  - lib/cpumask.c:alloc_cpumask_var_node
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:__netif_set_xps_queue
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff812e92d0-ffffffff812e957d: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f0500)
Location: mm/slub.c:4078
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - kernel/events/core.c:perf_cgroup_ensure_storage
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/memblock.c:memblock_alloc_internal
  - mm/memcontrol.c:memcg_alloc_page_obj_cgroups
  - crypto/api.c:crypto_create_tfm_node
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - lib/sbitmap.c:sbitmap_init_node
  - lib/cpumask.c:alloc_cpumask_var_node
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:expand_xps_map
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff812f0500-ffffffff812f07f5: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:4424
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - kernel/sched/core.c:dup_user_cpus_ptr
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - kernel/events/core.c:perf_cgroup_ensure_storage
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/memblock.c:memblock_alloc_internal
  - mm/memcontrol.c:memcg_alloc_page_obj_cgroups
  - crypto/api.c:crypto_create_tfm_node
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - lib/sbitmap.c:sbitmap_init_node
  - lib/cpumask.c:alloc_cpumask_var_node
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:expand_xps_map
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff81cc1a88-ffffffff81cc1aa1: __kmalloc_node.cold (STB_LOCAL)
ffffffff813384b0-ffffffff81338843: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:4470
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - kernel/sched/core.c:dup_user_cpus_ptr
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - kernel/events/core.c:perf_cgroup_ensure_storage
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/mempool.c:mempool_init_node
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/memblock.c:memblock_alloc_internal
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
  - crypto/api.c:crypto_create_tfm_node
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_tag_set_tags
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - lib/bitmap.c:bitmap_zalloc_node
  - lib/cpumask.c:alloc_cpumask_var_node
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:expand_xps_map
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff81e73f52-ffffffff81e73f6b: __kmalloc_node.cold (STB_LOCAL)
ffffffff813aa350-ffffffff813aa75f: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:973
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - kernel/sched/core.c:alloc_user_cpus_ptr
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - kernel/bpf/memalloc.c:__alloc
  - kernel/bpf/memalloc.c:__alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/mempool.c:mempool_init_node
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/memblock.c:memblock_alloc_internal
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
  - crypto/api.c:crypto_create_tfm_node
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_tag_set_tags
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - lib/bitmap.c:bitmap_zalloc_node
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:expand_xps_map
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - lib/cpumask.c:alloc_cpumask_var_node
```
**Symbols:**

```
ffffffff820632e7-ffffffff8206338a: __kmalloc_node.cold (STB_LOCAL)
ffffffff813a1f10-ffffffff813a1fea: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:990
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - kernel/sched/core.c:alloc_user_cpus_ptr
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - kernel/bpf/memalloc.c:__alloc
  - kernel/bpf/memalloc.c:__alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/mempool.c:mempool_init_node
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/memblock.c:memblock_alloc_internal
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_tag_set_tags
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - lib/bitmap.c:bitmap_zalloc_node
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:expand_xps_map
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - lib/cpumask.c:alloc_cpumask_var_node
```
**Symbols:**

```
ffffffff820e2b3c-ffffffff820e2b5b: __kmalloc_node.cold (STB_LOCAL)
ffffffff813d5390-ffffffff813d5500: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3986
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - kernel/sched/core.c:alloc_user_cpus_ptr
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_kmalloc_node
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
  - kernel/bpf/memalloc.c:__alloc
  - kernel/bpf/memalloc.c:__alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/mempool.c:mempool_init_node
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/memblock.c:memblock_alloc_internal
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_realloc_tag_set_tags
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-ia-ranges.c:disk_alloc_independent_access_ranges
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blk_revalidate_zone_cb
  - block/blk-zoned.c:blkdev_zone_reset_all_emulated
  - lib/bitmap.c:bitmap_zalloc_node
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:expand_xps_map
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv4/tcp_sigpool.c:sigpool_reserve_scratch
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - lib/cpumask.c:alloc_cpumask_var_node
  - lib/objpool.c:objpool_init_percpu_slots
```
**Symbols:**

```
ffffffff821c208e-ffffffff821c20ad: __kmalloc_node.cold (STB_LOCAL)
ffffffff8145bdf0-ffffffff8145c2ef: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010348b90)
Location: mm/slub.c:3845
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:get_callchain_buffers
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/memblock.c:memblock_alloc_internal
  - security/apparmor/lsm.c:alloc_buffers
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_add_in_port
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/sock_map.c:sock_hash_update_common
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffff800010348b90-ffff800010348e64: __kmalloc_node (STB_GLOBAL)
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
In kernel/workqueue.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/irq/irqdomain.c (c03d2fa4)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/taskstats.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/bpf/syscall.c (c0495240)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
```
```
In kernel/bpf/hashtab.c (c04aa490)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/lpm_trie.c (c04af20c)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
```
```
In kernel/bpf/local_storage.c (c04b066c)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/events/ring_buffer.c (c04d2600)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (c04d2ec0)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In mm/mempool.c (c04e254c)
Location: include/linux/slab.h:420
Inline: True
```
```
In mm/util.c (c04ff808)
Location: include/linux/slab.h:420
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In mm/vmalloc.c (c052c424)
Location: include/linux/slab.h:420
Inline: True
```
```
In mm/memblock.c (c1532558)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/zswap.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In mm/dmapool.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In security/apparmor/lsm.c (c15444bc)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In block/elevator.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In block/blk-flush.c (c0794004)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (c079f3f8)
Location: include/linux/slab.h:420
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
In block/blk-mq-tag.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In block/genhd.c (c07a6c84)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In block/blk-iocost.c (c07bfcec)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In block/blk-zoned.c (c07c7964)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/genalloc.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In lib/sbitmap.c (c0811fe0)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081c1cc)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (c0b4ed34)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In net/core/sysctl_net_core.c (c0ce0f24)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (c0cea614)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In net/core/sock_map.c (c0d38714)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/sched/sch_generic.c (c0d4bcd0)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In net/ipv6/seg6_hmac.c (c15ba488)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0000000004274d0)
Location: mm/slub.c:3845
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/memblock.c:memblock_alloc_internal
  - security/apparmor/lsm.c:apparmor_init
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/sock_map.c:sock_hash_update_common
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
c0000000004274d0-c000000000427974: __kmalloc_node (STB_GLOBAL)
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
In kernel/workqueue.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/smpboot.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffe00011af2e)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
```
```
In kernel/taskstats.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffe00019f092)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_area_alloc
```
```
In kernel/bpf/hashtab.c (ffffffe0001afbc6)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
```
In kernel/bpf/lpm_trie.c (ffffffe0001b4d0a)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
```
```
In kernel/bpf/local_storage.c (ffffffe0001b5f7a)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffe0001d1642)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffe0001d1d12)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In mm/mempool.c (ffffffe0001da284)
Location: include/linux/slab.h:420
Inline: True
```
```
In mm/util.c (ffffffe0001f2afe)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - mm/util.c:kvmalloc_node
```
```
In mm/backing-dev.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In mm/vmalloc.c (ffffffe00021847c)
Location: include/linux/slab.h:420
Inline: True
```
```
In mm/memblock.c (ffffffe000016cdc)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
```
```
In mm/zswap.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In mm/dmapool.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In mm/sparse.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In security/apparmor/lsm.c (ffffffe000026802)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In block/elevator.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In block/blk-flush.c (ffffffe0004282b2)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-mq.c (ffffffe000431a02)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In block/genhd.c (ffffffe000437c5c)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - block/genhd.c:disk_expand_part_tbl
```
```
In block/partition-generic.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In block/blk-iocost.c (ffffffe00044b6d4)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_alloc
```
```
In block/mq-deadline.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In block/blk-zoned.c (ffffffe0004525d0)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In lib/genalloc.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In lib/sbitmap.c (ffffffe00049474c)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000692a86)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/md/dm.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffe000752088)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffe00075a7ca)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/page_pool.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In net/core/sock_map.c (ffffffe000799c12)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
```
```
In net/sched/sch_generic.c (ffffffe0007aad22)
Location: include/linux/slab.h:420
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/slab.h:420
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffe000043f1c)
Location: include/linux/slab.h:420
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
<summary>In <code>aws</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129fcc0)
Location: mm/slub.c:3845
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/memblock.c:memblock_alloc_internal
  - security/apparmor/lsm.c:apparmor_init
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/sock_map.c:sock_hash_update_common
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - lib/cpumask.c:alloc_cpumask_var_node
```
**Symbols:**

```
ffffffff8129fcc0-ffffffff8129ffd9: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812917e0)
Location: mm/slub.c:3845
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/memblock.c:memblock_alloc_internal
  - security/apparmor/lsm.c:apparmor_init
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/sock_map.c:sock_hash_update_common
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - lib/cpumask.c:alloc_cpumask_var_node
```
**Symbols:**

```
ffffffff812917e0-ffffffff81291af9: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129dad0)
Location: mm/slub.c:3845
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/memblock.c:memblock_alloc_internal
  - security/apparmor/lsm.c:apparmor_init
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/sock_map.c:sock_hash_update_common
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - lib/cpumask.c:alloc_cpumask_var_node
```
**Symbols:**

```
ffffffff8129dad0-ffffffff8129dde9: __kmalloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__kmalloc_node(size_t size, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812acf30)
Location: mm/slub.c:3845
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/bpf/syscall.c:bpf_map_area_alloc
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/lpm_trie.c:lpm_trie_node_alloc
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/callchain.c:alloc_callchain_buffers
  - mm/util.c:kvmalloc_node
  - mm/util.c:kvmalloc_node
  - mm/memblock.c:memblock_alloc_internal
  - security/apparmor/lsm.c:apparmor_init
  - block/blk-flush.c:blk_alloc_flush_queue
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/blk-mq.c:blk_mq_alloc_rq_map
  - block/genhd.c:disk_expand_part_tbl
  - block/blk-iocost.c:ioc_pd_alloc
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/sock_map.c:sock_hash_update_common
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - lib/cpumask.c:alloc_cpumask_var_node
```
**Symbols:**

```
ffffffff812acf30-ffffffff812ad259: __kmalloc_node (STB_GLOBAL)
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
