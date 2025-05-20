# Function: <code>arch_atomic_long_add</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
```
```
In kernel/kthread.c (ffffffff810df972)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
```
```
In kernel/sched/core.c (ffffffff810fd854)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810fe57c)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/fair.c (ffffffff81106393)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
```
```
In kernel/locking/rwsem.c (ffffffff8112cff2)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d524)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff811a64f4)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/trampoline.c (ffffffff8125f491)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff8127454d)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81286eb6)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff8129c402)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/vmscan.c (ffffffff812b416c)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff812c4d06)
Location: include/linux/atomic/atomic-long.h:51
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
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:fold_vm_numa_events
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
```
```
In mm/backing-dev.c (ffffffff812c733d)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff812d6a29)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff812e39e7)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffff812ffac0)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
```
```
In mm/page_alloc.c (ffffffff81300c37)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff832da75e)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff8130a973)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff8131274a)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8132392d)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/slub.c (ffffffff8133502a)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff81348671)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff81350563)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8135b90e)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/zsmalloc.c (ffffffff8136491c)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff813696d0)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff813ac28a)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff813daa5c)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff813e166c)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:__io_splice_prep
  - fs/io_uring.c:io_prep_rw
  - fs/io_uring.c:tctx_task_work
  - fs/io_uring.c:io_fallback_req_func
```
```
In fs/dax.c (0)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff815e102b)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff815f1a8e)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff815f4e2c)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In lib/percpu-refcount.c (ffffffff8161b69e)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8162a7b7)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff8186fe31)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b62cc)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff819f27c2)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81b49246)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae1b3)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/reassembly.c (ffffffff81c2aa68)
Location: include/linux/atomic/atomic-long.h:51
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
In arch/x86/mm/pgtable.c (0)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
```
```
In kernel/kthread.c (ffffffff810f9cf0)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
```
```
In kernel/sched/core.c (ffffffff8111a26a)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/fair.c (ffffffff811212db)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
```
```
In kernel/sched/build_utility.c (ffffffff81148b38)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
```
```
In kernel/locking/rwsem.c (ffffffff8114e2f6)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd863)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/cpuset.c (ffffffff811d7987)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/trampoline.c (ffffffff812a9bd6)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff812c4bbb)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff812db81e)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmscan.c (ffffffff81310121)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff81322236)
Location: include/linux/atomic/atomic-long.h:51
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
In mm/backing-dev.c (ffffffff81323b99)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff81336159)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff81344d73)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pmd_install
```
```
In mm/vmalloc.c (ffffffff81366b84)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff813680e8)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff8348f875)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81373561)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff8137d2da)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff813914a3)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/slub.c (ffffffff813ad471)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff813be819)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff813c8813)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff813d51b9)
Location: include/linux/atomic/atomic-long.h:51
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
In mm/zsmalloc.c (ffffffff813e27eb)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff813e77f1)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff81432349)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81465472)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
```
```
In block/blk-mq.c (ffffffff81683a3e)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-mq-sched.c (ffffffff8168fc23)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff816a3a80)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff816a6a37)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In io_uring/io_uring.c (ffffffff816d7312)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_async_cancel
  - io_uring/io_uring.c:io_splice
  - io_uring/io_uring.c:io_tee
  - io_uring/io_uring.c:io_prep_rw
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:handle_prev_tw_list
```
```
In lib/percpu-refcount.c (ffffffff816e8eb8)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff816fbc21)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff819b67f0)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a0182f)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81b5b681)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd68d0)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81d412f6)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff81dc7f5f)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
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
In kernel/kthread.c (ffffffff8111ca30)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
```
```
In kernel/sched/core.c (ffffffff811419d2)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/fair.c (ffffffff8114a89c)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
```
```
In kernel/sched/build_utility.c (ffffffff81177368)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
```
```
In kernel/locking/rwsem.c (ffffffff8117d276)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff81210f03)
Location: include/linux/atomic/atomic-long.h:51
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
In kernel/cgroup/cpuset.c (ffffffff8121c67f)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/helpers.c (ffffffff812f44f6)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/trampoline.c (ffffffff81308b76)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup_iter.c (ffffffff81325542)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff8132a0a0)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81343ae5)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmscan.c (ffffffff8138373f)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff813963a6)
Location: include/linux/atomic/atomic-long.h:51
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
In mm/backing-dev.c (ffffffff81398407)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff813ad3d9)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memory.c (ffffffff813bcfa3)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pmd_install
```
```
In mm/vmalloc.c (ffffffff813e2923)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff813e4138)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff83ec1f5a)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff813f0cd1)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff813fa75a)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8140e4cc)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:add_reservation_in_range
  - mm/hugetlb.c:add_reservation_in_range
```
```
In mm/slub.c (ffffffff81427c48)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff81441097)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff8144cf03)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8145ac1a)
Location: include/linux/atomic/atomic-long.h:51
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
In mm/zsmalloc.c (ffffffff81469d36)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff8146f40c)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff814c2da1)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:wb_io_lists_populated
```
```
In fs/aio.c (ffffffff814f54af)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
```
```
In block/blk-mq.c (ffffffff817413be)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-mq-sched.c (ffffffff8174e7e4)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81763c2d)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81765950)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In io_uring/io_uring.c (ffffffff8178df41)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:handle_tw_list
  - io_uring/io_uring.c:__io_alloc_req_refill
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In io_uring/uring_cmd.c (0)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
```
```
In io_uring/net.c (0)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
```
```
In io_uring/rsrc.c (ffffffff817a0c2d)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_refs_refill
```
```
In io_uring/rw.c (0)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff817d8f78)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff817ee8c1)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/pci/p2pdma.c (ffffffff8191bf4f)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81b2ba00)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7fe7f)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81cf5051)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
```
```
In net/core/sock.c (ffffffff81d9e383)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/ip_fragment.c (ffffffff81e96e77)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ec9b0b)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a0a6)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f1ec29)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv6/reassembly.c (ffffffff81f98cd1)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81faca62)
Location: include/linux/atomic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
</details>
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
