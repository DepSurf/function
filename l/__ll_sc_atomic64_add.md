# Function: <code>__ll_sc_atomic64_add</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/arm.c (ffff8000100c7230)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
```
```
In kernel/fork.c (ffff8000100f47b4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffff80001011515c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kthread.c (ffff800010128948)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
```
```
In kernel/sched/core.c (ffff80001013d958)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
```
In kernel/sched/loadavg.c (ffff80001013ec60)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_load_nohz_fold
```
```
In kernel/sched/cputime.c (ffff80001013efb4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_index_time
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/sched/fair.c (ffff800010145e58)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffff8000101506a8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffff8000101558b0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffff80001015e09c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
```
```
In kernel/locking/rwsem.c (ffff800010169dd8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
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
In kernel/kcmp.c (ffff800010197b80)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/cgroup/cgroup.c (ffff8000101d2904)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/pids.c (ffff8000101def10)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/cpuset.c (ffff8000101e349c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/audit_tree.c (ffff8000101f566c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/ring_buffer.c (ffff80001021919c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
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
In kernel/trace/tracing_map.c (ffff80001022ec18)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_update_sum
```
```
In kernel/bpf/syscall.c (ffff800010265cb8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/cgroup.c (ffff80001028f184)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffff80001029ec58)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:perf_swevent_event
```
```
In kernel/events/ring_buffer.c (ffff8000102a2888)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
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
In kernel/events/uprobes.c (ffff8000102a581c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffff8000102b2ab4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffff8000102b7a68)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffff8000102ccbb4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffff8000102d3570)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/vmstat.c (ffff8000102dc9fc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
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
In mm/backing-dev.c (ffff8000102df930)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffff8000102e78bc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/workingset.c (ffff8000102f04dc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffff8000102f069c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffff8000102f9ac0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
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
In mm/mmap.c (ffff8000103040d0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffff800010306fd4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/msync.c:__arm64_sys_msync
```
```
In mm/rmap.c (ffff80001030a2f8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffff8000103100d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
```
```
In mm/page_alloc.c (ffff8000103139a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:adjust_managed_page_count
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/memblock.c (ffff80001031d6c0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
```
```
In mm/madvise.c (ffff80001031e730)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swapfile.c (ffff800010326240)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffff80001033387c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/slub.c (ffff80001034b6b4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/memory_hotplug.c (ffff80001034deb8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
```
In mm/migrate.c (ffff800010351d80)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffff8000103560fc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
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
In mm/khugepaged.c (ffff8000103600d4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/page_counter.c (ffff800010360a6c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffff800010365e04)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
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
```
```
In mm/memory-failure.c (ffff800010370604)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffff8000103759d0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/userfaultfd.c (ffff8000103781c4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/exec.c (ffff80001038c664)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
```
```
In fs/select.c (ffff8000103a1e64)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffff8000103ac70c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
```
```
In fs/file.c (ffff8000103b2a2c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/fs-writeback.c (ffff8000103ca3a8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
```
```
In fs/notify/mark.c (ffff8000103e94b4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffff8000103f1b8c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
```
```
In fs/aio.c (ffff8000103fdff8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffff800010403da4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
```
```
In fs/proc/fd.c (ffff800010447084)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffff800010496ea4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/resize.c (ffff8000104a8088)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffff8000104c0b04)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In ipc/shm.c (ffff80001052871c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffff8000105add98)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
```
```
In security/integrity/ima/ima_api.c (ffff8000105b08a4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffff8000105ba9a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
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
In block/blk-core.c (ffff8000105e43e0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-ioc.c (ffff8000105e8818)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
```
```
In block/blk-mq.c (ffff8000105efb28)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffff8000105f721c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/genhd.c (ffff8000105fab10)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - block/genhd.c:part_inc_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/blk-cgroup.c (ffff80001060eb98)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_add_delay
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffff80001061066c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffff80001061599c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
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
In lib/percpu-refcount.c (ffff8000106356f0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/genalloc.c (ffff800010644a20)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
```
```
In drivers/tty/tty_io.c (ffff800010852c14)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffff8000108cd0f8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffff800010924f88)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffff8000109656f0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/scsi/scsi_lib.c (ffff800010978360)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/usb/core/devio.c (ffff800010a2c348)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_increase_memory_usage
```
```
In drivers/md/md.c (ffff800010aeaa50)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
```
```
In drivers/md/md-bitmap.c (ffff800010afad4c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/perf/arm-cci.c (ffff800010b91304)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_event_update
```
```
In drivers/perf/arm-ccn.c (ffff800010b93104)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update
```
```
In drivers/perf/arm_pmu.c (ffff800010b95050)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_event_update
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b96650)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_event_update
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98ea8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_update
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a6e0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__32bit_counter_update
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__64bit_counter_update
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c0f0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_perf_event_update
```
```
In net/core/scm.c (ffff800010bbdec4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffff800010bd2b0c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
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
In net/core/filter.c (ffff800010c01548)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffff800010c30c78)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffff800010c36010)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/ip_fragment.c (ffff800010c5fadc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/icmp.c (ffff800010ca510c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/inet_fragment.c (ffff800010cbeff8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/xfrm/xfrm_device.c (ffff800010cee6b0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffff800010cf0db8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffff800010cf47d0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffff800010cfc800)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffff800010d20bf4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d26dcc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffff800010d2ce1c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
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
In net/ipv6/mcast.c (ffff800010d301cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
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
In net/ipv6/reassembly.c (ffff800010d3578c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39dbc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffff800010d3a640)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffff800010d58310)
Location: arch/arm64/include/asm/atomic_ll_sc.h:210
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
