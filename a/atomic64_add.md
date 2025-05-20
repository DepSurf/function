# Function: <code>atomic64_add</code>

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
In arch/x86/events/intel/cqm.c (ffffffff8100d743)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__intel_cqm_event_count
  - arch/x86/events/intel/cqm.c:__intel_mbm_event_count
```
```
In kernel/sched/core.c (ffffffff810ac444)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_call
```
```
In kernel/sched/loadavg.c (ffffffff810b0dda)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_load_enter_idle
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load_tick
```
```
In kernel/sched/cputime.c (ffffffff810b174c)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_user_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
```
```
In kernel/sched/fair.c (ffffffff810b4b3f)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:remove_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810bfb05)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c2216)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810c3173)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup.c (ffffffff81114620)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup_pids.c (ffffffff8111a559)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_can_attach
  - kernel/cgroup_pids.c:pids_cancel_attach
```
```
In kernel/cpuset.c (ffffffff8111c897)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/core.c (ffffffff811724c0)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In kernel/bpf/syscall.c (ffffffff811730f3)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811812bc)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
```
```
In mm/vmstat.c (ffffffff811ac534)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:__mod_zone_page_state
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:mod_zone_page_state
  - mm/vmstat.c:mod_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__inc_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:__dec_zone_state
  - mm/vmstat.c:inc_zone_state
  - mm/vmstat.c:inc_zone_state
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
```
```
In mm/backing-dev.c (ffffffff81208cc9)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In mm/memory.c (ffffffff811bbc49)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memory.c:sync_mm_rss
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/swapfile.c (ffffffff811d30c4)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/hugetlb.c (ffffffff811de9d8)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/slub.c (ffffffff811e99f2)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:kmem_cache_open
```
```
In mm/huge_memory.c (ffffffff811f5666)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memcontrol.c (ffffffff811fb3f7)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:__memcg_kmem_get_cache
```
```
In mm/memory-failure.c (ffffffff812024f7)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/zsmalloc.c (ffffffff81205bc4)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff81212fd8)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In fs/pipe.c (ffffffff81215618)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_fcntl
```
```
In fs/fs-writeback.c (ffffffff81236221)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/aio.c (ffffffff8125b992)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:do_io_submit
```
```
In fs/ext4/super.c (ffffffff812be4d9)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff812c0c7b)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/mballoc.c (ffffffff812d4cd3)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
```
```
In block/bio.c (ffffffff813b10e1)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkcg
```
```
In block/blk-core.c (ffffffff813baab3)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff813c4ce0)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
```
```
In block/blk-cgroup.c (ffffffff813d738f)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_add_aux
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
```
```
In block/cfq-iosched.c (ffffffff813de1ef)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/cfq-iosched.c:blkg_rwstat_add_aux
  - block/cfq-iosched.c:cfq_pd_offline
```
```
In lib/percpu-refcount.c (ffffffff813ff018)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/percpu-refcount.c:percpu_ref_reinit
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
In arch/x86/events/intel/cqm.c (ffffffff8100d978)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__intel_mbm_event_count
  - arch/x86/events/intel/cqm.c:__intel_cqm_event_count
```
```
In arch/x86/mm/gup.c (ffffffff8107171c)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/sched/core.c (ffffffff810b2d9d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810b3c0e)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_enter_idle
```
```
In kernel/sched/cputime.c (ffffffff810b427f)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810b9d09)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff810c3434)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c5bee)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810c6aef)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8189dd2e)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
```
```
In kernel/cgroup.c (ffffffff8111bfce)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup_pids.c (ffffffff811224a9)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_cancel_attach
  - kernel/cgroup_pids.c:pids_can_attach
```
```
In kernel/cpuset.c (ffffffff81124797)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/tracing_map.c (ffffffff81160a78)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/core.c (ffffffff811802c3)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In kernel/bpf/syscall.c (ffffffff81181ab7)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8119673d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
```
```
In kernel/memremap.c (ffffffff8119e2ff)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/memremap.c:get_zone_device_page
```
```
In mm/vmstat.c (ffffffff811c707d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
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
In mm/backing-dev.c (ffffffff8122e9b8)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In mm/memory.c (ffffffff811da332)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff811eedad)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff811f0f6a)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/hugetlb.c (ffffffff811fd7b7)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8120d0c7)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff8121601b)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121a5db)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81224241)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In mm/memory-failure.c (ffffffff81227b93)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff8122b1f8)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff8123a240)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In fs/pipe.c (ffffffff8123d070)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/fs-writeback.c (ffffffff81261b4b)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8128644d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:lookup_ioctx
```
```
In fs/ext4/super.c (ffffffff812edbb7)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff812f056b)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/mballoc.c (ffffffff813052a8)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In block/bio.c (ffffffff813f4ab1)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In block/blk-core.c (ffffffff813fe845)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff81408ebb)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
```
```
In block/blk-cgroup.c (ffffffff8141df4d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_add_aux
```
```
In block/cfq-iosched.c (ffffffff81428eb6)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_add_aux
```
```
In lib/percpu-refcount.c (ffffffff81446ad0)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:__percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
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
In arch/x86/events/intel/cqm.c (ffffffff8100da38)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__intel_mbm_event_count
  - arch/x86/events/intel/cqm.c:__intel_cqm_event_count
```
```
In arch/x86/mm/gup.c (ffffffff8107529a)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/sched/core.c (ffffffff810b937a)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810ba24e)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_enter_idle
```
```
In kernel/sched/cputime.c (ffffffff810ba8a7)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810c0a63)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810c94a4)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cbbae)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810ccacf)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem-xadd.c (ffffffff818d2ba6)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
```
```
In kernel/cgroup.c (ffffffff8112430e)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup_pids.c (ffffffff8112aac9)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/cgroup_pids.c:pids_cancel_attach
  - kernel/cgroup_pids.c:pids_can_attach
