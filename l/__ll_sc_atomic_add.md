# Function: <code>__ll_sc_atomic_add</code>

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
In arch/arm64/kernel/insn.c (ffff800010da7a64)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:aarch64_insn_patch_text_cb
```
```
In arch/arm64/kernel/smp.c (ffff80001009c260)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:secondary_start_kernel
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6e20)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:cpu_suspend
```
```
In virt/kvm/kvm_main.c (ffff8000100bf330)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_fault
  - virt/kvm/kvm_main.c:kvm_create_vm
```
```
In virt/kvm/arm/mmu.c (ffff8000100cb3bc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_get_pud
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
```
```
In kernel/fork.c (ffff8000100f4a8c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffff8000100fa2cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In kernel/exit.c (ffff8000100fd920)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffff800010107e5c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In kernel/umh.c (ffff80001011ad28)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffff80001011cd8c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:wq_worker_running
```
```
In kernel/nsproxy.c (ffff80001012b46c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/nsproxy.c:copy_namespaces
```
```
In kernel/cred.c (ffff80001012d108)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/async.c (ffff80001012ec40)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/async.c:async_schedule_node_domain
```
```
In kernel/kmod.c (ffff800010130740)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/groups.c (ffff80001013117c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffff800010da1b28)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/fair.c (ffff80001014c4c4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffff80001014ea00)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/deadline.c (ffff800010152cc4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In kernel/sched/cpupri.c (ffff800010159fcc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/topology.c (ffff80001015bfdc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_get_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/debug.c (ffff800010163858)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/locking/qrwlock.c (ffff80001016c9a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/process.c (ffff8000101700c4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
```
```
In kernel/printk/printk_safe.c (ffff800010176d44)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/irq/handle.c (ffff8000101786b4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In kernel/irq/manage.c (ffff800010179c88)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffff800010188fe8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_expedite_gp
```
```
In kernel/rcu/srcutree.c (ffff80001018a6b8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffff800010191730)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_prepare_cpu
```
```
In kernel/profile.c (ffff800010198dc0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/futex.c (ffff8000101ba09c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
```
In kernel/module.c (ffff8000101c4f58)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/cgroup/cgroup.c (ffff8000101d4f24)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:online_css
  - kernel/cgroup/cgroup.c:online_css
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffff8000101da418)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de358)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_css_online
```
```
In kernel/utsname.c (ffff8000101e5370)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffff8000101e65ec)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffff8000101e7954)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffff8000101e9540)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In kernel/debug/debug_core.c (ffff8000101f9868)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_breakpoint
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/relay.c (ffff80001020b864)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/relay.c:relay_buf_fault
```
```
In kernel/trace/ring_buffer.c (ffff800010218514)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_advance_reader
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_disable
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
  - kernel/trace/ring_buffer.c:rb_set_head_page
```
```
In kernel/trace/trace.c (ffff80001022163c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/blktrace.c (ffff800010235d1c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In kernel/trace/fgraph.c (ffff800010238260)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
```
In kernel/trace/trace_kdb.c (ffff800010255230)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
```
In kernel/bpf/syscall.c (ffff800010260150)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_inc
```
```
In kernel/bpf/cpumap.c (ffff800010288978)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/bpf/offload.c (ffff80001028a05c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/events/core.c (ffff800010296dfc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_refresh
```
```
In kernel/events/uprobes.c (ffff8000102a8500)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (ffff8000102a9fd4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/jump_label.c (ffff8000102ab5d0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In mm/filemap.c (ffff8000102b0de8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffff8000102b7a74)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page-writeback.c (ffff8000102bd22c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffff8000102c3424)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:get_kernel_pages
```
```
In mm/truncate.c (ffff8000102c527c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffff8000102ca220)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/shmem.c (ffff8000102d615c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/backing-dev.c (ffff8000102ddaa4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/backing-dev.c:set_wb_congested
```
```
In mm/mmu_context.c (ffff8000102e0078)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffff8000102f22b0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102fa290)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffff8000102fe39c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mmap.c (ffff8000102ffdc8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/mmap.c:special_mapping_fault
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:__remove_shared_vm_struct
```
```
In mm/mmu_gather.c (ffff800010304da0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/mprotect.c (ffff800010304f28)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffff80001030ac78)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/rmap.c:anon_vma_fork
```
```
In mm/page_alloc.c (ffff8000103190a8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/madvise.c (ffff80001031edd4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (ffff800010320b14)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/swap_state.c (ffff800010321a6c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffff800010328094)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/frontswap.c (ffff80001032a9b4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffff80001032c3dc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffff800010335e98)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffff80001033b6a8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_lookup
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/mmu_notifier.c (ffff80001033d0b0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffff800010341ba8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/memory_hotplug.c (ffff80001034e0a8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/migrate.c (ffff80001035333c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff800010354cdc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035df68)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffff800010365fa4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
```
In mm/zpool.c (ffff80001037265c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/zpool.c:zpool_get_driver
```
```
In mm/zsmalloc.c (ffff800010375e74)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
```
```
In mm/memfd.c (ffff80001037c60c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffff80001037ddf0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffff800010385868)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
  - fs/file_table.c:__alloc_file
```
```
In fs/super.c (ffff800010386e2c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/super.c:freeze_super
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffff80001038c7d4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/exec.c:free_bprm
  - fs/exec.c:would_dump
  - fs/exec.c:kernel_read_file
```
```
In fs/pipe.c (ffff80001038fd68)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_get
```
```
In fs/dcache.c (ffff8000103a87a8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:take_dentry_name_snapshot
```
```
In fs/inode.c (ffff8000103aeb40)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:inode_lru_isolate
```
```
In fs/file.c (ffff8000103b1d94)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffff8000103bada4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
```
In fs/fs-writeback.c (ffff8000103c80bc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/fs_context.c (ffff8000103d5b28)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/buffer.c (ffff8000103dbf7c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/block_dev.c (ffff8000103e1020)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
  - fs/block_dev.c:blkdev_direct_IO
```
```
In fs/direct-io.c (ffff8000103e53d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/proc_namespace.c (ffff8000103e7b18)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/mark.c (ffff8000103ea57c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103edf20)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init
```
```
In fs/userfaultfd.c (ffff8000103f6db4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/userfaultfd.c:__arm64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffff8000103faaa4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/aio.c:put_reqs_available
  - fs/aio.c:aio_migratepage
```
```
In fs/io_uring.c (ffff80001040319c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_timeout_fn
```
```
In fs/verity/enable.c (ffff800010411ac4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/binfmt_script.c (ffff80001041db34)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/binfmt_script.c:load_script
```
```
In fs/binfmt_elf.c (ffff80001041fa54)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffff800010423314)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/mbcache.c (ffff800010425884)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffff80001042c190)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/iomap/direct-io.c (ffff80001042d408)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/quota/dquot.c (ffff8000104323ec)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
```
```
In fs/proc/task_mmu.c (ffff8000104399d0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In fs/proc/root.c (ffff80001043ca04)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffff80001043ee18)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
```
```
In fs/proc/proc_sysctl.c (ffff80001044ba04)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll_notify
```
```
In fs/kernfs/dir.c (ffff800010453d60)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_get
```
```
In fs/kernfs/file.c (ffff80001045539c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_open
```
```
In fs/sysfs/mount.c (ffff800010457ad8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/dir.c (ffff80001045bd7c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
  - fs/configfs/dir.c:configfs_new_dirent
```
```
In fs/configfs/symlink.c (ffff80001045d278)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
```
```
In fs/devpts/inode.c (ffff80001045ea70)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
```
```
In fs/ext4/balloc.c (ffff800010460e30)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffff800010475e28)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffff80001047966c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
```
```
In fs/ext4/inode.c (ffff8000104805f8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
```
In fs/ext4/mballoc.c (ffff80001048f924)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
  - fs/ext4/mballoc.c:ext4_mb_use_best_found
```
```
In fs/ext4/mmp.c (ffff800010499154)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/page-io.c (ffff8000104a41c8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/resize.c (ffff8000104a8090)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffff8000104c0ac8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffff8000104c4f88)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/jbd2/transaction.c (ffff8000104ccab8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
```
```
In fs/jbd2/commit.c (ffff8000104cf1cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffff8000104d13f4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffff8000104d8c7c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
```
```
In fs/fat/dir.c (ffff8000104e4e30)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_add_new_entries
```
```
In fs/fat/fatent.c (ffff8000104e8d9c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_collect_bhs
```
```
In fs/ecryptfs/miscdev.c (ffff8000104fda14)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_open
```
```
In fs/fuse/dev.c (ffff800010503bd8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (ffff80001050c0ac)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readpages_fill
```
```
In fs/fuse/inode.c (ffff800010512480)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffff80001051d640)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/msg.c (ffff80001051f5f4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/mqueue.c (ffff80001052c298)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffff80001052cdc8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffff80001052e618)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/key.c:key_alloc
```
```
In security/keys/keyctl.c (ffff80001053306c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/process_keys.c (ffff800010535294)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffff800010535920)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffff800010536798)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/selinux/hooks.c (ffff80001054e404)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_secmark_refcount_inc
```
```
In security/selinux/selinuxfs.c (ffff8000105569e8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_mmap_policy_fault
```
```
In security/selinux/ss/services.c (ffff800010567274)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/selinux/xfrm.c (ffff80001056bbc0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
  - security/selinux/xfrm.c:selinux_xfrm_policy_clone
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
```
In security/tomoyo/common.c (ffff80001057d688)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_open_control
  - security/tomoyo/common.c:tomoyo_supervisor
  - security/tomoyo/common.c:tomoyo_supervisor
```
```
In security/tomoyo/condition.c (ffff80001057e724)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
```
In security/tomoyo/domain.c (ffff8000105805cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/memory.c (ffff8000105842bc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_get_group
```
```
In security/tomoyo/securityfs_if.c (ffff800010586788)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffff80001146b164)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/tomoyo/tomoyo.c:tomoyo_task_alloc
```
```
In security/apparmor/domain.c (ffff800010594f74)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/policy_unpack.c (ffff800010598b24)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In block/bio.c (ffff8000105dd224)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - block/bio.c:bio_map_user_iov
```
```
In block/blk-core.c (ffff8000105e0c20)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - block/blk-core.c:blk_set_pm_only
```
```
In block/blk-map.c (ffff8000105e98ec)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-mq.c (ffff8000105f08c4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffff8000105f4294)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-iocost.c (ffff800010615560)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/iov_iter.c (ffff80001062df98)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
```
In lib/rhashtable.c (ffff800010636ecc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
```
```
In lib/sbitmap.c (ffff80001066a18c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_prepare_to_wait
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676c6c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake
```
```
In drivers/pci/pci.c (ffff8000106e74cc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffff8000107010f8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010708d2c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070be1c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/ats.c (ffff8000107166c0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
```
```
In drivers/video/fbdev/core/fbmem.c (ffff800010743edc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:register_framebuffer
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074c2dc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault
```
```
In drivers/acpi/apei/ghes.c (ffff8000107af4bc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cached
```
```
In drivers/amba/bus.c (ffff8000107b9450)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/clk/clk.c (ffff8000107bf7f4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/dma/dmaengine.c (ffff8000107fd40c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d550)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b020)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/tty/tty_buffer.c (ffff80001085d2c0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:__tty_buffer_request_room
  - drivers/tty/tty_buffer.c:tty_buffer_flush
  - drivers/tty/tty_buffer.c:tty_buffer_lock_exclusive
```
```
In drivers/tty/vt/keyboard.c (ffff80001086a5b8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
```
In drivers/tty/serial/kgdb_nmi.c (ffff8000108a8610)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In drivers/tty/serial/kgdboc.c (ffff8000108a8fb4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler
```
```
In drivers/char/virtio_console.c (ffff8000108b2b40)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d6430)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev
```
```
In drivers/connector/cn_queue.c (ffff8000108dd440)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/cn_proc.c (ffff8000108de1bc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In drivers/base/core.c (ffff8000108e7498)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/dd.c (ffff8000108eaa4c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/devtmpfs.c (ffff8000108f6e38)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
```
In drivers/base/power/runtime.c (ffff8000108fd2ec)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_forbid
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffff800010902f08)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/wakeup.c (ffff800010905160)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_irq_wakeup
```
```
In drivers/base/power/domain.c (ffff800010908704)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_add_subdomain
```
```
In drivers/block/loop.c (ffff800010922778)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e44c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake
```
```
In drivers/mfd/mfd-core.c (ffff80001094094c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In drivers/nvdimm/bus.c (ffff800010952f04)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095cbbc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096c924)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_vm_fault
```
```
In drivers/scsi/hosts.c (ffff80001096fa64)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_lib.c (ffff800010976fe8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_disable_disk_events
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
```
In drivers/scsi/sg.c (ffff80001098f0fc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_vma_fault
```
```
In drivers/net/tun.c (ffff8000109dba70)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e9c28)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a00474)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffff800010a08ed4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In drivers/usb/core/hub.c (ffff800010a19cec)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffff800010a1e3c4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/urb.c (ffff800010a20ac4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_anchor_suspend_wakeups
  - drivers/usb/core/urb.c:usb_block_urb
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/driver.c (ffff800010a259f4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/devio.c (ffff800010a2ef80)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/core/devices.c (ffff800010a34d2c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usbfs_conn_disc_event
```
```
In drivers/usb/core/port.c (ffff800010a3603c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a37358)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a90f78)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010aba1d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010abac40)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac4050)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_update
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc8dc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle
  - drivers/power/supply/power_supply_core.c:power_supply_get_by_name
```
```
In drivers/md/md.c (ffff800010aeff68)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_seq_next
  - drivers/md/md.c:md_attr_store
  - drivers/md/md.c:md_attr_show
  - drivers/md/md.c:mddev_find
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffff800010af8334)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffff800010affe28)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dm_blk_open
  - drivers/md/dm.c:dm_issue_global_event
```
```
In drivers/md/dm-stripe.c (ffff800010b06730)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-io.c (ffff800010b0a438)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0ae8c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback
  - drivers/md/dm-kcopyd.c:dm_kcopyd_copy
  - drivers/md/dm-kcopyd.c:dispatch_job
```
```
In drivers/md/dm-stats.c (ffff800010b0de14)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b1405c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_npe
  - drivers/edac/edac_pci_sysfs.c:edac_pci_handle_pe
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a794)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b3d8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffff800010b4b2a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b812a4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In drivers/perf/arm-cci.c (ffff800010b91db8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_event_init
```
```
In drivers/ras/debugfs.c (ffff800010b9e558)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - drivers/ras/debugfs.c:trace_open
```
```
In net/core/sock.c (ffff800010badc88)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/core/sock.c:sock_omalloc
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb80c4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/datagram.c (ffff800010bbc8e8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/net_namespace.c (ffff800010bc2050)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffff800010bcb4d4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In net/core/neighbour.c (ffff800010be667c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_probe
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffff800010bfdc30)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/flow_offload.c (ffff800010c087f8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffff800010c0edf0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/core/bpf_sk_storage.c (ffff800010c31a68)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
```
In net/sched/sch_generic.c (ffff800010c3803c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In net/sched/cls_api.c (ffff800010c43634)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_cls_offload_cnt_update
```
```
In net/sched/act_api.c (ffff800010c47690)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
```
```
In net/netlink/af_netlink.c (ffff800010c4df0c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:netlink_skb_set_owner_r
  - net/netlink/af_netlink.c:netlink_overrun
```
```
In net/ipv4/route.c (ffff800010c58794)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/ip_output.c (ffff800010c62464)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6b9fc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6cff0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp.c (ffff800010c75354)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffff800010c7a590)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_queue_rcv
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_drop
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8cd6c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93f9c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable
```
```
In net/ipv4/raw.c (ffff800010c98894)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9f5f8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:__first_packet_length
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/fib_frontend.c (ffff800010cb59d4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
```
```
In net/ipv4/fib_semantics.c (ffff800010cb66c8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf72c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
```
```
In net/ipv4/ping.c (ffff800010cc0ddc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffff800010cce0c0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3f60)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde0c4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
```
```
In net/unix/af_unix.c (ffff800010cf4190)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffff800010cf84fc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffff800010d011c0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
```
```
In net/ipv6/route.c (ffff800010d15480)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_alloc
```
```
In net/ipv6/udp.c (ffff800010d27788)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffff800010d2adcc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38d80)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d403bc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/ip6mr.c (ffff800010d45aec)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48ca4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/seg6_hmac.c (ffff800010d5263c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffff800010d5b4fc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mm_open
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d68934)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d6a6a4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6ad58)
Location: arch/arm64/include/asm/atomic_ll_sc.h:111
Inline: True
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
