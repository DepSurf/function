# Function: <code>__alloc_percpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811b1670)
Location: mm/percpu.c:1080
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/intel/uncore.c:uncore_types_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_alloc
  - kernel/sched/cpuacct.c:cpuacct_css_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcu.c:init_srcu_struct
  - kernel/smp.c:hotplug_cfd
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:SyS_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:SyS_io_setup
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:alloc_disk_node
  - block/partition-generic.c:add_partition
  - lib/percpu_ida.c:__percpu_ida_init
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/md/dm-stats.c:dm_stats_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/core/flow.c:flow_cache_init
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff811b1670-ffffffff811b1687: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811ca7d0)
Location: mm/percpu.c:1073
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_alloc
  - kernel/sched/cpuacct.c:cpuacct_css_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcu.c:init_srcu_struct
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:SyS_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:SyS_io_setup
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:alloc_disk_node
  - block/partition-generic.c:add_partition
  - lib/percpu_ida.c:__percpu_ida_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/md/dm-stats.c:dm_stats_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/core/flow.c:flow_cache_init
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff811ca7d0-ffffffff811ca7e7: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811da8f0)
Location: mm/percpu.c:1077
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_alloc
  - kernel/sched/cpuacct.c:cpuacct_css_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcu.c:init_srcu_struct
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/relay.c:relay_open
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:SyS_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:alloc_disk_node
  - block/partition-generic.c:add_partition
  - lib/percpu_ida.c:__percpu_ida_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/md/dm-stats.c:dm_stats_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/core/flow.c:flow_cache_init
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff811da8f0-ffffffff811da907: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811e4010)
Location: mm/percpu.c:1077
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/relay.c:relay_open
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:SyS_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_create
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - lib/percpu_ida.c:__percpu_ida_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/core/flow.c:flow_cache_init
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff811e4010-ffffffff811e4027: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811faa50)
Location: mm/percpu.c:1537
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/hyperv/mmu.c:hyper_alloc_mmu
  - arch/x86/hyperv/mmu.c:hyper_alloc_mmu
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/stat.c:cgroup_stat_init
  - kernel/relay.c:relay_open
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:SYSC_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_create
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - lib/percpu_ida.c:__percpu_ida_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff811faa50-ffffffff811faa67: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8121b640)
Location: mm/percpu.c:1546
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - lib/percpu_ida.c:__percpu_ida_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff8121b640-ffffffff8121b657: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122e620)
Location: mm/percpu.c:1557
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff8122e620-ffffffff8122e637: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123ee90)
Location: mm/percpu.c:1794
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff8123ee90-ffffffff8123eea7: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124d2f0)
Location: mm/percpu.c:1794
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff8124d2f0-ffffffff8124d307: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8127b630)
Location: mm/percpu.c:1771
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:alloc_mem_cgroup_per_node_info
  - mm/memcontrol.c:alloc_mem_cgroup_per_node_info
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__alloc_disk_node
  - block/partitions/core.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/iova.c:init_iova_rcaches
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/packet/af_packet.c:packet_create
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff8127b630-ffffffff8127b647: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81286160)
Location: mm/percpu.c:1904
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/shmem.c:shmem_fill_super
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - fs/namespace.c:alloc_vfsmnt
  - fs/block_dev.c:bdev_alloc
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/iova.c:init_iova_rcaches
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/packet/af_packet.c:packet_create
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff81286160-ffffffff81286177: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8128ad40)
Location: mm/percpu.c:1905
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/trace_functions.c:func_set_flag
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/shmem.c:shmem_fill_super
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - fs/namespace.c:alloc_vfsmnt
  - fs/block_dev.c:bdev_alloc
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/packet/af_packet.c:packet_create
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff8128ad40-ffffffff8128ad57: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812cb100)
Location: mm/percpu.c:1948
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/trace_functions.c:func_set_flag
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/shmem.c:shmem_fill_super
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/bdev.c:bdev_alloc
  - block/bio.c:bioset_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/iommu/iova.c:init_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/hv/hv_common.c:hv_common_init
  - drivers/hv/hv_common.c:hv_common_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/packet/af_packet.c:packet_create
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff812cb100-ffffffff812cb117: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81328ad0)
Location: mm/percpu.c:1948
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/relay.c:relay_open
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/trace.c:trace_array_init_printk
  - kernel/trace/trace_functions.c:func_set_flag
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/shmem.c:shmem_fill_super
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:free_area_init_core_hotplug
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - block/bdev.c:bdev_alloc
  - block/bio.c:bioset_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/hv/hv_common.c:hv_common_init
  - drivers/hv/hv_common.c:hv_common_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/packet/af_packet.c:packet_create
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff81328ad0-ffffffff81328af3: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8139dd30)
Location: mm/percpu.c:1941
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/relay.c:relay_open
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/trace.c:trace_array_init_printk
  - kernel/trace/trace_functions.c:func_set_flag
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/shmem.c:shmem_fill_super
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:free_area_init_core_hotplug
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - block/bdev.c:bdev_alloc
  - block/bio.c:bioset_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/hv/hv_common.c:hv_common_init
  - drivers/hv/hv_common.c:hv_common_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/packet/af_packet.c:packet_create
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff8139dd30-ffffffff8139dd53: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813d0e90)
Location: mm/percpu.c:1941
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/fork.c:mm_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:srcu_module_notify
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/relay.c:relay_open
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/trace.c:trace_array_init_printk
  - kernel/trace/trace_functions.c:func_set_flag
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/shmem.c:shmem_fill_super
  - mm/mm_init.c:free_area_init_core_hotplug
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - block/bdev.c:bdev_alloc
  - block/bio.c:bioset_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/hv/hv_common.c:hv_common_init
  - drivers/hv/hv_common.c:hv_common_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/core/page_pool.c:page_pool_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/packet/af_packet.c:packet_create
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff813d0e90-ffffffff813d0eb3: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813fb830)
Location: mm/percpu.c:1941
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/fork.c:mm_init
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/core.c:sched_tick_offload_init
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:srcu_module_notify
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/crash_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/relay.c:relay_open
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/trace.c:trace_array_init_printk
  - kernel/trace/trace_functions.c:func_set_flag
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/shmem.c:shmem_fill_super
  - mm/mm_init.c:free_area_init_core_hotplug
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/slub.c:kmem_cache_open
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - block/bdev.c:bdev_alloc
  - block/bio.c:bioset_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm.c:alloc_dev
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/hv/hv_common.c:hv_common_init
  - drivers/hv/hv_common.c:hv_common_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/core/page_pool.c:page_pool_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/packet/af_packet.c:packet_create
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff813fb830-ffffffff813fb853: __alloc_percpu (STB_GLOBAL)
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
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e3ba8)
Location: mm/percpu.c:1794
Inline: False
Direct callers:
  - arch/arm64/kernel/fpsimd.c:sve_setup
  - virt/kvm/arm/arm.c:kvm_arch_init_vm
  - arch/arm/xen/enlighten.c:xen_guest_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/firmware/arm_sdei.c:sdei_event_register
  - drivers/clocksource/arm_arch_timer.c:arch_timer_register
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffff8000102e3ba8-ffff8000102e3be4: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0507bb4)
Location: mm/percpu.c:1794
Inline: False
Direct callers:
  - arch/arm/kernel/smp_twd.c:twd_local_timer_of_register
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:__se_sys_io_setup
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init
  - drivers/clocksource/timer-qcom.c:msm_dt_timer_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_of_init
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
c0507bb4-c0507bd8: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0000000003a3540)
Location: mm/percpu.c:1794
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
c0000000003a3540-c0000000003a355c: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001f9c64)
Location: mm/percpu.c:1794
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:__se_sys_io_setup
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffe0001f9c64-ffffffe0001f9c9e: __alloc_percpu (STB_GLOBAL)
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
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81245940)
Location: mm/percpu.c:1794
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff81245940-ffffffff81245957: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812388f0)
Location: mm/percpu.c:1794
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/core.c:sched_tick_offload_init
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/hv/hv.c:hv_init
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff812388f0-ffffffff81238907: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812436e0)
Location: mm/percpu.c:1794
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_init_net
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_init_net
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff812436e0-ffffffff812436f7: __alloc_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__alloc_percpu(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81252ea0)
Location: mm/percpu.c:1794
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_init
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/psi.c:psi_cgroup_alloc
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/matrix.c:irq_alloc_matrix
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/kexec_core.c:crash_notes_memory_init
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/swapfile.c:__do_sys_swapon
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:kmem_cache_open
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - fs/namespace.c:alloc_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-stat.c:blk_stat_alloc_callback
  - block/genhd.c:__alloc_disk_node
  - block/partition-generic.c:add_partition
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/iommu/iova.c:init_iova_flush_queue
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - net/core/sock.c:sock_inuse_init_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_init
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:fib_trie_table
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff81252ea0-ffffffff81252eb7: __alloc_percpu (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