```
```
In kernel/cpuset.c (ffffffff8112dbf2)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/tracing_map.c (ffffffff8116b4d8)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/core.c (ffffffff8118c133)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In kernel/bpf/syscall.c (ffffffff8118dcde)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811a61bd)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
```
```
In kernel/memremap.c (ffffffff811add2f)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/memremap.c:get_zone_device_page
```
```
In mm/vmstat.c (ffffffff811d719d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
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
In mm/backing-dev.c (ffffffff81240f07)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In mm/memory.c (ffffffff811e9e5a)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff811ff6dc)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812018da)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/hugetlb.c (ffffffff8120e27a)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8121f127)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff812285e3)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122e9e2)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812367c1)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In mm/memory-failure.c (ffffffff8123a120)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff8123d765)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff8124cf97)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8127504b)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff812998ae)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:lookup_ioctx
```
```
In fs/ext4/super.c (ffffffff81303b53)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff8130653b)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/mballoc.c (ffffffff8131b278)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In block/bio.c (ffffffff8140e4a1)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In block/blk-core.c (ffffffff81418231)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff81422289)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
```
```
In block/blk-cgroup.c (ffffffff8143950d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_add_aux
```
```
In block/cfq-iosched.c (ffffffff81440eb6)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_add_aux
```
```
In lib/percpu-refcount.c (ffffffff814651a0)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
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
In kernel/sched/core.c (ffffffff810b3e26)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810b4a9c)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810b516a)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810c253b)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810c4737)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c7e75)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810cd98f)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8190996a)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
```
```
In kernel/cgroup/cgroup.c (ffffffff81128b5b)
Location: arch/x86/include/asm/atomic64_64.h:43
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
In kernel/cgroup/pids.c (ffffffff8112b7c9)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8112f249)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/tracing_map.c (ffffffff8116e70d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/core.c (ffffffff81190017)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/bpf/core.c:___bpf_prog_run
```
```
In kernel/bpf/syscall.c (ffffffff81192ac3)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811ad994)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
```
```
In kernel/memremap.c (ffffffff811b5025)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/vmstat.c (ffffffff811e0001)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
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
In mm/backing-dev.c (ffffffff811e1d7d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff811e77f9)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/gup.c (ffffffff811f0fd3)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__gup_device_huge
```
```
In mm/memory.c (ffffffff811f4f53)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff8120a4d1)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8120cb69)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff81217873)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8122b906)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff81231d1e)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81238674)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81242289)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In mm/zsmalloc.c (ffffffff812490ce)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff81258f39)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812825b4)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff812a7745)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/ext4/mballoc.c (ffffffff8131265a)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff81320ee7)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff81338281)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In block/bio.c (ffffffff8141b21f)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In block/blk-core.c (ffffffff814260b8)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff8142f3ff)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-cgroup.c (ffffffff81446c9a)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_add_aux
```
```
In block/cfq-iosched.c (ffffffff81450194)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_add_aux
```
```
In lib/percpu-refcount.c (ffffffff8146a2bd)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/usb/core/devio.c (ffffffff816bc833)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff8173aa05)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/kthread.c (ffffffff810ac973)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff810bb0d1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810bbd6c)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810bc2f2)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810c9ba6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810cbe0b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cf5c1)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810d51dc)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819939c6)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
```
```
In kernel/cgroup/cgroup.c (ffffffff8113518d)
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
In kernel/cgroup/pids.c (ffffffff811385c9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8113c0f5)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/tracing_map.c (ffffffff8117b815)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff811a0d81)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811c14f9)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
```
```
In kernel/memremap.c (ffffffff811c9231)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/vmstat.c (ffffffff811f5ef4)
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
In mm/backing-dev.c (ffffffff811f7de4)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff811fda3b)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/gup.c (ffffffff81205c28)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
```
```
In mm/memory.c (ffffffff8120e445)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff81223751)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff81226a36)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff81234400)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8124701a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff8125298e)
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
In mm/khugepaged.c (ffffffff81259b41)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8126207f)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In mm/zsmalloc.c (ffffffff81269309)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff8127b0cd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a512a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff812caadb)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/ext4/mballoc.c (ffffffff81336e2a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff8134561d)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8135c761)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In block/bio.c (ffffffff81445e57)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
```
```
In block/blk-core.c (ffffffff814514fd)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-mq.c (ffffffff8145a951)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-cgroup.c (ffffffff8147387a)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_add_aux
```
```
In block/cfq-iosched.c (ffffffff8147eb54)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:blkg_rwstat_add_aux
```
```
In lib/percpu-refcount.c (ffffffff814965ad)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff814a0432)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free
```
```
In drivers/block/loop.c (ffffffff8166fcdb)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/usb/core/devio.c (ffffffff81728203)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff817ad0e7)
Location: arch/x86/include/asm/atomic64_64.h:44
Inline: True
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
```
```
In kernel/fork.c (ffffffff8108b067)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/kthread.c (ffffffff810b398a)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c26de)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810c3436)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810c39c6)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810d1fb8)
Location: include/asm-generic/atomic-instrumented.h:130
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
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810d712a)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810dd1b0)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819eff73)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
```
```
In kernel/cgroup/cgroup.c (ffffffff811438b4)
Location: include/asm-generic/atomic-instrumented.h:130
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
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8114ad1f)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/tracing_map.c (ffffffff8118989b)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff811b5376)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/core.c (ffffffff811e1813)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
```
```
In kernel/memremap.c (ffffffff811e9b5c)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/filemap.c (ffffffff811f003d)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/page-writeback.c (ffffffff811fea1a)
Location: include/asm-generic/atomic-instrumented.h:130
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
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
```
```
In mm/vmscan.c (ffffffff8120aac8)
Location: include/asm-generic/atomic-instrumented.h:130
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
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/vmstat.c (ffffffff8121716c)
Location: include/asm-generic/atomic-instrumented.h:130
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
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff8121ed78)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/workingset.c (ffffffff812257dd)
Location: include/asm-generic/atomic-instrumented.h:130
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
Location: include/asm-generic/atomic-instrumented.h:130
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
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff81246558)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812492c6)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff81257373)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8126834e)
Location: include/asm-generic/atomic-instrumented.h:130
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
Location: include/asm-generic/atomic-instrumented.h:130
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
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/page_counter.c (ffffffff8127e2b5)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff81286739)
Location: include/asm-generic/atomic-instrumented.h:130
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
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff812a1eb4)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812cc00b)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff812f48cf)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (ffffffff812f9dd6)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8136541c)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813736cd)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8138b18b)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In block/bio.c (ffffffff81479acd)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
```
```
In block/blk-core.c (ffffffff81484722)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-mq.c (ffffffff8148ef0f)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-cgroup.c (ffffffff814a789b)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/cfq-iosched.c (ffffffff814b2b52)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_pd_offline
```
```
In lib/percpu-refcount.c (ffffffff814cb80d)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff814d55cb)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free
```
```
In drivers/block/loop.c (ffffffff816ab9cb)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/usb/core/devio.c (ffffffff81767050)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff817f5526)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff818e96ee)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff81939413)
Location: include/asm-generic/atomic-instrumented.h:130
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81990ab5)
Location: include/asm-generic/atomic-instrumented.h:130
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
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
```
```
In kernel/fork.c (ffffffff8109370d)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/kthread.c (ffffffff810bcc8a)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
```
```
In kernel/sched/core.c (ffffffff810cb9d2)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810cc6e6)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810ccc86)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810db91c)
Location: include/asm-generic/atomic-instrumented.h:147
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
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e1676)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e6e10)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b990)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f3cd)
Location: include/asm-generic/atomic-instrumented.h:147
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
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff81156de1)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/tracing_map.c (ffffffff8119714b)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/events/core.c (ffffffff811f1c83)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
```
```
In kernel/memremap.c (ffffffff811fa6cb)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/filemap.c (ffffffff812023c9)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/page_alloc.c (ffffffff812066b8)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:memblock_free_pages
```
```
In mm/page-writeback.c (ffffffff8120f1fa)
Location: include/asm-generic/atomic-instrumented.h:147
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
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
```
```
In mm/vmscan.c (ffffffff8121d7c8)
Location: include/asm-generic/atomic-instrumented.h:147
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
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/vmstat.c (ffffffff8122a07c)
Location: include/asm-generic/atomic-instrumented.h:147
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
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81231d58)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/workingset.c (ffffffff81238d3f)
Location: include/asm-generic/atomic-instrumented.h:147
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
Location: include/asm-generic/atomic-instrumented.h:147
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
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/memblock.c (ffffffff828be664)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8125a97b)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8125db93)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8126b9e5)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8127de5a)
Location: include/asm-generic/atomic-instrumented.h:147
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
Location: include/asm-generic/atomic-instrumented.h:147
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
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/page_counter.c (ffffffff812929a5)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8129b6a9)
Location: include/asm-generic/atomic-instrumented.h:147
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
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff812b6c63)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812e0f24)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81309786)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (ffffffff8130dc34)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8137d7dc)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff8138bac2)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813a33ff)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (ffffffff8147819e)
Location: include/asm-generic/atomic-instrumented.h:147
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
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:generic_make_request
```
```
In block/blk-mq.c (ffffffff814a89a5)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-cgroup.c (ffffffff814c34b7)
Location: include/asm-generic/atomic-instrumented.h:147
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
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff814e0543)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff814ea02b)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free
```
```
In drivers/block/loop.c (ffffffff816cc76c)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81714787)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff8178b5d0)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff81821406)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819164c6)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff81969000)
Location: include/asm-generic/atomic-instrumented.h:147
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff819c71f3)
Location: include/asm-generic/atomic-instrumented.h:147
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In kernel/kthread.c (ffffffff810c2a76)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d3a44)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810d4b19)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810d5067)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810dd24f)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e3869)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e812d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810edaa0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff810f86bd)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8116471e)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/tracing_map.c (ffffffff811a53aa)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/cgroup.c (ffffffff811f8ccb)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8120984e)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81242348)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff8125424d)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126c668)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828d7833)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff81275956)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8127adea)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff81286ce4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff81299cad)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff8129bc02)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812a32c4)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In mm/page_counter.c (ffffffff812ad375)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812b62b0)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812c2d59)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In fs/exec.c (ffffffff812d3936)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812ff646)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8132b973)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a7391)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813b671b)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813ce0a2)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (ffffffff814a606f)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814d637c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814dd676)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f1bb7)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814f2e2d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff8150c4e8)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff81516ccd)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff817081f7)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff817500c4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff817c9be0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff818637e5)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81978351)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf49f)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a36350)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In kernel/kthread.c (ffffffff810c8fe6)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ddf17)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810df0d9)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/cputime.c (ffffffff810df626)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810e767f)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810ef29f)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f34fc)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f967f)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff81104505)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8117056d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff811b0bda)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/cgroup.c (ffffffff81205e94)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81216bbe)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff812507d8)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff812627ad)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127b478)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828dfca4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff81284926)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8128a8ca)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff812968e4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff812a9b6d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812aba03)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812b47c4)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812beec5)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812c8112)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812d4bb1)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812e54c6)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131455e)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8133e7c3)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813c0221)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813cf63b)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813e7b55)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (ffffffff814c09bf)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814ef6f3)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814f6b06)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8150b197)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8150c3cd)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff8150f92f)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8153770d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff8172c447)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff817742b4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff817fa720)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff81895535)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819aecc1)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06023)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a6ce70)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
```
```
In kernel/kthread.c (ffffffff810d09d9)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
```
```
In kernel/sched/core.c (ffffffff810e64e1)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810e73b9)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810e7976)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810ed96d)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f8c98)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fcbe7)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff8110378f)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff8110efb0)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff811818b4)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
```
In kernel/trace/tracing_map.c (ffffffff811c939a)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff811fb3dd)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/bpf/cgroup.c (ffffffff8122d5ee)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81240c39)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/slab_common.c (ffffffff8127ee38)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/workingset.c (ffffffff812869e9)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff812926ad)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffff812ac403)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff812ad618)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff82cfd116)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/swapfile.c (ffffffff812bad9c)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff812c9e34)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812e0373)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812eaf1a)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff812f41a0)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812fd968)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff8130a6fb)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/fs-writeback.c (ffffffff8134e073)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8137849f)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff81380855)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:__io_async_wake
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8140c351)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff814192fc)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81430c02)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In crypto/algapi.c (ffffffff815211e3)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8156c101)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8156da57)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In block/blk-iocost.c (ffffffff81570a2f)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8159bfa0)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff817e7c07)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81836c1c)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff818ca940)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff819629d5)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
```
```
In drivers/md/dm.c (ffffffff81979a90)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
```
```
In net/ipv4/ip_fragment.c (ffffffff81a990d6)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5736)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81b65de9)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
```
```
In kernel/kthread.c (ffffffff810cb5c7)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
```
```
In kernel/sched/core.c (ffffffff810e43ac)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810e4ff9)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810e5666)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810eb79d)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f6eab)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fb0f7)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff81101eaf)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff8110c2a9)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff811753df)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e7c2)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
```
In kernel/trace/tracing_map.c (ffffffff811c6a5a)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff811fa53d)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/bpf/trampoline.c (ffffffff81222b51)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff81235b2a)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8124b1ea)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff81290c39)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff8129cf94)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffff812b798d)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff812b9019)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff82fe9b47)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/swapfile.c (ffffffff812c681c)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff812d5a71)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memory_hotplug.c (ffffffff812eb2f3)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812f8581)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff812ffa90)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff81309d92)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff8131615c)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff8135af31)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff813861ac)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff8138b041)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8141f823)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff8142d3b5)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814499c6)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In crypto/algapi.c (ffffffff8153e233)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81585a8e)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81587f7c)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In block/blk-iocost.c (ffffffff8158be5f)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff815b79d1)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff817fcaf0)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff8184767d)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff818d5a50)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff81969422)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa3046)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81b024f6)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81b74559)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
```
```
In kernel/kthread.c (ffffffff810ccf04)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
```
```
In kernel/sched/core.c (ffffffff810e636b)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810e6fa9)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffff810e7626)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810ed686)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f8ffb)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fd2ff)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff8110421f)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff8110e0ee)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff81175f4e)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e7d4)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff811c7a4a)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff811fb47d)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/bpf/trampoline.c (ffffffff81227391)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff81239d7a)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8124d2a6)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/vmscan.c (ffffffff8127695c)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff81285b94)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff81296299)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff812a2677)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffff812bd3a0)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
```
```
In mm/page_alloc.c (ffffffff812be4e9)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff831f433d)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff812c5f73)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff812cd3bc)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff812dc775)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff812fea74)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff81306733)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff813105fe)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff8131c3d8)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff81361b31)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8138d2fc)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff81391882)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:io_prep_rw
  - fs/io_uring.c:tctx_task_work
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff814260fd)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/resize.c (ffffffff8143407a)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8144f346)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In crypto/algapi.c (ffffffff815469ee)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8158c45e)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8158edcc)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In block/blk-iocost.c (ffffffff81592d0f)
Location: include/asm-generic/atomic-instrumented.h:871
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
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff815c2844)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff817e16c0)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182a83d)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff818b8fa0)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff8194d3b2)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e056)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81aede03)
Location: include/asm-generic/atomic-instrumented.h:871
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/reassembly.c (ffffffff81b62fb8)
Location: include/asm-generic/atomic-instrumented.h:871
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
In kernel/sched/cputime.c (ffffffff810fecb7)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff8110701e)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff811144f3)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff811196cf)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff81121321)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/pids.c (ffffffff811a1ac7)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/trace/tracing_map.c (ffffffff811f32aa)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff8122cbbd)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/events/core.c (ffffffff81286ec3)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
```
In fs/io_uring.c (ffffffff813df78b)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/ext4/mballoc.c (ffffffff81479cfa)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/resize.c (ffffffff81487ac9)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff814a2ec7)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In crypto/algapi.c (ffffffff815a6f9e)
Location: include/linux/atomic/atomic-instrumented.h:631
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
In block/blk-cgroup.c (ffffffff815f36e1)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
```
```
In block/blk-iocost.c (ffffffff815f9e5d)
Location: include/linux/atomic/atomic-instrumented.h:631
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
In drivers/usb/core/devio.c (ffffffff8194ea60)
Location: include/linux/atomic/atomic-instrumented.h:631
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
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
In kernel/sched/fair.c (ffffffff811241aa)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81136165)
Location: include/linux/atomic/atomic-instrumented.h:673
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
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
```
```
In kernel/cgroup/pids.c (ffffffff811d248f)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/trace/tracing_map.c (ffffffff8122c8ba)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff8126eedd)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/events/core.c (ffffffff812db830)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
```
In fs/ext4/mballoc.c (ffffffff814fbedd)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/resize.c (ffffffff8150b3bc)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff8152a34b)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In crypto/algapi.c (ffffffff8164e0fe)
Location: include/linux/atomic/atomic-instrumented.h:673
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
In block/blk-cgroup.c (ffffffff816a4d01)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
```
```
In block/blk-iocost.c (ffffffff816ac0fd)
Location: include/linux/atomic/atomic-instrumented.h:673
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
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_buffer_account_pin
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
In kernel/sched/fair.c (ffffffff8114c14b)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81160745)
Location: include/linux/atomic/atomic-instrumented.h:673
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
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
```
```
In kernel/trace/tracing_map.c (ffffffff8127842a)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff812c46dd)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/events/core.c (ffffffff81343af7)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
```
In fs/ext4/mballoc.c (ffffffff81596643)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/resize.c (ffffffff815a603d)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff815c8ceb)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In crypto/algapi.c (ffffffff8170757e)
Location: include/linux/atomic/atomic-instrumented.h:673
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
In block/blk-cgroup.c (ffffffff81763ab1)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
```
```
In block/blk-iocost.c (ffffffff8176ab2d)
Location: include/linux/atomic/atomic-instrumented.h:673
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
In io_uring/rsrc.c (ffffffff817a0ab2)
Location: include/linux/atomic/atomic-instrumented.h:673
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
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
In kernel/sched/fair.c (ffffffff8115a3db)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81170e6b)
Location: include/linux/atomic/atomic-instrumented.h:1666
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
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
```
```
In kernel/trace/tracing_map.c (ffffffff8128fe6a)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff812eb6dd)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/events/core.c (ffffffff81374b7d)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
```
In mm/zswap.c (ffffffff8143681d)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
```
```
In fs/ext4/mballoc.c (ffffffff815cd085)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/resize.c (ffffffff815dc8ad)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff81600aac)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81733149)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/aead.c (ffffffff81741ea7)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/geniv.c (ffffffff817421ae)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff81742ff7)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/ahash.c (ffffffff81745152)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
```
```
In crypto/shash.c (ffffffff8174680a)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_update
```
```
In crypto/akcipher.c (ffffffff81747853)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
```
```
In crypto/dh.c (ffffffff81748b40)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a807)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/gcm.c (ffffffff817530a3)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In crypto/drbg.c (ffffffff817593c7)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
```
```
In block/blk-cgroup.c (ffffffff817a2b51)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
```
```
In block/blk-iocost.c (ffffffff817a9c0d)
Location: include/linux/atomic/atomic-instrumented.h:1666
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
In io_uring/rsrc.c (ffffffff817e1d03)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff81811c2b)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In net/ipv4/tcp.c (ffffffff81f0ae7d)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c120)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffaddc)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
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
In kernel/sched/fair.c (ffffffff81164b57)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr_common
```
```
In kernel/sched/build_policy.c (ffffffff81181db7)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:account_system_index_time
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
```
In kernel/trace/tracing_map.c (ffffffff812ab42a)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffffffff81309c2d)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_add
```
```
In kernel/events/core.c (ffffffff8139dead)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
  - kernel/events/core.c:__perf_remove_from_context
```
```
In mm/zswap.c (ffffffff81470b50)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_load
```
```
In mm/memcontrol.c (ffffffff814bafbf)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
```
```
In fs/ext4/mballoc.c (ffffffff81601763)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/resize.c (ffffffff8161518d)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_update_super
```
```
In fs/ext4/super.c (ffffffff816397fc)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
```
```
In crypto/aead.c (ffffffff81782d87)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/geniv.c (ffffffff8178308e)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/lskcipher.c (ffffffff81783da2)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/lskcipher.c:crypto_lskcipher_decrypt
  - crypto/lskcipher.c:crypto_lskcipher_encrypt
```
```
In crypto/skcipher.c (ffffffff81785347)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/ahash.c (ffffffff81787e7b)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_update
```
```
In crypto/shash.c (ffffffff817889b6)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_update
```
```
In crypto/akcipher.c (ffffffff817896c3)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
```
```
In crypto/dh.c (ffffffff8178a9e0)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c3c7)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/drbg.c (ffffffff8179b2c7)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
```
```
In block/blk-cgroup.c (ffffffff817e6691)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
```
```
In block/blk-iocost.c (ffffffff817ed9cd)
Location: include/linux/atomic/atomic-instrumented.h:1666
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
In io_uring/rsrc.c (ffffffff818260ac)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb42ed)
Location: include/linux/atomic/atomic-instrumented.h:1666
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:store_vblank
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
In virt/kvm/arm/arm.c (ffff8000100c71a0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
```
```
In kernel/fork.c (ffff8000100f472c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffff800010115128)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kthread.c (ffff800010128924)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In kernel/sched/core.c (ffff80001013d93c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffff80001013ec34)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/cputime.c (ffff80001013ef44)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffff800010145e28)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffff8000101504c0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffff800010155708)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffff80001015e030)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffff800010169db4)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/cgroup/cgroup.c (ffff8000101d28f4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/pids.c (ffff8000101deea4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffff8000101e344c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/audit_tree.c (ffff8000101f5640)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/ring_buffer.c (ffff800010219010)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffff8000102657d4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (ffff80001028f170)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffff80001029eb44)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/ring_buffer.c (ffff8000102a2838)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffff8000102b2910)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffff8000102ccb44)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffff8000102d3218)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/vmstat.c (ffff8000102dc9b4)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffff8000102e78a4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/workingset.c (ffff8000102f04c0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffff8000102f0660)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffff8000102f9a34)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffff800010306f5c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/msync.c:__arm64_sys_msync
```
```
In mm/rmap.c (ffff80001030a288)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffff8000103100b4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In mm/page_alloc.c (ffff80001031396c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffff800011458e2c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffff80001031e188)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffff8000103260e4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffff8000103337cc)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffff80001034b638)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffff80001034de98)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/migrate.c (ffff8000103518b4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffff800010355dac)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/page_counter.c (ffff800010360a20)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffff800010365d3c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
```
```
In mm/memory-failure.c (ffff8000103705b0)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/userfaultfd.c (ffff8000103781b0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/exec.c (ffff80001038c64c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/select.c (ffff8000103a1e50)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffff8000103ac6ec)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/file.c (ffff8000103b29f4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/fs-writeback.c (ffff8000103ca390)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/notify/mark.c (ffff8000103e9494)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffff8000103f1b30)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/aio.c (ffff8000103fdf20)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffff800010403c48)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
```
```
In fs/proc/fd.c (ffff800010446fa0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffff800010496e94)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffff8000104a8058)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffff8000104c0520)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/shm.c (ffff8000105286fc)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffff8000105adcec)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In security/integrity/ima/ima_api.c (ffff8000105b0824)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffff8000105ba98c)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-ioc.c (ffff8000105e87fc)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In block/blk-mq.c (ffff8000105efb14)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffff8000105f7208)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/genhd.c (ffff8000105faafc)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/genhd.c:part_inc_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/blk-cgroup.c (ffff80001060eb7c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffff800010610658)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffff800010615984)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffff8000106449fc)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/tty/tty_io.c (ffff800010852574)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffff8000108cd0e4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffff800010924f74)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffff8000109656dc)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/scsi/scsi_lib.c (ffff80001097834c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffff800010a2c318)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffff800010aeaa3c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In drivers/md/md-bitmap.c (ffff800010afad08)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/perf/arm-cci.c (ffff800010b912e0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_event_update
```
```
In drivers/perf/arm-ccn.c (ffff800010b930e0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update
```
```
In drivers/perf/arm_pmu.c (ffff800010b95008)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b9662c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_event_update
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98e88)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_update
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a6c8)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_update
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c0cc)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_perf_event_update
```
```
In net/core/scm.c (ffff800010bbde7c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffff800010bd2468)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffff800010c30c50)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffff800010c35f28)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f89c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffff800010ca4fc0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/inet_fragment.c (ffff800010cbefc4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/xfrm/xfrm_device.c (ffff800010cee690)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffff800010cf0d58)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffff800010cf47b4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffff800010cfc76c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffff800010d20b1c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d26b50)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffff800010d2cb40)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39d8c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffff800010d3a594)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffff800010d581d0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In arch/arm/mm/cache-l2x0-pmu.c (c0324afc)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_read
```
```
In arch/arm/mach-imx/mmdc.c (c03335a4)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_update
```
```
In kernel/sched/cputime.c (c038eef4)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (c0392270)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c039e130)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c03a306c)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (c03a9ecc)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/cgroup/pids.c (c0420600)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
```
```
In kernel/events/core.c (c04ce320)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:task_clock_event_update
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_mmap
```
```
In fs/ext4/mballoc.c (c0658f34)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (c066a210)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c0683c70)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (c0768cac)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
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
In block/blk-cgroup.c (c07b93c4)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-iocost.c (c07bde74)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_done_bio
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_kick_waitq
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:iocg_activate
```
```
In drivers/usb/core/devio.c (c0b016a0)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/perf/arm-cci.c (c0c7af10)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_event_update
```
```
In drivers/perf/arm-ccn.c (c0c7ce48)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update
```
```
In drivers/perf/arm_pmu.c (c0c7e66c)
Location: arch/arm/include/asm/atomic.h:376
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
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
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eeb8dc)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:create_physical_mapping
```
```
In arch/powerpc/platforms/pseries/lparcfg.c (c0000000000fd56c)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lparcfg.c:cpu_get_purr
```
```
In kernel/kthread.c (c000000000173584)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
```
```
In kernel/sched/core.c (c00000000018c800)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (c00000000018ddc4)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/cputime.c (c00000000018e0e8)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (c000000000198cbc)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c0000000001a4488)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c0000000001a991c)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (c0000000001b2c6c)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (c0000000001c1c28)
Location: arch/powerpc/include/asm/atomic.h:370
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
In kernel/cgroup/cgroup.c (c000000000246224)
Location: arch/powerpc/include/asm/atomic.h:370
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
In kernel/cgroup/pids.c (c00000000024d054)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (c000000000254034)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (c0000000002b77c0)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/cgroup.c (c00000000033bdc4)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (c000000000352ea0)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (c00000000039c598)
Location: arch/powerpc/include/asm/atomic.h:370
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
In mm/backing-dev.c (c00000000039f4e0)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (c0000000003a96a8)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (c0000000003c3948)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (c0000000003e1324)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
```
```
In mm/page_alloc.c (c0000000003ecca4)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (c000000001382758)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (c0000000003f3160)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (c0000000003f8d60)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (c00000000040eec8)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (c00000000042ac78)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (c00000000042d3ac)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (c00000000043c0c4)
Location: arch/powerpc/include/asm/atomic.h:370
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
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c00000000044a4c4)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (c00000000044bb04)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (c00000000045a734)
Location: arch/powerpc/include/asm/atomic.h:370
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
In mm/zsmalloc.c (c00000000046637c)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (c00000000046e4e4)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (c000000000484fd0)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
```
```
In fs/fs-writeback.c (c0000000004cbcc4)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (c000000000507464)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (c000000000514594)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
```
```
In fs/ext4/mballoc.c (c0000000005c11b4)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (c0000000005d59f0)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (c0000000005f6dac)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (c0000000007413f8)
Location: arch/powerpc/include/asm/atomic.h:370
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
In block/blk-core.c (c000000000778104)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (c000000000784a54)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (c00000000078f7e0)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (c0000000007ac1d4)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (c0000000007ad734)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (c0000000007b1dd8)
Location: arch/powerpc/include/asm/atomic.h:370
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
In lib/percpu-refcount.c (c0000000007dae30)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (c0000000007efd30)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (c0000000009c79b8)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (c000000000a32820)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (c000000000aed8e4)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/md/md.c (c000000000bd57d0)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
```
```
In net/ipv4/ip_fragment.c (c000000000d61e50)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (c000000000dd9800)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (c000000000e67628)
Location: arch/powerpc/include/asm/atomic.h:370
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
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
In arch/riscv/kernel/perf_event.c (ffffffe0000b963a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_event.c:riscv_pmu_read
```
```
In kernel/fork.c (ffffffe0000c0d08)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffe0000d214e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kthread.c (ffffffe0000df5be)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In kernel/sched/loadavg.c (ffffffe0000ed492)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/cputime.c (ffffffe0000ed6c8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffe0000f0a32)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffe0000f8c4a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fd2ac)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffe00010253e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffe00010aeaa)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/kcmp.c (ffffffe000128cd8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/cgroup/cgroup.c (ffffffe000151d58)
Location: arch/riscv/include/asm/atomic.h:76
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
In kernel/cgroup/pids.c (ffffffe000155f28)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffe00015909e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/audit_tree.c (ffffffe000168810)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/ring_buffer.c (ffffffe000179c9e)
Location: arch/riscv/include/asm/atomic.h:76
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
In kernel/bpf/syscall.c (ffffffe0001a1096)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (ffffffe0001c2182)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffe0001d01d2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/ring_buffer.c (ffffffe0001d146a)
Location: arch/riscv/include/asm/atomic.h:76
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
In mm/filemap.c (ffffffe0001d8206)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffe0001dbb34)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffe0001eb544)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffe0001ee3ce)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/vmstat.c (ffffffe0001f577c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:drain_zonestat
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:cpu_vm_stats_fold
  - mm/vmstat.c:fold_diff
  - mm/vmstat.c:fold_diff
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
In mm/backing-dev.c (ffffffe0001f75de)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffe0001fd3f4)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/workingset.c (ffffffe000203e62)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffe000203f0c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffe000209790)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:handle_mm_fault
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
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__pte_alloc
```
```
In mm/mmap.c (ffffffe000210948)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffe0002124de)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
```
```
In mm/rmap.c (ffffffe000214030)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffe0002184f2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In mm/page_alloc.c (ffffffe00021f6e2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffe00001743c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffe000221234)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffe000226440)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffe0002310ee)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffe00023ccec)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/page_counter.c (ffffffe0002402de)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffe000248c0e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/zsmalloc.c (ffffffe00024e678)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/userfaultfd.c (ffffffe00024feaa)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffe00025ecea)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:copy_strings
```
```
In fs/select.c (ffffffe00026a6fe)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffe000270cd6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/inode.c:drop_nlink
```
```
In fs/file.c (ffffffe000276a1a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/fs-writeback.c (ffffffe00028860e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/notify/mark.c (ffffffe00029dc84)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffe0002a4364)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/aio.c (ffffffe0002ac07c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
```
```
In fs/io_uring.c (ffffffe0002b1350)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/proc/fd.c (ffffffe0002dcd6e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffe00031b89e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffe0003284cc)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffe00033c3f6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/shm.c (ffffffe00038bd76)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In security/integrity/ima/ima_queue.c (ffffffe0003f6064)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffe0003f83d8)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffe00040069a)
Location: arch/riscv/include/asm/atomic.h:76
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
In block/blk-core.c (ffffffe000425bce)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-ioc.c (ffffffe000429796)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
```
```
In block/blk-mq.c (ffffffe00042dbd2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffe0004348ce)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/genhd.c (ffffffe000436e56)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - block/genhd.c:part_inc_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/blk-cgroup.c (ffffffe000446f28)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffe000447e60)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffe00044ab0e)
Location: arch/riscv/include/asm/atomic.h:76
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
In lib/percpu-refcount.c (ffffffe000462ea0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffe000470bf2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/tty/tty_io.c (ffffffe00052f80e)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffe0005a10d2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffe0005d1faa)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dfdca)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffe00064eaba)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/md/md.c (ffffffe0006ddf3c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffe0006ec5c2)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffe00074c646)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffe00075c970)
Location: arch/riscv/include/asm/atomic.h:76
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
In net/core/filter.c (ffffffe00077fffa)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffe0007a6b5c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c770c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffffffe0008008da)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/inet_fragment.c (ffffffe000814d48)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b856)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffe00083d0e0)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffe0008405de)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffe00084700a)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffe000862b9c)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffe000868b24)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffe00086cdc6)
Location: arch/riscv/include/asm/atomic.h:76
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
In net/ipv6/mcast.c (ffffffe00086f884)
Location: arch/riscv/include/asm/atomic.h:76
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
In net/ipv6/reassembly.c (ffffffe000872962)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875bb6)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffe000877238)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffe00088f410)
Location: arch/riscv/include/asm/atomic.h:76
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In kernel/kthread.c (ffffffff810c3366)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d8107)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810d92c9)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/cputime.c (ffffffff810d9816)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810e182f)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e8c28)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810ec8fc)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f2a7f)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff810fd815)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff81168b8d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff811a91fa)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/cgroup.c (ffffffff811fe4b4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8120f20e)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81248e28)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff8125adfd)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In mm/page_alloc.c (ffffffff81273ac8)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828c8b58)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8127cf76)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff81282eaa)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8128eec4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff812a214d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812a3fe3)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812acda4)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812b74a5)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812c06f2)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812cd191)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812ddaa6)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130cb3e)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81336da3)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b8801)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813c7c1b)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813e0135)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (ffffffff814b8f9f)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814e7cd3)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814ef0e6)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81503777)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff815049ad)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff81507f0f)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8152fced)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff816f2227)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff817289a4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff817b2b00)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff8183b3b5)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8194eb31)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5dc3)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a0c500)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In kernel/kthread.c (ffffffff810b1ba6)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c6b11)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810c7cc9)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/cputime.c (ffffffff810c81f6)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810d090f)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810d865f)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810dc99c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e2b8f)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff810eda09)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_enqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8115277e)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8115bd9d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff8119c17a)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/cgroup.c (ffffffff811f1204)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81201fb8)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff8123bdd2)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff8124d184)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In mm/page_alloc.c (ffffffff81265a38)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828c127d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8126eca0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812749ca)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff81280ade)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff81293c2d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff81295ab3)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff8129de6d)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/page_counter.c (ffffffff812a8675)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812b17ac)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812be001)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812ce726)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fd75e)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81327719)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a9291)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813b869b)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813d0bb5)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (ffffffff814a99bf)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814d8243)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814df626)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f3c37)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814f4e6d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff814f83bf)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8151ffcd)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff816cc327)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81701dd4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff817a4530)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff81802a25)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81908621)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f883)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff819c92c0)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In kernel/kthread.c (ffffffff810c28b6)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d48f7)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810d5609)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/cputime.c (ffffffff810d5b56)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810ddbaf)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e57cf)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e9a2c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810efbaf)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff810fa9d5)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff8116695d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff811a6fca)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/cgroup.c (ffffffff811fc284)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8120cfae)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81246bc8)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff81258b9d)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In mm/page_alloc.c (ffffffff81271868)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828db8d8)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8127ad16)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff81280cba)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8128ccd4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8129ff5d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812a1df3)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812aabb4)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812b52b5)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812be502)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812cafa1)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812db8b6)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130a92e)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81334873)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b6061)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813c50ab)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813dd4ae)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (ffffffff814b502f)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814e3d63)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814eb176)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814ff807)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81500a3d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff81503f9f)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8152ba2d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff8171f907)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767774)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff817ef5a0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff8188a9e5)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199ddc8)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_ct_kill_acct
  - net/netfilter/nf_conntrack_core.c:__nf_ct_refresh_acct
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9301)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10663)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a76f80)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a90b37)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In kernel/kthread.c (ffffffff810caee7)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In kernel/sched/core.c (ffffffff810dfcf1)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810e0eb9)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/cputime.c (ffffffff810e1456)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffffffff810e968f)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810efae8)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f49dc)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810fabff)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffffffff81105b97)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffffffff81173fee)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/tracing_map.c (ffffffff811b4d6a)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/cgroup.c (ffffffff8120aede)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8121be95)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff812563fb)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff8126859d)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In mm/page_alloc.c (ffffffff812812c8)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828e0cf9)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8128a8f5)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812908e6)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8129caa2)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff812b009d)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812b1fb3)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812baf04)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812c57f5)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812cef0b)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812dbcf6)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812ec869)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131c057)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81346d46)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813cadee)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813da3f4)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813f28ce)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In crypto/algapi.c (ffffffff814cdaaf)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814fd2c7)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff81504188)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff815189d7)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff815199b1)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff8151d54f)
Location: include/asm-generic/atomic-instrumented.h:870
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
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff815457be)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff8173ad5c)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81782eb1)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff818097e0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffffffff818a8da3)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2bf1)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1aeb3)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a835a0)
Location: include/asm-generic/atomic-instrumented.h:870
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
</details>
</li>
</ul>

## Differences
