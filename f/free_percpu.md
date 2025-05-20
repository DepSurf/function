# Function: <code>free_percpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811b07e0)
Location: mm/percpu.c:1231
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/events/intel/uncore.c:uncore_type_exit
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_alloc
  - kernel/locking/percpu-rwsem.c:percpu_free_rwsem
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/srcu.c:cleanup_srcu_struct
  - kernel/smp.c:hotplug_cfd
  - kernel/module.c:free_module
  - kernel/module.c:load_module
  - kernel/trace/trace.c:free_trace_buffers
  - kernel/trace/trace.c:free_trace_buffers
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_create
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:free_ioctx
  - fs/aio.c:SyS_io_setup
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_release
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_release
  - block/genhd.c:disk_release
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:alloc_disk_node
  - block/partition-generic.c:part_release
  - block/partition-generic.c:add_partition
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu_ida.c:percpu_ida_destroy
  - lib/percpu_counter.c:percpu_counter_destroy
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_cpuidle_devices_uninit
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_clear
  - net/core/flow.c:flow_cache_fini
  - net/core/flow.c:flow_cache_init
  - net/sched/sch_generic.c:qdisc_rcu_free
  - net/sched/sch_generic.c:qdisc_rcu_free
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:free_tcf
  - net/sched/act_api.c:free_tcf
  - net/sched/act_api.c:tcf_hash_create
  - net/sched/act_api.c:tcf_hash_create
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff811b07e0-ffffffff811b0989: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811c9a10)
Location: mm/percpu.c:1244
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_alloc
  - kernel/locking/percpu-rwsem.c:percpu_free_rwsem
  - kernel/irq/irqdesc.c:delayed_free_desc
  - kernel/rcu/srcu.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/trace/trace.c:free_trace_buffers
  - kernel/trace/trace.c:free_trace_buffers
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:free_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_destroy
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_release
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu_ida.c:percpu_ida_destroy
  - lib/percpu_counter.c:percpu_counter_destroy
  - arch/x86/lib/msr.c:msrs_free
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_clear
  - net/core/flow.c:flow_cache_fini
  - net/core/flow.c:flow_cache_init
  - net/core/dst_cache.c:dst_cache_destroy
  - net/sched/sch_generic.c:qdisc_rcu_free
  - net/sched/sch_generic.c:qdisc_rcu_free
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
  - net/sched/act_api.c:tcf_hash_create
  - net/sched/act_api.c:free_tcf
  - net/sched/act_api.c:free_tcf
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff811c9a10-ffffffff811c9baa: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811d9b00)
Location: mm/percpu.c:1248
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_alloc
  - kernel/locking/percpu-rwsem.c:percpu_free_rwsem
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcu.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/trace/trace.c:free_trace_buffers
  - kernel/trace/trace.c:free_trace_buffers
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:free_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu_ida.c:percpu_ida_destroy
  - lib/percpu_counter.c:percpu_counter_destroy
  - arch/x86/lib/msr.c:msrs_free
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_clear
  - net/core/flow.c:flow_cache_fini
  - net/core/flow.c:flow_cache_init
  - net/core/dst_cache.c:dst_cache_destroy
  - net/sched/sch_generic.c:qdisc_rcu_free
  - net/sched/sch_generic.c:qdisc_rcu_free
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
  - net/sched/act_api.c:tcf_hash_create
  - net/sched/act_api.c:free_tcf
  - net/sched/act_api.c:free_tcf
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_init
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff811d9b00-ffffffff811d9c9a: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811e3180)
Location: mm/percpu.c:1248
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:free_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu_ida.c:percpu_ida_destroy
  - arch/x86/lib/msr.c:msrs_free
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/neighbour.c:neigh_table_clear
  - net/core/flow.c:flow_cache_fini
  - net/core/flow.c:flow_cache_init
  - net/sched/sch_generic.c:qdisc_rcu_free
  - net/sched/sch_generic.c:qdisc_rcu_free
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/act_api.c:tcf_hash_create
  - net/sched/act_api.c:tcf_hash_create
  - net/sched/act_api.c:free_tcf
  - net/sched/act_api.c:free_tcf
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff811e3180-ffffffff811e3349: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811faa70)
Location: mm/percpu.c:1697
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/stat.c:cgroup_stat_exit
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:free_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu_ida.c:percpu_ida_destroy
  - arch/x86/lib/msr.c:msrs_free
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - drivers/net/xen-netfront.c:xennet_free_netdev
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:free_tcf
  - net/sched/act_api.c:free_tcf
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff811faa70-ffffffff811fac1e: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8121aa30)
Location: mm/percpu.c:1707
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:_cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_kprobe.c:free_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu_ida.c:percpu_ida_destroy
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:__tcf_idr_release
  - net/sched/act_api.c:__tcf_idr_release
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff8121aa30-ffffffff8121abda: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122d9e0)
Location: mm/percpu.c:1718
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:_cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - lib/percpu-refcount.c:percpu_ref_exit
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff8122d9e0-ffffffff8122db8a: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123d710)
Location: mm/percpu.c:1955
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - lib/percpu-refcount.c:percpu_ref_exit
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff8123d710-ffffffff8123d8f3: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124bb60)
Location: mm/percpu.c:1955
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_group_item_put
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff8124bb60-ffffffff8124bd43: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff8127a350)
Location: mm/percpu.c:1932
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_serial_worker
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:zswap_pool_destroy
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:alloc_mem_cgroup_per_node_info
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devlink_trap_group_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_register
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_free
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff8127a350-ffffffff8127a4a9: free_percpu.part.0 (STB_LOCAL)
ffffffff8127a4b0-ffffffff8127a4c6: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff81285530)
Location: mm/percpu.c:2080
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_serial_worker
  - mm/shmem.c:shmem_fill_super
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:zswap_pool_destroy
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_create
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:alloc_mem_cgroup_per_node_info
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
  - fs/block_dev.c:bdev_free_inode
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_exit_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_exit_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_init_shared_sbitmap
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:__percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_init
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devlink_trap_group_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_register
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_free
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/af_inet6.c:ipv6_init_mibs
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff81285530-ffffffff812856ac: free_percpu.part.0 (STB_LOCAL)
ffffffff812856b0-ffffffff812856c6: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff8128a2a0)
Location: mm/percpu.c:2081
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:do_blk_trace_setup
  - kernel/trace/blktrace.c:blk_trace_remove
  - kernel/trace/blktrace.c:blk_trace_remove
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_serial_worker
  - mm/shmem.c:shmem_fill_super
  - mm/page_alloc.c:zone_pcp_reset
  - mm/memory_hotplug.c:add_memory_resource
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:zswap_pool_destroy
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_create
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/block_dev.c:bdev_free_inode
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_exit_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_exit_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_init_shared_sbitmap
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:__percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_init_node
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_local.c:destroy_attr_counters
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff8128a2a0-ffffffff8128a4b6: free_percpu.part.0 (STB_LOCAL)
ffffffff8128a4c0-ffffffff8128a4d6: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff812c9f70)
Location: mm/percpu.c:2264
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/topology.c:__sdt_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_serial_worker
  - mm/shmem.c:shmem_fill_super
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_reset
  - mm/memory_hotplug.c:add_memory_resource
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:zswap_pool_destroy
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/bdev.c:bdev_free_inode
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_exit_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_exit_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/blk-mq-sched.c:blk_mq_exit_sched
  - block/blk-mq-sched.c:blk_mq_exit_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - block/mq-deadline.c:dd_exit_sched
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_init_node
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/hv/hv_common.c:hv_common_free
  - drivers/hv/hv_common.c:hv_common_free
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_local.c:destroy_attr_counters
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff812c9cb0-ffffffff812c9f64: free_percpu.part.0 (STB_LOCAL)
ffffffff81cbb035-ffffffff81cbb088: free_percpu.part.0.cold (STB_LOCAL)
ffffffff812c9f70-ffffffff812c9f86: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff81327e10)
Location: mm/percpu.c:2262
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/build_utility.c:psi_cgroup_free
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:cpuacct_css_free
  - kernel/sched/build_utility.c:cpuacct_css_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_serial_worker
  - mm/shmem.c:shmem_fill_super
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:zswap_pool_destroy
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_destroy
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - block/bdev.c:bdev_free_inode
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/blk-cgroup.c:blkg_free_workfn
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_init_node
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/hv/hv_common.c:hv_common_free
  - drivers/hv/hv_common.c:hv_common_free
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_core_stats_alloc
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/gro_cells.c:percpu_free_defer_callback
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/addrconf.c:ipv6_add_dev
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/seg6_local.c:destroy_attr_counters
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff81327a60-ffffffff81327e05: free_percpu.part.0 (STB_LOCAL)
ffffffff81e6cc2e-ffffffff81e6cc7e: free_percpu.part.0.cold (STB_LOCAL)
ffffffff81327e10-ffffffff81327e32: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff8139d240)
Location: mm/percpu.c:2254
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/build_utility.c:psi_cgroup_free
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:cpuacct_css_free
  - kernel/sched/build_utility.c:cpuacct_css_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:allocate_trace_buffers
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:free_mem_alloc_deferred
  - kernel/bpf/memalloc.c:free_mem_alloc_deferred
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:__free_rcu_tasks_trace
  - kernel/bpf/memalloc.c:__alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_serial_worker
  - mm/shmem.c:shmem_fill_super
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:zswap_pool_destroy
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_destroy
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - block/bdev.c:bdev_free_inode
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkg_free_workfn
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_init_node
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/spi/spi.c:spidev_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/hv/hv_common.c:hv_common_free
  - drivers/hv/hv_common.c:hv_common_free
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_core_stats_alloc
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devl_trap_groups_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/gro_cells.c:percpu_free_defer_callback
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/seg6_local.c:destroy_attr_counters
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff8139ce80-ffffffff8139d225: free_percpu.part.0 (STB_LOCAL)
ffffffff820630cf-ffffffff8206311f: free_percpu.part.0.cold (STB_LOCAL)
ffffffff8139d240-ffffffff8139d262: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff813d0340)
Location: mm/percpu.c:2254
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/fork.c:mm_init
  - kernel/fork.c:__mmdrop
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/build_utility.c:psi_cgroup_free
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:cpuacct_css_free
  - kernel/sched/build_utility.c:cpuacct_css_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:srcu_module_notify
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:allocate_trace_buffers
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:free_mem_alloc_deferred
  - kernel/bpf/memalloc.c:free_mem_alloc_deferred
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:__free_rcu_tasks_trace
  - kernel/bpf/memalloc.c:__alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_serial_worker
  - mm/shmem.c:shmem_fill_super
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:zswap_pool_destroy
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_destroy
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - block/bdev.c:bdev_free_inode
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_free_workfn
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_init_node
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/spi/spi.c:spidev_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_remove
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/hv/hv_common.c:hv_common_free
  - drivers/hv/hv_common.c:hv_common_free
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_core_stats_alloc
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/page_pool.c:page_pool_release
  - net/core/gro_cells.c:percpu_free_defer_callback
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/seg6_local.c:destroy_attr_counters
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
  - net/devlink/leftover.c:devl_trap_groups_register
  - net/devlink/leftover.c:devlink_trap_unregister
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff813cff50-ffffffff813d032a: free_percpu.part.0 (STB_LOCAL)
ffffffff820e296c-ffffffff820e29bc: free_percpu.part.0.cold (STB_LOCAL)
ffffffff813d0340-ffffffff813d0362: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff813fae20)
Location: mm/percpu.c:2285
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/events/amd/ibs.c:perf_event_ibs_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/fork.c:mm_init
  - kernel/fork.c:__mmdrop
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/build_utility.c:psi_cgroup_free
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:cpuacct_css_free
  - kernel/sched/build_utility.c:cpuacct_css_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:srcu_module_notify
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_destroy_buf
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/trace.c:allocate_trace_buffers
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/memalloc.c:destroy_mem_alloc
  - kernel/bpf/memalloc.c:destroy_mem_alloc
  - kernel/bpf/memalloc.c:free_mem_alloc_deferred
  - kernel/bpf/memalloc.c:free_mem_alloc_deferred
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:__free_rcu_tasks_trace
  - kernel/bpf/memalloc.c:__alloc
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_serial_worker
  - mm/shmem.c:shmem_put_super
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:zone_pcp_reset
  - mm/slub.c:__kmem_cache_release
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:zswap_pool_destroy
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:zswap_pool_create
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_destroy
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - block/bdev.c:bdev_free_inode
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_alloc_hctx
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_free_workfn
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu-refcount.c:percpu_ref_init
  - lib/sbitmap.c:sbitmap_queue_init_node
  - lib/sbitmap.c:sbitmap_init_node
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/nvdimm/region_devs.c:nd_region_release
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/spi/spi.c:spidev_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_remove
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/hv/hv_common.c:hv_common_free
  - drivers/hv/hv_common.c:hv_common_free
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:netdev_core_stats_inc
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_create
  - net/core/page_pool.c:page_pool_init
  - net/core/gro_cells.c:percpu_free_defer_callback
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_free_cb
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_exit
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/af_inet6.c:inet6_net_init
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/seg6_local.c:destroy_attr_counters
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
  - net/devlink/trap.c:devl_trap_groups_register
  - net/devlink/trap.c:devlink_trap_unregister
  - net/mptcp/mib.c:mptcp_mib_alloc
