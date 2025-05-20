# Function: <code>atomic_sub_return_relaxed</code>

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
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d8176)
Location: include/linux/atomic/atomic-instrumented.h:151
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140cb01)
Location: include/linux/atomic/atomic-instrumented.h:342
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8143b23d)
Location: include/linux/atomic/atomic-instrumented.h:342
Inline: True
Inline callers:
  - mm/rmap.c:folio_remove_rmap_pmd
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (c15018a0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/arm/mm/fault-armv.c (c1507e94)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - arch/arm/mm/fault-armv.c:check_writebuffer_bugs
```
```
In kernel/fork.c (c0353fb0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (c035a434)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (c0361f14)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (c0363de0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/umh.c (c036f2a0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (c03708e0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/kthread.c (c037ad64)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_associate_blkcg
```
```
In kernel/nsproxy.c (c037bc4c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (c037d5c8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/groups.c (c0380790)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (c038d2c8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/topology.c (c03a77e0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (c03b4fa4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In kernel/power/swap.c (c03c0a74)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (c03cb28c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In kernel/rcu/srcutree.c (c03d8d04)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (c03dc648)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In kernel/futex.c (c0401990)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (c04064e8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/uid16.c:__se_sys_setgroups16
```
```
In kernel/module.c (c040a618)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/module.c:__se_sys_delete_module
```
```
In kernel/acct.c (c040e518)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In kernel/cgroup/cgroup.c (c041bcf4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/namespace.c (c041c9d4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (c041ed34)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c04202b4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c0421364)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (c04258c4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/utsname.c (c0425aa4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (c04267e8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (c04276c8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (c0428708)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/audit_tree.c (c04356a0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/trace/trace_events.c (c0475ad8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (c047e29c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In kernel/bpf/syscall.c (c0492d20)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/bpf/arraymap.c (c04ad350)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cpumap.c (c04b8010)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In kernel/bpf/stackmap.c (c04bb270)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/bpf/cgroup.c (c04bf5e0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (c04c7bfc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:put_event
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (c04d74d0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (c04d8668)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_serial_worker
```
```
In mm/filemap.c (c04de188)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/oom_kill.c (c04e4870)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (c04e97a4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/readahead.c (c04eaee8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (c04ecadc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (c04eeb20)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c04f5534)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c04fdb48)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/backing-dev.c (c0504464)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/mmu_context.c (c050490c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/slab_common.c (c050b98c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (c0515674)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (c051c09c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (c051c414)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (c051ce08)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (c0526bd8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (c052d280)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In mm/page_alloc.c (c053196c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/madvise.c (c05385e0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c053aa58)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c053ef7c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (c05428fc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/mmu_notifier.c (c0543890)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (c0545ec8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/slub.c (c054b290)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (c0552a3c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/page_counter.c (c0553210)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In mm/memcontrol.c (c055cb00)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/zsmalloc.c (c0561fa8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (c056398c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c0564a18)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c0564f98)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/hmm.c (c0566908)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/open.c (c0568de4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (c056b6ac)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/file_table.c (c056e0a0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (c056f390)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (c05759f8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:would_dump
  - fs/exec.c:copy_strings
  - fs/exec.c:copy_strings
```
```
In fs/pipe.c (c0576ac8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (c057a274)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (c058910c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/inode.c (c058de38)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (c05912c4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In fs/namespace.c (c0593040)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (c059df7c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (c05a70a4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/splice.c (c05a9bd0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (c05af010)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (c05b64f0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (c05b99dc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (c05bcf20)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (c05bebc8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/notify/group.c (c05c0680)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (c05c0abc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In fs/userfaultfd.c (c05cdd44)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
```
```
In fs/aio.c (c05cfc58)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:exit_aio
  - fs/aio.c:free_ioctx_users
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (c05d69cc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_mem_free
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In fs/verity/enable.c (c05dd750)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (c05df6f4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (c05e91f8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/binfmt_elf_fdpic.c (c05ea328)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
```
```
In fs/mbcache.c (c05edcc0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/coredump.c (c05f10dc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (c05f5018)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (c05f64c0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (c0600e4c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/inode.c (c060195c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/root.c (c0602974)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (c0603e30)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (c0609c18)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (c0614e08)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In fs/kernfs/file.c (c0616c54)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_put_open_node
```
```
In fs/sysfs/mount.c (c06197f0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (c061aa38)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (c061c39c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/configfs/dir.c:detach_attrs
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:put_fragment
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (c061e538)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (c063cbb0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (c064b544)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (c0653714)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_unload_buddy
  - fs/ext4/mballoc.c:ext4_mb_unload_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (c065c130)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (c0665ab4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (c0666674)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (c0684bd4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In fs/ext4/xattr.c (c0688bc4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/verity.c (c068bd94)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (c068df90)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (c0692100)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (c069d3bc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (c069fd74)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (c06b3be8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (c06b409c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (c06bf400)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (c06c9dec)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/inode.c (c06cd268)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In fs/fuse/readdir.c (c06d0420)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
```
```
In ipc/mqueue.c (c06e3b78)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (c06e5678)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/keyctl.c (c06eb398)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (c06ec9a8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (c06ed1d0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (c06eda14)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In security/tomoyo/common.c (c072fe38)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (c073279c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (c0745ec0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (c074e3e4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bio.c (c07883f0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
  - block/bio.c:bio_endio
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-core.c (c07914a8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-ioc.c (c07951c0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In block/blk-merge.c (c079809c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In block/blk-mq-sched.c (c07a291c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/partition-generic.c (c07a790c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (c07aa7e8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (c07ab3c8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (c07ab7f0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (c07ac4b4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (c07ae6bc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (c07afc28)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (c07b0400)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (c07b05e0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (c07b08ec)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (c07b0b44)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (c07b0e2c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (c07b1f94)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (c07b235c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/blk-cgroup.c (c07b92a4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (c07bc4a4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/blk-wbt.c (c07c8850)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/percpu-refcount.c (c07db6a4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/sbitmap.c (c0811bd8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0852148)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_retention_disable
```
```
In drivers/pci/pci.c (c0881e00)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/video/fbdev/core/fbmem.c (c08c7ba0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In drivers/dma/dmaengine.c (c091db1c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (c09476c4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/reset/core.c (c095955c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In drivers/tty/tty_buffer.c (c0964f44)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In drivers/tty/serial/serial_core.c (c097f254)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (c09ad690)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In drivers/base/power/runtime.c (c09e7ef4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (c09efab8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/block/loop.c (c0a068c8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/mfd/mfd-core.c (c0a29678)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_disable
```
```
In drivers/dax/super.c (0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (c0a3e400)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (c0a42120)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (c0a457ec)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (c0a4c9e0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/sd.c (c0a5966c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/net/tun.c (c0ac6b30)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/usb/core/devio.c (c0b02b30)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/power/supply/power_supply_core.c (c0bac6cc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/md.c (c0bccdf8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (c0bd77f0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (c0bdcc80)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (c0be84f8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (c0be9088)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/edac/edac_pci_sysfs.c (c0bf1d5c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In drivers/cpufreq/omap-cpufreq.c (c0c00484)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/cpufreq/omap-cpufreq.c:omap_cpu_exit
```
```
In drivers/remoteproc/remoteproc_core.c (c0c647ec)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In drivers/devfreq/devfreq.c (c0c6885c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In net/core/sock.c (c0ccaa18)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (c0cd67d4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/net_namespace.c (c0cdc294)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (c0ce4a94)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (c0cfadd8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (c0d1a04c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (c0d20080)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (c0d251bc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (c0d27480)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (c0d5cdc0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_input.c (c0d6e1c4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (c0d71bdc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (c0d848cc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (c0d90b54)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (c0d9e0cc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (c0da6658)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
```
```
In net/ipv4/udp.c (c0dac6a8)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (c0dc207c)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (c0dcbd64)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (c0dda174)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (c0ddd3d0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (c0de9f70)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (c0debb80)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (c0df3074)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df4308)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (c0dfb338)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/unix/scm.c (c0dfbf74)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_output.c (c0dffbe0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (c0e050c0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (c0e1b3bc)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (c0e2eeac)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/ip6_flowlabel.c (c0e419e4)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (c0e5b844)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/rfkill/core.c (c0e69c08)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In net/dns_resolver/dns_key.c (c0e6fde0)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In lib/dec_and_lock.c (c0e7fc34)
Location: arch/arm/include/asm/atomic.h:226
Inline: True
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
In arch/powerpc/mm/pgtable-frag.c (c00000000008907c)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable-frag.c:pte_frag_destroy
```
```
In arch/powerpc/mm/book3s64/mmu_context.c (c000000000090660)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/mmu_context.c:arch_exit_mmap
```
```
In kernel/module.c (c000000000229a3c)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - kernel/module.c:__se_sys_delete_module
```
```
In kernel/bpf/syscall.c (c000000000304950)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_sub
```
```
In kernel/padata.c (c00000000035cdec)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (c0000000003ebae0)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memcontrol.c (c000000000451d20)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
```
```
In fs/aio.c (c0000000005091d0)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In drivers/tty/tty_buffer.c (c0000000008fc278)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free
```
```
In net/core/sock.c (c000000000c835a0)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/core/skbuff.c (c000000000c8d51c)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_data
```
```
In net/ipv4/tcp_output.c (c000000000d8d300)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (c000000000da6780)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (c000000000db36cc)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (c000000000dd909c)
Location: arch/powerpc/include/asm/atomic.h:100
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
</details>
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
