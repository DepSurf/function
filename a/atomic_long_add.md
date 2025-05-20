# Function: <code>atomic_long_add</code>

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
In kernel/sched/core.c (ffffffff810ac444)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_call
```
```
In kernel/sched/loadavg.c (ffffffff810b0dda)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_load_enter_idle
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load_tick
```
```
In kernel/sched/fair.c (ffffffff810b5459)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
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
In kernel/cgroup.c (ffffffff81114620)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cpuset.c (ffffffff8111c897)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff811730f3)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811812bc)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff811ac534)
Location: include/asm-generic/atomic-long.h:124
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
Location: include/asm-generic/atomic-long.h:124
Inline: True
```
```
In mm/memory.c (ffffffff811bbc49)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - mm/memory.c:sync_mm_rss
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/swapfile.c (ffffffff811d30c4)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/hugetlb.c (ffffffff811de9d8)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/slub.c (ffffffff811e99f2)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:kmem_cache_open
```
```
In mm/huge_memory.c (ffffffff811f5666)
Location: include/asm-generic/atomic-long.h:124
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
Location: include/asm-generic/atomic-long.h:124
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
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/zsmalloc.c (ffffffff81205bc4)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff81212fd8)
Location: include/asm-generic/atomic-long.h:124
Inline: True
```
```
In fs/pipe.c (ffffffff81215618)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_fcntl
```
```
In fs/fs-writeback.c (ffffffff81236221)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/aio.c (ffffffff8125b992)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:do_io_submit
```
```
In block/bio.c (ffffffff813b10e1)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkcg
```
```
In block/blk-core.c (ffffffff813baab3)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff813c4ce0)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
```
```
In lib/percpu-refcount.c (ffffffff813ff018)
Location: include/asm-generic/atomic-long.h:124
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
In arch/x86/mm/gup.c (ffffffff8107171c)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/sched/core.c (ffffffff810b2d9d)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810b3c0e)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_enter_idle
```
```
In kernel/sched/fair.c (ffffffff810b9d09)
Location: include/asm-generic/atomic-long.h:180
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
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8189dd2e)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
```
```
In kernel/cgroup.c (ffffffff8111bfce)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cpuset.c (ffffffff81124797)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff81181ab7)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/events/core.c (ffffffff8119309e)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/memremap.c (ffffffff8119e2ff)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/memremap.c:get_zone_device_page
```
```
In mm/vmstat.c (ffffffff811c707d)
Location: include/asm-generic/atomic-long.h:180
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
Location: include/asm-generic/atomic-long.h:180
Inline: True
```
```
In mm/gup.c (0)
Location: include/asm-generic/atomic-long.h:180
Inline: True
```
```
In mm/memory.c (ffffffff811da332)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff811eedad)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff811f0f6a)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/hugetlb.c (ffffffff811fd7b7)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8120d0c7)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff8121601b)
Location: include/asm-generic/atomic-long.h:180
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
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81224241)
Location: include/asm-generic/atomic-long.h:180
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
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff8122b1f8)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff8123a240)
Location: include/asm-generic/atomic-long.h:180
Inline: True
```
```
In fs/pipe.c (ffffffff8123d070)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/fs-writeback.c (ffffffff81261b4b)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8128644d)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:lookup_ioctx
```
```
In block/bio.c (ffffffff813f4ab1)
Location: include/asm-generic/atomic-long.h:180
Inline: True
```
```
In block/blk-core.c (ffffffff813fe845)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff81408ebb)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
```
```
In lib/percpu-refcount.c (ffffffff81446ad0)
Location: include/asm-generic/atomic-long.h:180
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
In arch/x86/mm/gup.c (ffffffff8107529a)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In kernel/sched/core.c (ffffffff810b937a)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810ba24e)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_enter_idle
```
```
In kernel/sched/fair.c (ffffffff810c0a63)
Location: include/asm-generic/atomic-long.h:180
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
```
```
In kernel/locking/rwsem-xadd.c (ffffffff818d2ba6)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
```
```
In kernel/cgroup.c (ffffffff8112430e)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/cgroup.c:kill_css
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_get
  - kernel/cgroup.c:cgroup_get_e_css
