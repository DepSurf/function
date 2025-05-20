# Function: <code>arch_atomic64_add</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/fork.c (ffffffff8108b067)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/kthread.c (ffffffff810b398a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c26de)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810c3436)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810c39c6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810d1fb8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810d3529)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810d712a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810dd1b0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819eff73)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
```
```
In kernel/cgroup/cgroup.c (ffffffff811438b4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/pids.c (ffffffff81146ec9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8114ad1f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/tracing_map.c (ffffffff8118989b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff811b5376)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/core.c (ffffffff811e1813)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
```
```
In kernel/memremap.c (ffffffff811e9b5c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/filemap.c (ffffffff811f003d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/page-writeback.c (ffffffff811fea1a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff81200e77)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In mm/vmscan.c (ffffffff8120aac8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81211757)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/vmstat.c (ffffffff8121716c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_diff
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
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
```
```
In mm/backing-dev.c (ffffffff81219151)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff8121ed78)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/workingset.c (ffffffff812257dd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/memory.c (ffffffff8122ee3e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:__pte_alloc
  - mm/memory.c:sync_mm_rss
```
```
In mm/rmap.c (ffffffff8123ea43)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff81246558)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812492c6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff81257373)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8126834e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff81276dd3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127c4ba)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/page_counter.c (ffffffff8127e2b5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff81286739)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/zsmalloc.c (ffffffff8128e2c5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff812a1eb4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812cc00b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff812f48cf)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (ffffffff812f9dd6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8136541c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813736cd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8138b18b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In block/bio.c (ffffffff81479acd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In block/blk-core.c (ffffffff81484722)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-mq.c (ffffffff8148ef0f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-cgroup.c (ffffffff814a789b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/cfq-iosched.c (ffffffff814b2b52)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
```
```
In lib/percpu-refcount.c (ffffffff814cb80d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff814d55cb)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free
```
```
In drivers/block/loop.c (ffffffff816ab9cb)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/usb/core/devio.c (ffffffff81767050)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff817f5526)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff818e96ee)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff81939413)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81990ab5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/fork.c (ffffffff8109370d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/kthread.c (ffffffff810bcc8a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff810cb9d2)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810cc6e6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810ccc86)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810db91c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810dc8c8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e1676)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e6e10)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b990)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f3cd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/pids.c (ffffffff81152a49)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff81156de1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/tracing_map.c (ffffffff8119714b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/events/core.c (ffffffff811f1c83)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
```
```
In kernel/memremap.c (ffffffff811fa6cb)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/filemap.c (ffffffff812023c9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/page_alloc.c (ffffffff812066b8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:memblock_free_pages
```
```
In mm/page-writeback.c (ffffffff8120f1fa)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/swap.c (ffffffff812137ec)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In mm/vmscan.c (ffffffff8121d7c8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81223739)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/vmstat.c (ffffffff8122a07c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_diff
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
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
```
```
In mm/backing-dev.c (ffffffff8122bfa1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81231d58)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/workingset.c (ffffffff81238d3f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/memory.c (ffffffff812418ce)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:__pte_alloc
  - mm/memory.c:sync_mm_rss
```
```
In mm/rmap.c (ffffffff81252fd7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/memblock.c (ffffffff828be664)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8125a97b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8125db93)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8126b9e5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8127de5a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff81288686)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81290b5c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/page_counter.c (ffffffff812929a5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8129b6a9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_split_huge_fixup
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/zsmalloc.c (ffffffff812a3bf5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff812b6c63)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812e0f24)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81309786)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (ffffffff8130dc34)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8137d7dc)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff8138bac2)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813a33ff)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (ffffffff8147819e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-core.c (ffffffff8149f73f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:generic_make_request
```
```
In block/blk-mq.c (ffffffff814a89a5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-cgroup.c (ffffffff814c34b7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814c4666)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff814e0543)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff814ea02b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free
```
```
In drivers/block/loop.c (ffffffff816cc76c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81714787)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff8178b5d0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff81821406)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819164c6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff81969000)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff819c71f3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/kthread.c (ffffffff810c2a76)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d3a44)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810d4b19)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810d5067)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810dd24f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e3869)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e812d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810edaa0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff810f86bd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b210)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/pids.c (ffffffff8115f099)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8116471e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/tracing_map.c (ffffffff811a53aa)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/cgroup.c (ffffffff811f8ccb)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8120984e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff81239d1c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_diff
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
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
```
```
In mm/backing-dev.c (ffffffff8123bc46)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81242348)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff8125424d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (ffffffff8126a6a1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126c668)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828d7833)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff81275956)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8127adea)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff81286ce4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff81299cad)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff8129bc02)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812a32c4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a9e8f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In mm/page_counter.c (ffffffff812ad375)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812b62b0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In mm/zsmalloc.c (ffffffff812bf00d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812c2d59)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In fs/exec.c (ffffffff812d3936)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812ff646)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8132b973)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a7391)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813b671b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813ce0a2)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (ffffffff814a606f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-core.c (ffffffff814cd80f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814d637c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814dd676)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f1bb7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814f2e2d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff8150c4e8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff81516ccd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff817081f7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff817500c4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff817c9be0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff818637e5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81978351)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf49f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a36350)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/kthread.c (ffffffff810c8fe6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ddf17)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810df0d9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/cputime.c (ffffffff810df626)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810e767f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810ef29f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f34fc)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f967f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff81104505)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff81166ece)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/pids.c (ffffffff8116acf9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8117056d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff811b0bda)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/cgroup.c (ffffffff81205e94)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81216bbe)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff8124801c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_diff
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
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
```
```
In mm/backing-dev.c (ffffffff8124a0f5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff812507d8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff812627ad)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (ffffffff812795b3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127b478)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828dfca4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff81284926)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8128a8ca)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff812968e4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff812a9b6d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812aba03)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812b47c4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bdfe6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812beec5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812c8112)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In mm/zsmalloc.c (ffffffff812d0f6d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812d4bb1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812e54c6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131455e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8133e7c3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813c0221)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813cf63b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813e7b55)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (ffffffff814c09bf)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-core.c (ffffffff814e6aff)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814ef6f3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814f6b06)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8150b197)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8150c3cd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff8150f92f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
```
```
In lib/percpu-refcount.c (ffffffff8152a338)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8153770d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff8172c447)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff817742b4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff817fa720)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff81895535)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819aecc1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06023)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a6ce70)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/kthread.c (ffffffff810d09d9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff810e64e1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810e73b9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810e7976)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810ed96d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f8c98)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fcbe7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff8110378f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff8110efb0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff81178631)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/pids.c (ffffffff8117c79a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff811818b4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
```
In kernel/trace/tracing_map.c (ffffffff811c939a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff811fb3dd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/bpf/cgroup.c (ffffffff8122d5ee)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81240c39)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff8127618c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_diff
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
In mm/backing-dev.c (ffffffff812782d4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/slab_common.c (ffffffff8127ee38)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/workingset.c (ffffffff812869e9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff812926ad)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffff812ac403)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff812ad618)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff82cfd116)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/swapfile.c (ffffffff812bad9c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff812c9e34)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:region_del
```
```
In mm/slub.c (ffffffff812d9f18)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812e0373)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812eaf1a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff812f41a0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812fd968)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__mod_lruvec_state
```
```
In mm/zsmalloc.c (ffffffff81307706)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff8130a6fb)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/fs-writeback.c (ffffffff8134e073)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8137849f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff81380855)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:__io_async_wake
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8140c351)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff814192fc)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81430c02)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In crypto/algapi.c (ffffffff815211e3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
```
```
In block/blk-mq-sched.c (ffffffff815575a6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8156c101)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8156da57)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In block/blk-iocost.c (ffffffff81570a2f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In lib/percpu-refcount.c (ffffffff8158da58)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8159bfa0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff817e7c07)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81836c1c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff818ca940)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff819629d5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In drivers/md/dm.c (ffffffff81979a90)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
```
```
In net/ipv4/ip_fragment.c (ffffffff81a990d6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5736)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81b65de9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/kthread.c (ffffffff810cb5c7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff810e43ac)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810e4ff9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810e5666)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810eb79d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f6eab)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fb0f7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff81101eaf)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff8110c2a9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff811753df)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/pids.c (ffffffff8117964a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e7c2)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
```
In kernel/trace/tracing_map.c (ffffffff811c6a5a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff811fa53d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/bpf/trampoline.c (ffffffff81222b51)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff81235b2a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8124b1ea)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff81280a94)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_diff
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
In mm/backing-dev.c (ffffffff81282a76)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff81290c39)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff8129cf94)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffff812b798d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff812b9019)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff82fe9b47)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/swapfile.c (ffffffff812c681c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff812d5a71)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:region_del
```
```
In mm/slub.c (ffffffff812e524a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memory_hotplug.c (ffffffff812eb2f3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812f8581)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff812ffa90)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff81309d92)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - mm/memcontrol.c:memcg_reparent_objcgs
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In mm/zsmalloc.c (ffffffff81312439)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff8131615c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff8135af31)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff813861ac)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff8138b041)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_sqe_files_unregister
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:io_async_buf_func
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8141f823)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff8142d3b5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814499c6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In crypto/algapi.c (ffffffff8153e233)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
```
```
In block/blk-mq-sched.c (ffffffff81573bc0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81585a8e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81587f7c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In block/blk-iocost.c (ffffffff8158be5f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In lib/percpu-refcount.c (ffffffff815aa6de)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff815b79d1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff817fcaf0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff8184767d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff818d5a50)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff81969422)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa3046)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81b024f6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81b74559)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/kthread.c (ffffffff810ccf04)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff810e636b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810e6fa9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810e7626)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810ed686)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f8ffb)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fd2ff)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff8110421f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff8110e0ee)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff81175f4e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_disable
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/pids.c (ffffffff8117a1a7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e7d4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff811c7a4a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff811fb47d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/bpf/trampoline.c (ffffffff81227391)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff81239d7a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8124d2a6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
```
In mm/filemap.c (ffffffff8125fa92)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/vmscan.c (ffffffff8127695c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff81285b94)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_diff
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
In mm/backing-dev.c (ffffffff81287b9b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff81296299)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff812a2677)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffff812bd3a0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In mm/page_alloc.c (ffffffff812be4e9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff831f433d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff812c5f73)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff812cd3bc)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff812dc775)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:region_del
```
```
In mm/slub.c (ffffffff812ece1a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff812fea74)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff81306733)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff813105fe)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:split_page_memcg
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_flush_lruvec_page_state
  - mm/memcontrol.c:refill_stock
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__mod_memcg_lruvec_state
```
```
In mm/zsmalloc.c (ffffffff81318414)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff8131c3d8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff81361b31)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8138d2fc)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff81391882)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:io_prep_rw
  - fs/io_uring.c:tctx_task_work
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff814260fd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/resize.c (ffffffff8143407a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8144f346)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In crypto/algapi.c (ffffffff815469ee)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
```
```
In block/blk-mq-sched.c (ffffffff8157bc50)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8158c45e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8158edcc)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In block/blk-iocost.c (ffffffff81592d0f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In lib/percpu-refcount.c (ffffffff815b52fe)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff815c2844)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff817e16c0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182a83d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff818b8fa0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff8194d3b2)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e056)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81aede03)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/reassembly.c (ffffffff81b62fb8)
Location: arch/x86/include/asm/atomic64_64.h:44
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/kthread.c (ffffffff810df972)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff810fd854)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810fe57c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810fecb7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff81106393)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff811144f3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff811196cf)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff81121321)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff8112cff2)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d524)
Location: arch/x86/include/asm/atomic64_64.h:44
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
In kernel/cgroup/pids.c (ffffffff811a1ac7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff811a64f4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff811f32aa)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff8122cbbd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/bpf/trampoline.c (ffffffff8125f491)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff8127454d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81286eb6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
```
In mm/filemap.c (ffffffff8129c402)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/vmscan.c (ffffffff812b416c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff812c4d06)
Location: arch/x86/include/asm/atomic64_64.h:44
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff812d6a29)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff812e39e7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffff812ffac0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In mm/page_alloc.c (ffffffff81300c37)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff832da75e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff8130a973)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff8131274a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8132392d)
Location: arch/x86/include/asm/atomic64_64.h:44
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff81348671)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff81350563)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8135b90e)
Location: arch/x86/include/asm/atomic64_64.h:44
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff813696d0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff813ac28a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff813daa5c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff813df78b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:__io_splice_prep
  - fs/io_uring.c:io_prep_rw
  - fs/io_uring.c:tctx_task_work
  - fs/io_uring.c:io_fallback_req_func
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81479cfa)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/resize.c (ffffffff81487ac9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814a2ec7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In crypto/algapi.c (ffffffff815a6f9e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
```
```
In block/blk-mq-sched.c (ffffffff815e102b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff815f1a8e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff815f4e2c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In block/blk-iocost.c (ffffffff815f9e5d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In lib/percpu-refcount.c (ffffffff8161b69e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8162a7b7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff8186fe31)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b62cc)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff8194ea60)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff819f27c2)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81b49246)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae1b3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/reassembly.c (ffffffff81c2aa68)
Location: arch/x86/include/asm/atomic64_64.h:44
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/kthread.c (ffffffff810f9cf0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff8111a26a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/fair.c (ffffffff811212db)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81136165)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff81144053)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
```
```
In kernel/locking/rwsem.c (ffffffff8114e2f6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd863)
Location: arch/x86/include/asm/atomic64_64.h:44
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
In kernel/cgroup/pids.c (ffffffff811d248f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff811d7987)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff8122c8ba)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff8126eedd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/bpf/trampoline.c (ffffffff812a9bd6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff812c4bbb)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff812db81e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
```
In mm/vmscan.c (ffffffff81310121)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff81322236)
Location: arch/x86/include/asm/atomic64_64.h:44
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff81336159)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff81344d73)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pmd_install
```
```
In mm/vmalloc.c (ffffffff81366b84)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff813680e8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff8348f875)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81373561)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff8137d2da)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff813914a3)
Location: arch/x86/include/asm/atomic64_64.h:44
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff813be819)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff813c8813)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff813d51b9)
Location: arch/x86/include/asm/atomic64_64.h:44
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff813e77f1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff81432349)
Location: arch/x86/include/asm/atomic64_64.h:44
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff814fbedd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/resize.c (ffffffff8150b3bc)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8152a34b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In crypto/algapi.c (ffffffff8164e0fe)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
```
```
In block/blk-mq.c (ffffffff81683a3e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-mq-sched.c (ffffffff8168fc23)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff816a4d01)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff816a6a37)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In block/blk-iocost.c (ffffffff816ac0fd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In io_uring/io_uring.c (ffffffff816cd4aa)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_buffer_account_pin
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff816fbc21)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff819b67f0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a0182f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81b5b681)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd68d0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81d412f6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff81dc7f5f)
Location: arch/x86/include/asm/atomic64_64.h:44
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff811419d2)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/fair.c (ffffffff8114a89c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81160745)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8116fd36)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
```
```
In kernel/locking/rwsem.c (ffffffff8117d276)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff81210f03)
Location: arch/x86/include/asm/atomic64_64.h:44
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff8127842a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff812c46dd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/bpf/helpers.c (ffffffff812f44f6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/trampoline.c (ffffffff81308b76)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup_iter.c (ffffffff81325542)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff8132a0a0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81343ae5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
```
In mm/vmscan.c (ffffffff8138373f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff813963a6)
Location: arch/x86/include/asm/atomic64_64.h:44
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff813ad3d9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memory.c (ffffffff813bcfa3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pmd_install
```
```
In mm/vmalloc.c (ffffffff813e2923)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff813e4138)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff83ec1f5a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff813f0cd1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff813fa75a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8140e4cc)
Location: arch/x86/include/asm/atomic64_64.h:44
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff81441097)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff8144cf03)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8145ac1a)
Location: arch/x86/include/asm/atomic64_64.h:44
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff8146f40c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff814c2da1)
Location: arch/x86/include/asm/atomic64_64.h:44
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
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81596643)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/resize.c (ffffffff815a603d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff815c8ceb)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In crypto/algapi.c (ffffffff8170757e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
```
```
In block/blk-mq.c (ffffffff817413be)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-mq-sched.c (ffffffff8174e7e4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81763c2d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81765950)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff8176ab2d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In io_uring/io_uring.c (ffffffff8178df41)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:handle_tw_list
  - io_uring/io_uring.c:__io_alloc_req_refill
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In io_uring/uring_cmd.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In io_uring/net.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In io_uring/rsrc.c (ffffffff817a0ab2)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_rsrc_refs_refill
```
```
In io_uring/rw.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff817d8f78)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff817ee8c1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/pci/p2pdma.c (ffffffff8191bf4f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81b2ba00)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7fe7f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81cf5051)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
```
```
In net/core/sock.c (ffffffff81d9e383)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/ip_fragment.c (ffffffff81e96e77)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ec9b0b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a0a6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f1ec29)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv6/reassembly.c (ffffffff81f98cd1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81faca62)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
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
In kernel/kthread.c (ffffffff81129bc0)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
```
```
In kernel/sched/core.c (ffffffff8114d685)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/fair.c (ffffffff8115c61c)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81170e6b)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8117e6c6)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
```
```
In kernel/locking/rwsem.c (ffffffff8118df26)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff812268f3)
Location: arch/x86/include/asm/atomic64_64.h:23
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
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff8128fe6a)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff812eb6dd)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/bpf/trampoline.c (ffffffff81337a96)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8135577d)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff8135a1e0)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81374b6b)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
```
In mm/vmscan.c (ffffffff813b514d)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff813c91f6)
Location: arch/x86/include/asm/atomic64_64.h:23
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
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff813e17c9)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memory.c (ffffffff813f1ce6)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pmd_install
```
```
In mm/vmalloc.c (ffffffff814174f0)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff81418e88)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff836e75a3)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81424811)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff8142d69a)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/zswap.c (ffffffff8143681d)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff814418ab)
Location: arch/x86/include/asm/atomic64_64.h:23
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
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff81476959)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff814827c3)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8149087a)
Location: arch/x86/include/asm/atomic64_64.h:23
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
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff814a3bd6)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff814f63bb)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:wb_io_lists_populated
```
```
In fs/aio.c (ffffffff8152c248)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff815cd085)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/resize.c (ffffffff815dc8ad)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81600aac)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81733149)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/aead.c (ffffffff81741ea7)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/geniv.c (ffffffff817421ae)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff81742ff7)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/ahash.c (ffffffff81745152)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
```
```
In crypto/shash.c (ffffffff8174680a)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_update
```
```
In crypto/akcipher.c (ffffffff81747853)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
```
```
In crypto/dh.c (ffffffff81748b40)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a807)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/gcm.c (ffffffff817530a3)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In crypto/drbg.c (ffffffff817593c7)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
```
```
In block/blk-mq.c (ffffffff817831ac)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-cgroup.c (ffffffff817a2b51)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff817a4a10)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff817a9c0d)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In io_uring/io_uring.c (ffffffff817c90fa)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_activate_pollwq
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:__io_alloc_req_refill
```
```
In io_uring/rsrc.c (ffffffff817e1d03)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff81811c2b)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In lib/percpu-refcount.c (ffffffff81818188)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8182ec7b)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/pci/p2pdma.c (ffffffff8195f562)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81b7bd00)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd3ed2)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81d5e8d9)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - drivers/md/md.c:md_account_bio
  - drivers/md/md.c:md_write_start
```
```
In net/core/sock.c (ffffffff81e0cbff)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef56b4)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp.c (ffffffff81f0ae7d)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81f2865a)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c120)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69bc2)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f7e729)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv6/reassembly.c (ffffffff81ff96ab)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffaddc)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200d472)
Location: arch/x86/include/asm/atomic64_64.h:23
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
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/kthread.c (ffffffff81134200)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
```
```
In kernel/cred.c (ffffffff8113e566)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/sched/core.c (ffffffff8115943b)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/fair.c (ffffffff8116679a)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/sched/fair.c:switched_from_fair
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr_common
```
```
In kernel/sched/build_policy.c (ffffffff81181db7)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
```
In kernel/sched/build_utility.c (ffffffff81196768)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
```
```
In kernel/locking/rwsem.c (ffffffff8119c8d6)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811e32bc)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_enqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e583)
Location: arch/x86/include/asm/atomic64_64.h:23
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
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff812ab42a)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff81309c2d)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/trampoline.c (ffffffff8135d8d6)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/memalloc.c (ffffffff81372fd0)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8137e0fd)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff81382d90)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8139de9b)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
```
In kernel/watch_queue.c (ffffffff813b2bde)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/shrinker.c (ffffffff813e4c41)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/shrinker.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff813f3b86)
Location: arch/x86/include/asm/atomic64_64.h:23
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
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/percpu.c (ffffffff813fa1ad)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
```
```
In mm/workingset.c (ffffffff8140bf09)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memory.c (ffffffff8141c9d6)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pmd_install
```
```
In mm/vmalloc.c (ffffffff81444000)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff814459d8)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff83919da3)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81451641)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/slub.c (ffffffff814578c0)
Location: arch/x86/include/asm/atomic64_64.h:23
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
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/zswap.c (ffffffff81470b50)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_load
```
```
In mm/hugetlb.c (ffffffff8147bb32)
Location: arch/x86/include/asm/atomic64_64.h:23
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
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff814b1b43)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff814c0157)
Location: arch/x86/include/asm/atomic64_64.h:23
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
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
```
```
In mm/zsmalloc.c (ffffffff814ccf68)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff814d4a76)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/file_table.c (ffffffff814e26a3)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - fs/file_table.c:init_file
```
```
In fs/fs-writeback.c (ffffffff8152aafb)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:wb_io_lists_populated
```
```
In fs/fs_context.c (ffffffff81538fd9)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/aio.c (ffffffff81561128)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81601763)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/resize.c (ffffffff8161518d)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff816397fc)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In security/keys/process_keys.c (ffffffff816cad23)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff816cbeb9)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff816cce92)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/audit.c (ffffffff81737344)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/domain.c (ffffffff8174198d)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
```
```
In crypto/aead.c (ffffffff81782d87)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/geniv.c (ffffffff8178308e)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/lskcipher.c (ffffffff81783da2)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/lskcipher.c:crypto_lskcipher_decrypt
  - crypto/lskcipher.c:crypto_lskcipher_encrypt
```
```
In crypto/skcipher.c (ffffffff81785347)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/ahash.c (ffffffff81787e7b)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_update
```
```
In crypto/shash.c (ffffffff817889b6)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_update
```
```
In crypto/akcipher.c (ffffffff817896c3)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
```
```
In crypto/dh.c (ffffffff8178a9e0)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c3c7)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/drbg.c (ffffffff8179b2c7)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
```
```
In block/blk-mq.c (ffffffff817c6cd9)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-cgroup.c (ffffffff817e6691)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff817e85e0)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff817ed9cd)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In io_uring/io_uring.c (ffffffff81816efe)
Location: arch/x86/include/asm/atomic64_64.h:23
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
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In io_uring/rsrc.c (ffffffff818260ac)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In io_uring/register.c (ffffffff8182bb9e)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
```
```
In lib/percpu-refcount.c (ffffffff8185d488)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8188083b)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/pci/p2pdma.c (ffffffff819a8bbf)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81bcfd2f)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c28b4c)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb42ed)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:store_vblank
```
```
In drivers/usb/core/devio.c (ffffffff81d4d3db)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/md/md.c (ffffffff81e15a9d)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - drivers/md/md.c:md_account_bio
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_flush_request
```
```
In net/core/sock.c (ffffffff81ec957f)
Location: arch/x86/include/asm/atomic64_64.h:23
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
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81fed0ea)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/inet_fragment.c (ffffffff82030242)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff82044dd4)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/unix/af_unix.c (ffffffff8207c0e6)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/reassembly.c (ffffffff820c731b)
Location: arch/x86/include/asm/atomic64_64.h:23
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dc43c)
Location: arch/x86/include/asm/atomic64_64.h:23
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
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void arch_atomic64_add(long int i, atomic64_t *v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In virt/kvm/arm/arm.c (ffff8000100c71a0)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
```
```
In kernel/fork.c (ffff8000100f472c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffff800010115128)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kthread.c (ffff800010128924)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
```
```
In kernel/sched/core.c (ffff80001013d93c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffff80001013ec34)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/cputime.c (ffff80001013ef44)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffff800010145e28)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffff8000101504c0)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffff800010155708)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffff80001015e030)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffff800010169db4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/kcmp.c (ffff800010197b00)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/cgroup/cgroup.c (ffff8000101d28f4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/pids.c (ffff8000101deea4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffff8000101e344c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/audit_tree.c (ffff8000101f5640)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/ring_buffer.c (ffff800010219010)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/trace/tracing_map.c (ffff80001022ec00)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffff8000102657d4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (ffff80001028f170)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffff80001029eb44)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:perf_swevent_event
Direct callers:
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/ring_buffer.c (ffff8000102a2838)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In kernel/events/uprobes.c (ffff8000102a57d4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffff8000102b2910)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffff8000102b7838)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffff8000102ccb44)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffff8000102d3218)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/vmstat.c (ffff8000102dc9b4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_diff
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
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
```
```
In mm/backing-dev.c (ffff8000102df8e4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffff8000102e78a4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/workingset.c (ffff8000102f04c0)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffff8000102f0660)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffff8000102f9a34)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:fault_dirty_shared_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc
  - mm/memory.c:sync_mm_rss
```
```
In mm/mmap.c (ffff8000103040a4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffff800010306f5c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/msync.c:__arm64_sys_msync
```
```
In mm/rmap.c (ffff80001030a288)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffff8000103100b4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
```
```
In mm/page_alloc.c (ffff80001031396c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffff80001031d6a8)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Direct callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffff80001031e188)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffff8000103260e4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffff8000103337cc)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffff80001034b638)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
Direct callers:
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffff80001034de98)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/migrate.c (ffff8000103518b4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffff800010355dac)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035fc2c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/page_counter.c (ffff800010360a20)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffff800010365d3c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_get_oom_group
```
```
In mm/memory-failure.c (ffff8000103705b0)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffff80001037591c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/userfaultfd.c (ffff8000103781b0)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/exec.c (ffff80001038c64c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
```
```
In fs/select.c (ffff8000103a1e50)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffff8000103ac6ec)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
```
```
In fs/file.c (ffff8000103b29f4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/fs-writeback.c (ffff8000103ca390)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/notify/mark.c (ffff8000103e9494)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffff8000103f1b30)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
```
```
In fs/aio.c (ffff8000103fdf20)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffff800010403c48)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
```
```
In fs/proc/fd.c (ffff800010446fa0)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffff800010496e94)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffff8000104a8058)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffff8000104c0520)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/shm.c (ffff8000105286fc)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffff8000105adcec)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
```
```
In security/integrity/ima/ima_api.c (ffff8000105b0824)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffff8000105ba98c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-core.c (ffff8000105e4384)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-ioc.c (ffff8000105e87fc)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
```
```
In block/blk-mq.c (ffff8000105efb14)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffff8000105f7208)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/genhd.c (ffff8000105faafc)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - block/genhd.c:part_inc_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/blk-cgroup.c (ffff80001060eb7c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffff800010610658)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffff800010615984)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
```
```
In lib/percpu-refcount.c (ffff8000106356dc)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffff8000106449fc)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/tty/tty_io.c (ffff800010852574)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffff8000108cd0e4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffff800010924f74)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffff8000109656dc)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/scsi/scsi_lib.c (ffff80001097834c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffff800010a2c318)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffff800010aeaa3c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
```
```
In drivers/md/md-bitmap.c (ffff800010afad08)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/perf/arm-cci.c (ffff800010b912e0)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_event_update
```
```
In drivers/perf/arm-ccn.c (ffff800010b930e0)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update
```
```
In drivers/perf/arm_pmu.c (ffff800010b95008)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b9662c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_event_update
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98e88)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_update
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a6c8)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_update
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c0cc)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_perf_event_update
```
```
In net/core/scm.c (ffff800010bbde7c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffff800010bd2468)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffff800010c01534)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffff800010c30c50)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffff800010c35f28)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f89c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffff800010ca4fc0)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/inet_fragment.c (ffff800010cbefc4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/xfrm/xfrm_device.c (ffff800010cee690)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffff800010cf0d58)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffff800010cf47b4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffff800010cfc76c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffff800010d20b1c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d26b50)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffff800010d2cb40)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffff800010d3012c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (ffff800010d355c4)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39d8c)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffff800010d3a594)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffff800010d581d0)
Location: arch/arm64/include/asm/atomic.h:67
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffff8000102950a8-ffff8000102950c0: arch_atomic64_add (STB_LOCAL)
ffff80001031d6a8-ffff80001031d6cc: arch_atomic64_add.constprop.0 (STB_LOCAL)
ffff800010344a30-ffff800010344a48: arch_atomic64_add (STB_LOCAL)
ffff800010364898-ffff8000103648b0: arch_atomic64_add (STB_LOCAL)
```
</details>
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/kthread.c (ffffffff810c3366)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d8107)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810d92c9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/cputime.c (ffffffff810d9816)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810e182f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e8c28)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810ec8fc)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f2a7f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff810fd815)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8115f4ee)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/pids.c (ffffffff81163319)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff81168b8d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff811a91fa)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/cgroup.c (ffffffff811fe4b4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8120f20e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff8124066c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_diff
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
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
```
```
In mm/backing-dev.c (ffffffff81242745)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81248e28)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff8125adfd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (ffffffff81271c03)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In mm/page_alloc.c (ffffffff81273ac8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828c8b58)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8127cf76)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff81282eaa)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8128eec4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff812a214d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812a3fe3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812acda4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b65c6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812b74a5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812c06f2)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In mm/zsmalloc.c (ffffffff812c954d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812cd191)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812ddaa6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130cb3e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81336da3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b8801)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813c7c1b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813e0135)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (ffffffff814b8f9f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-core.c (ffffffff814df0df)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814e7cd3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814ef0e6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81503777)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff815049ad)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff81507f0f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
```
```
In lib/percpu-refcount.c (ffffffff81522918)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8152fced)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff816f2227)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff817289a4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff817b2b00)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff8183b3b5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8194eb31)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5dc3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a0c500)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/kthread.c (ffffffff810b1ba6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c6b11)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810c7cc9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/cputime.c (ffffffff810c81f6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810d090f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810d865f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810dc99c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e2b8f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff810eda09)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81116700)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_enqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8115277e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/pids.c (ffffffff81156569)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8115bd9d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff8119c17a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/cgroup.c (ffffffff811f1204)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81201fb8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff8123366c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_diff
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
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
```
```
In mm/backing-dev.c (ffffffff81235715)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff8123bdd2)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff8124d184)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (ffffffff81263b73)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In mm/page_alloc.c (ffffffff81265a38)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828c127d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8126eca0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812749ca)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff81280ade)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff81293c2d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff81295ab3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff8129de6d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a779c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/page_counter.c (ffffffff812a8675)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812b17ac)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In mm/zsmalloc.c (ffffffff812ba58d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812be001)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812ce726)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fd75e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81327719)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a9291)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813b869b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813d0bb5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (ffffffff814a99bf)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-core.c (ffffffff814cfa7f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814d8243)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814df626)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f3c37)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814f4e6d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff814f83bf)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
```
```
In lib/percpu-refcount.c (ffffffff81512bf8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8151ffcd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff816cc327)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81701dd4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff817a4530)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff81802a25)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81908621)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f883)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff819c92c0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/kthread.c (ffffffff810c28b6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d48f7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810d5609)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/cputime.c (ffffffff810d5b56)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810ddbaf)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e57cf)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e9a2c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810efbaf)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff810fa9d5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8115d2be)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/pids.c (ffffffff811610e9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8116695d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff811a6fca)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/cgroup.c (ffffffff811fc284)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8120cfae)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff8123e40c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_diff
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
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
```
```
In mm/backing-dev.c (ffffffff812404e5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81246bc8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff81258b9d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (ffffffff8126f9a3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In mm/page_alloc.c (ffffffff81271868)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828db8d8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8127ad16)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff81280cba)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8128ccd4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8129ff5d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812a1df3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812aabb4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b43d6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812b52b5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812be502)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In mm/zsmalloc.c (ffffffff812c735d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812cafa1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812db8b6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130a92e)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81334873)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b6061)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813c50ab)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813dd4ae)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (ffffffff814b502f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-core.c (ffffffff814db16f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814e3d63)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814eb176)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814ff807)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81500a3d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff81503f9f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
```
```
In lib/percpu-refcount.c (ffffffff8151e9a8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8152ba2d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff8171f907)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767774)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff817ef5a0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff8188a9e5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199ddc8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_ct_kill_acct
  - net/netfilter/nf_conntrack_core.c:__nf_ct_refresh_acct
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9301)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10663)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a76f80)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a90b37)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/kthread.c (ffffffff810caee7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff810dfcf1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810e0eb9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/cputime.c (ffffffff810e1456)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810e968f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810efae8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f49dc)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810fabff)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff81105b97)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a490)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/pids.c (ffffffff8116e539)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff81173fee)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff811b4d6a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/cgroup.c (ffffffff8120aede)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8121be95)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff8124db3c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:__inc_numa_state
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:fold_diff
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
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_node_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_node_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_node_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
```
```
In mm/backing-dev.c (ffffffff8124fc12)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff812563fb)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff8126859d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (ffffffff8127f399)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In mm/page_alloc.c (ffffffff812812c8)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828e0cf9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8128a8f5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812908e6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8129caa2)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff812b009d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812b1fb3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812baf04)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c48a2)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812c57f5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812cef0b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In mm/zsmalloc.c (ffffffff812d6c1d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812dbcf6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812ec869)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131c057)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81346d46)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813cadee)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813da3f4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813f28ce)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (ffffffff814cdaaf)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-core.c (ffffffff814f3f84)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814fd2c7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff81504188)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff815189d7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff815199b1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff8151d54f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
```
```
In lib/percpu-refcount.c (ffffffff81538258)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff815457be)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff8173ad5c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81782eb1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff818097e0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff818a8da3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2bf1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1aeb3)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a835a0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
