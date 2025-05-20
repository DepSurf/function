# Function: <code>raw_atomic_long_add</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81129bc0)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
```
```
In kernel/sched/core.c (ffffffff8114d685)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/fair.c (ffffffff8115c61c)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
```
```
In kernel/sched/build_utility.c (ffffffff81187fb8)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
```
```
In kernel/locking/rwsem.c (ffffffff8118df26)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff812268f3)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff81232a6f)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/trampoline.c (ffffffff81337a96)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8135577d)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff8135a1e0)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81374b6b)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmscan.c (ffffffff813b514d)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff813c91f6)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_diff
  - mm/vmstat.c:fold_diff
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:inc_node_state
  - mm/vmstat.c:inc_node_state
  - mm/vmstat.c:mod_node_page_state
  - mm/vmstat.c:mod_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:mod_zone_page_state
  - mm/vmstat.c:mod_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:fold_vm_numa_events
```
```
In mm/backing-dev.c (ffffffff813cb387)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff813e17c9)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memory.c (ffffffff813f1ce6)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pmd_install
```
```
In mm/vmalloc.c (ffffffff814174f0)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff81418e88)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff836e75a3)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81424811)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff8142d69a)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff814418ab)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/slub.c (ffffffff8145d1c0)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff81476959)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff814827c3)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8149087a)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:get_obj_cgroup_from_page
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/zsmalloc.c (ffffffff8149d7a2)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff814a3bd6)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff814f63bb)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:wb_io_lists_populated
```
```
In fs/aio.c (ffffffff8152c248)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
```
```
In block/blk-mq.c (ffffffff817831ac)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-cgroup.c (ffffffff817a2018)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff817a4a10)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In io_uring/io_uring.c (ffffffff817c90fa)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_activate_pollwq
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:__io_alloc_req_refill
```
```
In lib/percpu-refcount.c (ffffffff81818188)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8182ec7b)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/pci/p2pdma.c (ffffffff8195f562)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81b7bd00)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd3ed2)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81d5e8d9)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - drivers/md/md.c:md_account_bio
  - drivers/md/md.c:md_write_start
```
```
In net/core/sock.c (ffffffff81e0cbff)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef56b4)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81f2865a)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69bc2)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f7e729)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv6/reassembly.c (ffffffff81ff96ab)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200d472)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
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
In kernel/ptrace.c (ffffffff81110f54)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/kthread.c (ffffffff81134200)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
```
```
In kernel/cred.c (ffffffff8113e566)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/sched/core.c (ffffffff8115943b)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/fair.c (ffffffff8116679a)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/sched/fair.c:switched_from_fair
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:__update_blocked_fair
```
```
In kernel/sched/build_utility.c (ffffffff81196768)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
```
```
In kernel/locking/rwsem.c (ffffffff8119c8d6)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811e32bc)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_enqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e583)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff8124c1ef)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff81310765)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/trampoline.c (ffffffff8135d8d6)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/memalloc.c (ffffffff81372fd0)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8137e0fd)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff81382d90)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8139de9b)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/watch_queue.c (ffffffff813b2bde)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/shrinker.c (ffffffff813e4c41)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/shrinker.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff813f3b86)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_diff
  - mm/vmstat.c:fold_diff
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:inc_node_state
  - mm/vmstat.c:inc_node_state
  - mm/vmstat.c:mod_node_page_state
  - mm/vmstat.c:mod_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:mod_zone_page_state
  - mm/vmstat.c:mod_zone_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_node_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__dec_zone_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/vmstat.c:__inc_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:fold_vm_numa_events
```
```
In mm/backing-dev.c (ffffffff813f5b91)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/percpu.c (ffffffff813fa1ad)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
```
```
In mm/workingset.c (ffffffff8140bf09)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memory.c (ffffffff8141c9d6)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pmd_install
```
```
In mm/vmalloc.c (ffffffff81444000)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff814459d8)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff83919da3)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81451641)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/slub.c (ffffffff814578c0)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__memcg_slab_post_alloc_hook
```
```
In mm/swapfile.c (ffffffff8146721a)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8147bb32)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/huge_memory.c (ffffffff814a61bf)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff814b1b43)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff814c0157)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_replace_folio
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:get_obj_cgroup_from_folio
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:__refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/zsmalloc.c (ffffffff814ccf68)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff814d4a76)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/file_table.c (ffffffff814e26a3)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - fs/file_table.c:init_file
```
```
In fs/fs-writeback.c (ffffffff8152aafb)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:wb_io_lists_populated
```
```
In fs/fs_context.c (ffffffff81538fd9)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/aio.c (ffffffff81561128)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
```
```
In security/keys/process_keys.c (ffffffff816cad23)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff816cbeb9)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff816cce92)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/audit.c (ffffffff81737344)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/domain.c (ffffffff8174198d)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
```
```
In block/blk-mq.c (ffffffff817c6cd9)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-cgroup.c (ffffffff817e5b65)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff817e85e0)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In io_uring/io_uring.c (ffffffff81816efe)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_activate_pollwq
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:__io_alloc_req_refill
  - io_uring/io_uring.c:io_prep_async_work
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In io_uring/sqpoll.c (ffffffff818201df)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In io_uring/register.c (ffffffff8182bb9e)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
```
```
In lib/percpu-refcount.c (ffffffff8185d488)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8188083b)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/pci/p2pdma.c (ffffffff819a8bbf)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81bcfd2f)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c28b4c)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff81d4d3db)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/md/md.c (ffffffff81e15a9d)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - drivers/md/md.c:md_account_bio
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_flush_request
```
```
In net/core/sock.c (ffffffff81ec957f)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9664)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81fed0ea)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/inet_fragment.c (ffffffff82030242)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff82044dd4)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/unix/af_unix.c (ffffffff8207c0e6)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/reassembly.c (ffffffff820c731b)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dc43c)
Location: include/linux/atomic/atomic-long.h:118
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