```
```
In kernel/cpuset.c (ffffffff8112dbf2)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff8118dcde)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811a287e)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/memremap.c (ffffffff811add2f)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/memremap.c:get_zone_device_page
```
```
In mm/vmstat.c (ffffffff811d719d)
Location: include/asm-generic/atomic-long.h:180
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
Location: include/asm-generic/atomic-long.h:180
Inline: True
```
```
In mm/gup.c (0)
Location: include/asm-generic/atomic-long.h:180
Inline: True
```
```
In mm/memory.c (ffffffff811e9e5a)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff811ff6dc)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812018da)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
```
```
In mm/hugetlb.c (ffffffff8120e27a)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8121f127)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff812285e3)
Location: include/asm-generic/atomic-long.h:180
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
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812367c1)
Location: include/asm-generic/atomic-long.h:180
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
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff8123d765)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff8124cf97)
Location: include/asm-generic/atomic-long.h:180
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8127504b)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff812998ae)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:lookup_ioctx
```
```
In block/bio.c (ffffffff8140e4a1)
Location: include/asm-generic/atomic-long.h:180
Inline: True
```
```
In block/blk-core.c (ffffffff81418231)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff81422289)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
```
```
In lib/percpu-refcount.c (ffffffff814651a0)
Location: include/asm-generic/atomic-long.h:180
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
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810b4a9c)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/fair.c (ffffffff810c253b)
Location: include/asm-generic/atomic-long.h:180
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
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8190996a)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
```
```
In kernel/cgroup/cgroup.c (ffffffff81128b5b)
Location: include/asm-generic/atomic-long.h:180
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
In kernel/cgroup/cpuset.c (ffffffff8112f249)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff81192ac3)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811a9ef1)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/memremap.c (ffffffff811b5025)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/vmstat.c (ffffffff811e0001)
Location: include/asm-generic/atomic-long.h:180
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
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff811e77f9)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/gup.c (ffffffff811f0fd3)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__gup_device_huge
```
```
In mm/memory.c (ffffffff811f4f53)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:sync_mm_rss
```
```
In mm/madvise.c (ffffffff8120a4d1)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8120cb69)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff81217873)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8122b906)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff81231d1e)
Location: include/asm-generic/atomic-long.h:180
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
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81242289)
Location: include/asm-generic/atomic-long.h:180
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
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff81258f39)
Location: include/asm-generic/atomic-long.h:180
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812825b4)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff812a7745)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/bio.c (ffffffff8141b21f)
Location: include/asm-generic/atomic-long.h:180
Inline: True
```
```
In block/blk-core.c (ffffffff814260b8)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff8142f3ff)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In lib/percpu-refcount.c (ffffffff8146a2bd)
Location: include/asm-generic/atomic-long.h:180
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/md/md.c (ffffffff8173aa05)
Location: include/asm-generic/atomic-long.h:180
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
Location: include/asm-generic/atomic-long.h:181
Inline: True
```
```
In kernel/kthread.c (ffffffff810ac973)
Location: include/asm-generic/atomic-long.h:181
Inline: True
```
```
In kernel/sched/core.c (ffffffff810bb0d1)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810bbd6c)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/fair.c (ffffffff810c9ba6)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819939c6)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
```
```
In kernel/cgroup/cgroup.c (ffffffff8113518d)
Location: include/asm-generic/atomic-long.h:181
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
In kernel/cgroup/cpuset.c (ffffffff8113c0f5)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff811a0d81)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811bd7e4)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/memremap.c (ffffffff811c9231)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/vmstat.c (ffffffff811f5ef4)
Location: include/asm-generic/atomic-long.h:181
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
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff811fda3b)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/gup.c (ffffffff81205c28)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
```
```
In mm/memory.c (ffffffff8120e445)
Location: include/asm-generic/atomic-long.h:181
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
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff81226a36)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff81234400)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8124701a)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:new_slab
```
```
In mm/huge_memory.c (ffffffff8125298e)
Location: include/asm-generic/atomic-long.h:181
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
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8126207f)
Location: include/asm-generic/atomic-long.h:181
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
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff8127b0cd)
Location: include/asm-generic/atomic-long.h:181
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a512a)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff812caadb)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/bio.c (ffffffff81445e57)
Location: include/asm-generic/atomic-long.h:181
Inline: True
```
```
In block/blk-core.c (ffffffff814514fd)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-mq.c (ffffffff8145a951)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In lib/percpu-refcount.c (ffffffff814965ad)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff814a0432)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free
```
```
In drivers/block/loop.c (ffffffff8166fcdb)
Location: include/asm-generic/atomic-long.h:181
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/md/md.c (ffffffff817ad0e7)
Location: include/asm-generic/atomic-long.h:181
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
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In kernel/fork.c (ffffffff8108b067)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/kthread.c (ffffffff810b398a)
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c26de)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810c3436)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/fair.c (ffffffff810d1fb8)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819eff73)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
```
```
In kernel/cgroup/cgroup.c (ffffffff811438b4)
Location: include/asm-generic/atomic-long.h:198
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
In kernel/cgroup/cpuset.c (ffffffff8114ad1f)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/syscall.c (ffffffff811b5376)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/events/core.c (ffffffff811dda47)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/memremap.c (ffffffff811e9b5c)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/filemap.c (ffffffff811f003d)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/page-writeback.c (ffffffff811fea1a)
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In mm/vmscan.c (ffffffff8120aac8)
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/vmstat.c (ffffffff8121716c)
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff8121ed78)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/workingset.c (ffffffff812257dd)
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff81246558)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812492c6)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff81257373)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8126834e)
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/page_counter.c (ffffffff8127e2b5)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff81286739)
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff812a1eb4)
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812cc00b)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff812f48cf)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (ffffffff812f9dd6)
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In block/bio.c (ffffffff81479acd)
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In block/blk-core.c (ffffffff81484722)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-mq.c (ffffffff8148ef0f)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In lib/percpu-refcount.c (ffffffff814cb80d)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff814d55cb)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free
```
```
In drivers/block/loop.c (ffffffff816ab9cb)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/md/md.c (ffffffff817f5526)
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff818e96ee)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff81939413)
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff81990ab5)
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In kernel/fork.c (ffffffff8109370d)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/kthread.c (ffffffff810bcc8a)
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In kernel/sched/core.c (ffffffff810cb9d2)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810cc6e6)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/fair.c (ffffffff810db91c)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b990)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8114f3cd)
Location: include/asm-generic/atomic-long.h:198
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
In kernel/cgroup/cpuset.c (ffffffff81156de1)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/events/core.c (ffffffff811ede47)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/memremap.c (ffffffff811fa6cb)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/filemap.c (ffffffff812023c9)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/page_alloc.c (ffffffff812066b8)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:memblock_free_pages
```
```
In mm/page-writeback.c (ffffffff8120f1fa)
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In mm/vmscan.c (ffffffff8121d7c8)
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/vmstat.c (ffffffff8122a07c)
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81231d58)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
```
```
In mm/workingset.c (ffffffff81238d3f)
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/memblock.c (ffffffff828be664)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8125a97b)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8125db93)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8126b9e5)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8127de5a)
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/page_counter.c (ffffffff812929a5)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8129b6a9)
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffff812b6c63)
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812e0f24)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81309786)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (ffffffff8130dc34)
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In block/blk-core.c (ffffffff8149f73f)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:generic_make_request
```
```
In block/blk-mq.c (ffffffff814a89a5)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-cgroup.c (ffffffff814c283d)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814c4666)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff814e0543)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff814ea02b)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free
```
```
In drivers/block/loop.c (ffffffff816cc76c)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81714787)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81821406)
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819164c6)
Location: include/asm-generic/atomic-long.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/inet_fragment.c (ffffffff81969000)
Location: include/asm-generic/atomic-long.h:198
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff819c71f3)
Location: include/asm-generic/atomic-long.h:198
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/kthread.c (ffffffff810c2a76)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d3a44)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810d4b19)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/fair.c (ffffffff810dd24f)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
```
```
In kernel/locking/rwsem.c (ffffffff810f86bd)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
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
In kernel/cgroup/cpuset.c (ffffffff8116471e)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/bpf/cgroup.c (ffffffff811f8ccb)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff812058b6)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff81239d1c)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81242348)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff8125424d)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126c668)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828d7833)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff81275956)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8127adea)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff81286ce4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff81299cad)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff8129bc02)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812a32c4)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In mm/page_counter.c (ffffffff812ad375)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812b62b0)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812c2d59)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In fs/exec.c (ffffffff812d3936)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812ff646)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8132b973)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In block/blk-core.c (ffffffff814cd80f)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814d637c)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814dd676)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f0e37)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814f2e2d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff8150c4e8)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff81516ccd)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff817081f7)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff817500c4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff818637e5)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81978351)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf49f)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a36350)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/kthread.c (ffffffff810c8fe6)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ddf17)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810df0d9)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/fair.c (ffffffff810e767f)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
```
```
In kernel/locking/rwsem.c (ffffffff81104505)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
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
In kernel/cgroup/cpuset.c (ffffffff8117056d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff81205e94)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81212c46)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff8124801c)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff812507d8)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff812627ad)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127b478)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828dfca4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff81284926)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff8128a8ca)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff812968e4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff812a9b6d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812aba03)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812b47c4)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812beec5)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812c8112)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812d4bb1)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812e54c6)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131455e)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8133e7c3)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In block/blk-core.c (ffffffff814e6aff)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814ef6f3)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814f6b06)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8150a450)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8150c3cd)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff8152a338)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8153770d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff8172c447)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff817742b4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81895535)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819aecc1)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06023)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a6ce70)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:51
Inline: True
```
```
In kernel/kthread.c (ffffffff810d09d9)
Location: include/asm-generic/atomic-long.h:51
Inline: True
```
```
In kernel/sched/core.c (ffffffff810e64e1)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810e73b9)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/fair.c (ffffffff810ed96d)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
```
```
In kernel/locking/rwsem.c (ffffffff8110efb0)
Location: include/asm-generic/atomic-long.h:51
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
Location: include/asm-generic/atomic-long.h:51
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
In kernel/cgroup/cpuset.c (ffffffff811818b4)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
```
In kernel/bpf/cgroup.c (ffffffff8122d5ee)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8123ece6)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff8127618c)
Location: include/asm-generic/atomic-long.h:51
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
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/slab_common.c (ffffffff8127ee38)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/workingset.c (ffffffff812869e9)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff812926ad)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffff812ac403)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff812ad618)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff82cfd116)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/swapfile.c (ffffffff812bad9c)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff812c9e34)
Location: include/asm-generic/atomic-long.h:51
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
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812e0373)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812eaf1a)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff812f41a0)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812fd968)
Location: include/asm-generic/atomic-long.h:51
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
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff8130a6fb)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/fs-writeback.c (ffffffff8134e073)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8137849f)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff81380855)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:__io_async_wake
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-long.h:51
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff815575a6)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8156b5f2)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8156da57)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In lib/percpu-refcount.c (ffffffff8158da58)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8159bfa0)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff817e7c07)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81836c1c)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff819629d5)
Location: include/asm-generic/atomic-long.h:51
Inline: True
```
```
In drivers/md/dm.c (ffffffff81979a90)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
```
```
In net/ipv4/ip_fragment.c (ffffffff81a990d6)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5736)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81b65de9)
Location: include/asm-generic/atomic-long.h:51
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
Location: include/asm-generic/atomic-long.h:51
Inline: True
```
```
In kernel/kthread.c (ffffffff810cb5c7)
Location: include/asm-generic/atomic-long.h:51
Inline: True
```
```
In kernel/sched/core.c (ffffffff810e43ac)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810e4ff9)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/fair.c (ffffffff810eb79d)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
```
```
In kernel/locking/rwsem.c (ffffffff8110c2a9)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff811753df)
Location: include/asm-generic/atomic-long.h:51
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
In kernel/cgroup/cpuset.c (ffffffff8117e7c2)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
```
In kernel/bpf/trampoline.c (ffffffff81222b51)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff81235b2a)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff812490d6)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff81280a94)
Location: include/asm-generic/atomic-long.h:51
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
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff81290c39)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff8129cf94)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffff812b798d)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff812b9019)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff82fe9b47)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/swapfile.c (ffffffff812c681c)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff812d5a71)
Location: include/asm-generic/atomic-long.h:51
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
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memory_hotplug.c (ffffffff812eb2f3)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812f8581)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff812ffa90)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff81309d92)
Location: include/asm-generic/atomic-long.h:51
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
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff8131615c)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff8135af31)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff813861ac)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff8138f125)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
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
Location: include/asm-generic/atomic-long.h:51
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff81573bc0)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81585a8e)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81587f7c)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In lib/percpu-refcount.c (ffffffff815aa6de)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff815b79d1)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff817fcaf0)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff8184767d)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81969422)
Location: include/asm-generic/atomic-long.h:51
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa3046)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81b024f6)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81b74559)
Location: include/asm-generic/atomic-long.h:51
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
Location: include/asm-generic/atomic-long.h:51
Inline: True
```
```
In kernel/kthread.c (ffffffff810ccf04)
Location: include/asm-generic/atomic-long.h:51
Inline: True
```
```
In kernel/sched/core.c (ffffffff810e636b)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810e6fa9)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/fair.c (ffffffff810ed686)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
```
```
In kernel/locking/rwsem.c (ffffffff8110e0ee)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff81175f4e)
Location: include/asm-generic/atomic-long.h:51
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
In kernel/cgroup/cpuset.c (ffffffff8117e7d4)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/trampoline.c (ffffffff81227391)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff81239d7a)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8124d2a6)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff8125fa92)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/vmscan.c (ffffffff8127695c)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff81285b94)
Location: include/asm-generic/atomic-long.h:51
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
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff81296299)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff812a2677)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffff812bd3a0)
Location: include/asm-generic/atomic-long.h:51
Inline: True
```
```
In mm/page_alloc.c (ffffffff812be4e9)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff831f433d)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff812c5f73)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff812cd3bc)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff812dc775)
Location: include/asm-generic/atomic-long.h:51
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
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff812fea74)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff81306733)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff813105fe)
Location: include/asm-generic/atomic-long.h:51
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
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff8131c3d8)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff81361b31)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff8138d2fc)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff813933f9)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:io_prep_rw
  - fs/io_uring.c:tctx_task_work
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-long.h:51
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff8157bc50)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff8158c45e)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8158edcc)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In lib/percpu-refcount.c (ffffffff815b52fe)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff815c2844)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff817e16c0)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182a83d)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8194d3b2)
Location: include/asm-generic/atomic-long.h:51
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e056)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81aede03)
Location: include/asm-generic/atomic-long.h:51
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/reassembly.c (ffffffff81b62fb8)
Location: include/asm-generic/atomic-long.h:51
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
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
```
```
In kernel/kthread.c (ffffffff810df972)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
```
```
In kernel/sched/core.c (ffffffff810fd854)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810fe57c)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/fair.c (ffffffff81106393)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
```
```
In kernel/locking/rwsem.c (ffffffff8112cff2)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8119d524)
Location: include/linux/atomic/atomic-instrumented.h:1209
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
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/trampoline.c (ffffffff8125f491)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff8127454d)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81286eb6)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/filemap.c (ffffffff8129c402)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/vmscan.c (ffffffff812b416c)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff812c4d06)
Location: include/linux/atomic/atomic-instrumented.h:1209
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
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff812d6a29)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff812e39e7)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:finish_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffff812ffac0)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
```
```
In mm/page_alloc.c (ffffffff81300c37)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff832da75e)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff8130a973)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff8131274a)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8132392d)
Location: include/linux/atomic/atomic-instrumented.h:1209
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
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff81348671)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff81350563)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8135b90e)
Location: include/linux/atomic/atomic-instrumented.h:1209
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
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff813696d0)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff813ac28a)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff813daa5c)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff813e166c)
Location: include/linux/atomic/atomic-instrumented.h:1209
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
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
```
```
In block/blk-mq-sched.c (ffffffff815e102b)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff815f1a8e)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff815f4e2c)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In lib/percpu-refcount.c (ffffffff8161b69e)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8162a7b7)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff8186fe31)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b62cc)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff819f27c2)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81b49246)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae1b3)
Location: include/linux/atomic/atomic-instrumented.h:1209
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
```
```
In net/ipv6/reassembly.c (ffffffff81c2aa68)
Location: include/linux/atomic/atomic-instrumented.h:1209
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
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
```
```
In kernel/kthread.c (ffffffff810f9cf0)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
```
```
In kernel/sched/core.c (ffffffff8111a26a)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/fair.c (ffffffff811212db)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
```
```
In kernel/sched/build_utility.c (ffffffff81148b38)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
```
```
In kernel/locking/rwsem.c (ffffffff8114e2f6)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd863)
Location: include/linux/atomic/atomic-instrumented.h:1292
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
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/trampoline.c (ffffffff812a9bd6)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup.c (ffffffff812c4bbb)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff812db81e)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmscan.c (ffffffff81310121)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff81322236)
Location: include/linux/atomic/atomic-instrumented.h:1292
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
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff81336159)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memory.c (ffffffff81344d73)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pmd_install
```
```
In mm/vmalloc.c (ffffffff81366b84)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff813680e8)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff8348f875)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81373561)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff8137d2da)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff813914a3)
Location: include/linux/atomic/atomic-instrumented.h:1292
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
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff813be819)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff813c8813)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff813d51b9)
Location: include/linux/atomic/atomic-instrumented.h:1292
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
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff813e77f1)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff81432349)
Location: include/linux/atomic/atomic-instrumented.h:1292
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
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
```
```
In block/blk-mq.c (ffffffff81683a3e)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-mq-sched.c (ffffffff8168fc23)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff816a3a80)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff816a6a37)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In io_uring/io_uring.c (ffffffff816d7312)
Location: include/linux/atomic/atomic-instrumented.h:1292
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
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff816fbc21)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff819b67f0)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a0182f)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81b5b681)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd68d0)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81d412f6)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv6/reassembly.c (ffffffff81dc7f5f)
Location: include/linux/atomic/atomic-instrumented.h:1292
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
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
```
```
In kernel/sched/core.c (ffffffff811419d2)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/fair.c (ffffffff8114a89c)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
```
```
In kernel/sched/build_utility.c (ffffffff81177368)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
```
```
In kernel/locking/rwsem.c (ffffffff8117d276)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff81210f03)
Location: include/linux/atomic/atomic-instrumented.h:1292
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
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/helpers.c (ffffffff812f44f6)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/trampoline.c (ffffffff81308b76)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup_iter.c (ffffffff81325542)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff8132a0a0)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81343ae5)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmscan.c (ffffffff8138373f)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff813963a6)
Location: include/linux/atomic/atomic-instrumented.h:1292
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
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff813ad3d9)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memory.c (ffffffff813bcfa3)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pmd_install
```
```
In mm/vmalloc.c (ffffffff813e2923)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff813e4138)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff83ec1f5a)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff813f0cd1)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff813fa75a)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8140e4cc)
Location: include/linux/atomic/atomic-instrumented.h:1292
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
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff81441097)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff8144cf03)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8145ac1a)
Location: include/linux/atomic/atomic-instrumented.h:1292
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
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff8146f40c)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff814c2da1)
Location: include/linux/atomic/atomic-instrumented.h:1292
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
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
```
```
In block/blk-mq.c (ffffffff817413be)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-mq-sched.c (ffffffff8174e7e4)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81763c2d)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81765950)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In io_uring/io_uring.c (ffffffff8178df41)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:handle_tw_list
  - io_uring/io_uring.c:__io_alloc_req_refill
  - io_uring/io_uring.c:io_fallback_req_func