```
**Symbols:**

```
ffffffff813faad0-ffffffff813fae0b: free_percpu.part.0 (STB_LOCAL)
ffffffff821bf35d-ffffffff821bf3ad: free_percpu.part.0.cold (STB_LOCAL)
ffffffff813fae20-ffffffff813fae42: free_percpu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e2648)
Location: mm/percpu.c:1955
Inline: True
Direct callers:
  - virt/kvm/arm/arm.c:kvm_arch_destroy_vm
  - virt/kvm/arm/arm.c:kvm_arch_init_vm
  - arch/arm/xen/enlighten.c:xen_guest_init
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/firmware/arm_sdei.c:sdei_event_destroy
  - drivers/clocksource/arm_arch_timer.c:arch_timer_register
  - drivers/perf/arm_pmu.c:armpmu_free
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_group_item_destroy
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffff8000102e2648-ffff8000102e28c4: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0506974)
Location: mm/percpu.c:1955
Inline: True
Direct callers:
  - arch/arm/kernel/smp_twd.c:twd_local_timer_of_register
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/clocksource/arm_arch_timer.c:arch_timer_of_init
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
  - drivers/perf/arm_pmu.c:armpmu_free
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_group_item_destroy
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
c0506974-c0506b90: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0000000003a26c0)
Location: mm/percpu.c:1955
Inline: True
Direct callers:
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_group_item_put
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
c0000000003a26c0-c0000000003a29e8: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001f9342)
Location: mm/percpu.c:1955
Inline: True
Direct callers:
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_init
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - lib/percpu_counter.c:percpu_counter_destroy
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_group_item_destroy
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffe0001f9342-ffffffe0001f94c8: free_percpu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812441b0)
Location: mm/percpu.c:1955
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_group_item_put
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff812441b0-ffffffff81244393: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81237180)
Location: mm/percpu.c:1955
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/vxlan.c:vxlan_uninit
  - drivers/net/vxlan.c:vxlan_init
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_group_item_put
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/ip_tunnel.c:ip_tunnel_init
  - net/ipv4/ip_tunnel.c:ip_tunnel_dev_free
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81237180-ffffffff81237363: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81241f50)
Location: mm/percpu.c:1955
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_group_item_put
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_init_net
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_init_net
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_cleanup_net_list
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_cleanup_net_list
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81241f50-ffffffff81242133: free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void free_percpu(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812516f0)
Location: mm/percpu.c:1955
Inline: True
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:perf_ibs_pmu_init
  - arch/x86/kernel/acpi/cstate.c:ffh_cstate_exit
  - kernel/workqueue.c:rcu_free_wq
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/cpuacct.c:cpuacct_css_free
  - kernel/sched/psi.c:psi_cgroup_free
  - kernel/irq/irqdesc.c:irq_kobj_release
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/smp.c:smpcfd_dead_cpu
  - kernel/module.c:load_module
  - kernel/module.c:free_module
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/trace/trace_functions_graph.c:graph_trace_close
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/blktrace.c:blk_trace_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_free_elems
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/bpf_lru_list.c:bpf_lru_destroy
  - kernel/bpf/local_storage.c:free_percpu_cgroup_storage_rcu
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/xskmap.c:xsk_map_free
  - kernel/events/core.c:perf_cgroup_css_free
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_unregister
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_free_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/page_alloc.c:zone_pcp_reset
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/slub.c:__kmem_cache_release
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - fs/namespace.c:free_vfsmnt
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-stat.c:blk_stat_free_callback_rcu
  - block/blk-mq-sysfs.c:blk_mq_sysfs_release
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:part_release
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_exit
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_rqos_exit
  - lib/percpu-refcount.c:percpu_ref_exit
  - arch/x86/lib/msr.c:msrs_free
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:dma_channel_table_init
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_percpu_release
  - drivers/net/loopback.c:loopback_dev_free
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_interface
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/md/dm-stats.c:dm_stats_cleanup
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_exit
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_exit_net
  - net/core/sock.c:sock_inuse_init_net
  - net/core/dev.c:free_netdev
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/neighbour.c:neigh_table_clear
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_group_item_put
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_free
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/sched/act_api.c:tcf_action_cleanup
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit
  - net/ipv4/icmp.c:icmp_sk_exit
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_exit_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/fib_trie.c:__trie_free_rcu
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/xfrm/xfrm_policy.c:xfrm_net_exit
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/af_inet6.c:ipv6_cleanup_mibs
  - net/ipv6/route.c:fib6_nh_release
  - net/ipv6/icmp.c:icmpv6_sk_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy_rcu
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff812516f0-ffffffff812518ec: free_percpu (STB_GLOBAL)
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