```
```
In io_uring/uring_cmd.c (0)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
```
```
In io_uring/net.c (0)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
```
```
In io_uring/rsrc.c (ffffffff817a0c2d)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_refs_refill
```
```
In io_uring/rw.c (0)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff817d8f78)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff817ee8c1)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/pci/p2pdma.c (ffffffff8191bf4f)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81b2ba00)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7fe7f)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81cf5051)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
```
```
In net/core/sock.c (ffffffff81d9e383)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/ip_fragment.c (ffffffff81e96e77)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ec9b0b)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a0a6)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f1ec29)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv6/reassembly.c (ffffffff81f98cd1)
Location: include/linux/atomic/atomic-instrumented.h:1292
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81faca62)
Location: include/linux/atomic/atomic-instrumented.h:1292
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
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
```
```
In kernel/sched/core.c (ffffffff8114d685)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/fair.c (ffffffff8115c61c)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
```
```
In kernel/sched/build_utility.c (ffffffff81187fb8)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
```
```
In kernel/locking/rwsem.c (ffffffff8118df26)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff812268f3)
Location: include/linux/atomic/atomic-instrumented.h:3230
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
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/trampoline.c (ffffffff81337a96)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8135577d)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff8135a1e0)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81374b6b)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmscan.c (ffffffff813b514d)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff813c91f6)
Location: include/linux/atomic/atomic-instrumented.h:3230
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
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/workingset.c (ffffffff813e17c9)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memory.c (ffffffff813f1ce6)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pmd_install
```
```
In mm/vmalloc.c (ffffffff814174f0)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff81418e88)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff836e75a3)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81424811)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/swapfile.c (ffffffff8142d69a)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff814418ab)
Location: include/linux/atomic/atomic-instrumented.h:3230
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
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/huge_memory.c (ffffffff81476959)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff814827c3)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff8149087a)
Location: include/linux/atomic/atomic-instrumented.h:3230
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
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff814a3bd6)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/fs-writeback.c (ffffffff814f63bb)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:wb_io_lists_populated
```
```
In fs/aio.c (ffffffff8152c248)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
```
```
In block/blk-mq.c (ffffffff817831ac)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-cgroup.c (ffffffff817a2018)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff817a4a10)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In io_uring/io_uring.c (ffffffff817c90fa)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_activate_pollwq
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:io_fallback_tw
  - io_uring/io_uring.c:__io_alloc_req_refill
```
```
In lib/percpu-refcount.c (ffffffff81818188)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8182ec7b)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/pci/p2pdma.c (ffffffff8195f562)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81b7bd00)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd3ed2)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81d5e8d9)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - drivers/md/md.c:md_account_bio
  - drivers/md/md.c:md_write_start
```
```
In net/core/sock.c (ffffffff81e0cbff)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef56b4)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81f2865a)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69bc2)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff81f7e729)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv6/reassembly.c (ffffffff81ff96ab)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200d472)
Location: include/linux/atomic/atomic-instrumented.h:3230
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
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/kthread.c (ffffffff81134200)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
```
```
In kernel/cred.c (ffffffff8113e566)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/sched/core.c (ffffffff8115943b)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/fair.c (ffffffff8116679a)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/sched/fair.c:switched_from_fair
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:__update_blocked_fair
```
```
In kernel/sched/build_utility.c (ffffffff81196768)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
```
```
In kernel/locking/rwsem.c (ffffffff8119c8d6)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811e32bc)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_enqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8123e583)
Location: include/linux/atomic/atomic-instrumented.h:3230
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
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/syscall.c (ffffffff81310765)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/trampoline.c (ffffffff8135d8d6)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_enter
```
```
In kernel/bpf/memalloc.c (ffffffff81372fd0)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8137e0fd)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init
```
```
In kernel/bpf/cgroup.c (ffffffff81382d90)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8139de9b)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/watch_queue.c (ffffffff813b2bde)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/shrinker.c (ffffffff813e4c41)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/shrinker.c:reparent_shrinker_deferred
```
```
In mm/vmstat.c (ffffffff813f3b86)
Location: include/linux/atomic/atomic-instrumented.h:3230
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
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_create
```
```
In mm/percpu.c (ffffffff813fa1ad)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
```
```
In mm/workingset.c (ffffffff8140bf09)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memory.c (ffffffff8141c9d6)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:pmd_install
```
```
In mm/vmalloc.c (ffffffff81444000)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff814459d8)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff83919da3)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/memory_hotplug.c (ffffffff81451641)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/slub.c (ffffffff814578c0)
Location: include/linux/atomic/atomic-instrumented.h:3230
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
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8147bb32)
Location: include/linux/atomic/atomic-instrumented.h:3230
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
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/page_counter.c (ffffffff814b1b43)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff814c0157)
Location: include/linux/atomic/atomic-instrumented.h:3230
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
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff814d4a76)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/file_table.c (ffffffff814e26a3)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - fs/file_table.c:init_file
```
```
In fs/fs-writeback.c (ffffffff8152aafb)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:wb_io_lists_populated
```
```
In fs/fs_context.c (ffffffff81538fd9)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/aio.c (ffffffff81561128)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
```
```
In security/keys/process_keys.c (ffffffff816cad23)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff816cbeb9)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff816cce92)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/audit.c (ffffffff81737344)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/domain.c (ffffffff8174198d)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
```
```
In block/blk-mq.c (ffffffff817c6cd9)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-cgroup.c (ffffffff817e5b65)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff817e85e0)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In io_uring/io_uring.c (ffffffff81816efe)
Location: include/linux/atomic/atomic-instrumented.h:3230
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
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In io_uring/register.c (ffffffff8182bb9e)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
```
```
In lib/percpu-refcount.c (ffffffff8185d488)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8188083b)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/pci/p2pdma.c (ffffffff819a8bbf)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/block/loop.c (ffffffff81bcfd2f)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c28b4c)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffffffff81d4d3db)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/md/md.c (ffffffff81e15a9d)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - drivers/md/md.c:md_account_bio
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_flush_request
```
```
In net/core/sock.c (ffffffff81ec957f)
Location: include/linux/atomic/atomic-instrumented.h:3230
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
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81fed0ea)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/inet_fragment.c (ffffffff82030242)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff82044dd4)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/unix/af_unix.c (ffffffff8207c0e6)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/reassembly.c (ffffffff820c731b)
Location: include/linux/atomic/atomic-instrumented.h:3230
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dc43c)
Location: include/linux/atomic/atomic-instrumented.h:3230
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128924)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/sched/core.c (ffff80001013d93c)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffff80001013ec34)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/fair.c (ffff800010145e28)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
```
```
In kernel/locking/rwsem.c (ffff800010169db4)
Location: include/asm-generic/atomic-long.h:50
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
In kernel/cgroup/cgroup.c (ffff8000101d28f4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/cpuset.c (ffff8000101e344c)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/ring_buffer.c (ffff800010219010)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/cgroup.c (ffff80001028f170)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffff800010294190)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/ring_buffer.c (ffff8000102a28d8)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/vmstat.c (ffff8000102dc9b4)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffff8000102e78a4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffff8000102f9a34)
Location: include/asm-generic/atomic-long.h:50
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
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (ffff8000103100b4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In mm/page_alloc.c (ffff80001031396c)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffff800011458e2c)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffff80001031ed84)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffff800010324558)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffff8000103337cc)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffff80001034b650)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffff80001034de98)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffff800010355dac)
Location: include/asm-generic/atomic-long.h:50
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
In mm/khugepaged.c (ffff80001035f5cc)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/page_counter.c (ffff800010360a20)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffff800010366388)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
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
In mm/zsmalloc.c (ffff800010376338)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffff80001038c64c)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In fs/fs-writeback.c (ffff8000103ca390)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffff8000103fdf20)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In block/blk-core.c (ffff8000105e4384)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffff8000105efb14)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffff8000105f7208)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffff80001060dc00)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffff800010610658)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffff8000106356dc)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffff8000106449fc)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffff800010924f74)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffff80001097834c)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffff800010aeaa3c)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In drivers/perf/arm-cci.c (ffff800010b912e0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_event_update
```
```
In drivers/perf/arm-ccn.c (ffff800010b930e0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update
```
```
In drivers/perf/arm_pmu.c (ffff800010b95008)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b9662c)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_event_update
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98e88)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_update
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a6c8)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_update
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c0cc)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_perf_event_update
```
```
In net/ipv4/ip_fragment.c (ffff800010c5f89c)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffff800010cbefc4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffff800010d355c4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
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
In kernel/kthread.c (c037ad40)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_associate_blkcg
```
```
In kernel/sched/core.c (c038d8ec)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (c038eb70)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/fair.c (c0393b1c)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
```
```
In kernel/locking/rwsem.c (c03b5e7c)
Location: include/asm-generic/atomic-long.h:544
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
In kernel/cgroup/cgroup.c (c041bb70)
Location: include/asm-generic/atomic-long.h:544
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
In kernel/cgroup/cpuset.c (c0424200)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/ring_buffer.c (c045ab74)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/cgroup.c (c04be9b0)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (c04cc6f4)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/ring_buffer.c (c04d2494)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/vmstat.c (c0502610)
Location: include/asm-generic/atomic-long.h:544
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
In mm/backing-dev.c (c0504680)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (c050b9c4)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (c051b4a0)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc
  - mm/memory.c:sync_mm_rss
```
```
In mm/vmalloc.c (c052c548)
Location: include/asm-generic/atomic-long.h:544
Inline: True
```
```
In mm/page_alloc.c (c0531714)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (c1532db4)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (c05378f4)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (c053c220)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:get_swap_pages
```
```
In mm/slub.c (c054f69c)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/page_counter.c (c055315c)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (c055c654)
Location: include/asm-generic/atomic-long.h:544
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
In mm/zsmalloc.c (c0560dcc)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (c0573624)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - fs/exec.c:acct_arg_size
```
```
In fs/fs-writeback.c (c05a69d0)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (c05d1568)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
```
```
In block/blk-core.c (c0791634)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (c079ac2c)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (c07a2950)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (c07b8758)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (c07ba864)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (c07db520)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (c07eac40)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (c0a07d58)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (c0a4c13c)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (c0bca2a8)
Location: include/asm-generic/atomic-long.h:544
Inline: True
```
```
In net/ipv4/ip_fragment.c (c0d6e8f8)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (c0dca72c)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (c0e37684)
Location: include/asm-generic/atomic-long.h:544
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:create_physical_mapping
```
```
In kernel/kthread.c (c000000000173584)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/sched/core.c (c00000000018c800)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (c00000000018ddc4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/fair.c (c000000000198cbc)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
```
```
In kernel/locking/rwsem.c (c0000000001c1c28)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
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
In kernel/cgroup/cpuset.c (c000000000254034)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (c00000000033bdc4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (c00000000034dc24)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (c00000000039c598)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (c0000000003a96a8)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (c0000000003c3948)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In mm/page_alloc.c (c0000000003ecca4)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (c0000000003f3160)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (c0000000003f8d60)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (c00000000040eec8)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (c00000000042ac78)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (c00000000042d3ac)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (c00000000043c0c4)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (c00000000044bb04)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (c00000000045a734)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (c00000000046e4e4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (c000000000484fd0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In fs/fs-writeback.c (c0000000004cbcc4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (c000000000507464)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (c000000000514594)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In block/blk-core.c (c000000000778104)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (c000000000784a54)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (c00000000078f7e0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (c0000000007aaee4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (c0000000007ad734)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (c0000000007dae30)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (c0000000007efd30)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (c0000000009c79b8)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (c000000000a32820)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (c000000000bd57d0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In net/ipv4/ip_fragment.c (c000000000d61e50)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (c000000000dd9800)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (c000000000e67628)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_event.c:riscv_pmu_read
```
```
In kernel/kthread.c (ffffffe0000df5be)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/sched/loadavg.c (ffffffe0000ed492)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
```
In kernel/sched/fair.c (ffffffe0000f0a32)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
```
```
In kernel/locking/rwsem.c (ffffffe00010aeaa)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffe000151d58)
Location: include/asm-generic/atomic-long.h:50
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
In kernel/cgroup/cpuset.c (ffffffe00015909e)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/ring_buffer.c (ffffffe000179c9e)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_read_page
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/cgroup.c (ffffffe0001c2182)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffe0001c37aa)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:cpu_clock_event_read
  - kernel/events/core.c:cpu_clock_event_stop
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/ring_buffer.c (ffffffe0001d14ce)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/vmstat.c (ffffffe0001f577c)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffe0001fd3f4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffe000209790)
Location: include/asm-generic/atomic-long.h:50
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
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffe0002184f2)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In mm/page_alloc.c (ffffffe00021f6e2)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffe0002206aa)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffe000224be0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffe0002310ee)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffe00023ccf6)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/page_counter.c (ffffffe0002402de)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffe00024873e)
Location: include/asm-generic/atomic-long.h:50
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
In mm/zsmalloc.c (ffffffe00024eaac)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In fs/exec.c (ffffffe00025ecea)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:copy_strings
```
```
In fs/fs-writeback.c (ffffffe00028860e)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffe0002ac07c)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
```
```
In block/blk-core.c (ffffffe000425bce)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffe00042dbd2)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffe0004348ce)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffe000446386)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffe000447e60)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffe000462ea0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffe000470bf2)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffe0005a10d2)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005dfdca)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffe0006ddf3c)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c770c)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffe000814d48)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffe000872962)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/kthread.c (ffffffff810c3366)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d8107)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810d92c9)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/fair.c (ffffffff810e182f)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
```
```
In kernel/locking/rwsem.c (ffffffff810fd815)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
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
In kernel/cgroup/cpuset.c (ffffffff81168b8d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff811fe4b4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff8120b296)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff8124066c)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81248e28)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff8125adfd)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In mm/page_alloc.c (ffffffff81273ac8)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828c8b58)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8127cf76)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff81282eaa)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8128eec4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff812a214d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812a3fe3)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812acda4)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812b74a5)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812c06f2)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812cd191)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812ddaa6)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130cb3e)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81336da3)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In block/blk-core.c (ffffffff814df0df)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814e7cd3)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814ef0e6)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81502a30)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff815049ad)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff81522918)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8152fced)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff816f2227)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff817289a4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8183b3b5)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8194eb31)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5dc3)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a0c500)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/kthread.c (ffffffff810b1ba6)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c6b11)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810c7cc9)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/fair.c (ffffffff810d090f)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
```
```
In kernel/locking/rwsem.c (ffffffff810eda09)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_enqueue
```
```
In kernel/cgroup/cgroup.c (ffffffff8115277e)
Location: include/asm-generic/atomic-long.h:50
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
In kernel/cgroup/cpuset.c (ffffffff8115bd9d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff811f1204)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff811fe066)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff8123366c)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff8123bdd2)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff8124d184)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In mm/page_alloc.c (ffffffff81265a38)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828c127d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8126eca0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812749ca)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff81280ade)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff81293c2d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff81295ab3)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff8129de6d)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/page_counter.c (ffffffff812a8675)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812b17ac)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812be001)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812ce726)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fd75e)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81327719)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In block/blk-core.c (ffffffff814cfa7f)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814d8243)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814df626)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814f31e0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814f4e6d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff81512bf8)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8151ffcd)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff816cc327)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81701dd4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff81802a25)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81908621)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f883)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff819c92c0)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/kthread.c (ffffffff810c28b6)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d48f7)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810d5609)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/fair.c (ffffffff810ddbaf)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
```
```
In kernel/locking/rwsem.c (ffffffff810fa9d5)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
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
In kernel/cgroup/cpuset.c (ffffffff8116695d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff811fc284)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81209036)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff8123e40c)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81246bc8)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff81258b9d)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In mm/page_alloc.c (ffffffff81271868)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828db8d8)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8127ad16)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff81280cba)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8128ccd4)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff8129ff5d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812a1df3)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812aabb4)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812b52b5)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812be502)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812cafa1)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812db8b6)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130a92e)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81334873)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In block/blk-core.c (ffffffff814db16f)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814e3d63)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814eb176)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff814feac0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81500a3d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff8151e9a8)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff8152ba2d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff8171f907)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767774)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff8188a9e5)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9301)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10663)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a76f80)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a90b37)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/kthread.c (ffffffff810caee7)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In kernel/sched/core.c (ffffffff810dfcf1)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffffffff810e0eb9)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/fair.c (ffffffff810e968f)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
```
```
In kernel/locking/rwsem.c (ffffffff81105b97)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
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
In kernel/cgroup/cpuset.c (ffffffff81173fee)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/bpf/cgroup.c (ffffffff8120aede)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81217dc6)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmstat.c (ffffffff8124db3c)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff812563fb)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memory.c (ffffffff8126859d)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In mm/page_alloc.c (ffffffff812812c8)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffffffff828e0cf9)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
```
```
In mm/madvise.c (ffffffff8128a8f5)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffffffff812908e6)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_range_free
```
```
In mm/hugetlb.c (ffffffff8129caa2)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffffffff812b009d)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memory_hotplug.c (ffffffff812b1fb3)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/huge_memory.c (ffffffff812baf04)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/page_counter.c (ffffffff812c57f5)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffffffff812cef0b)
Location: include/asm-generic/atomic-long.h:50
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
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/memremap.c (ffffffff812dbcf6)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/exec.c (ffffffff812ec869)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131c057)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/aio.c (ffffffff81346d46)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/dax.c (0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In block/blk-core.c (ffffffff814f3f84)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-mq.c (ffffffff814fd2c7)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff81504188)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (ffffffff81517eff)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff815199b1)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In lib/percpu-refcount.c (ffffffff81538258)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffffffff815457be)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/block/loop.c (ffffffff8173ad5c)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81782eb1)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (ffffffff818a8da3)
Location: include/asm-generic/atomic-long.h:50
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff819c2bf1)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1aeb3)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv6/reassembly.c (ffffffff81a835a0)
Location: include/asm-generic/atomic-long.h:50
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
</details>
</li>
</ul>

## Differences
