# Function: <code>atomic_cmpxchg</code>

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
In arch/x86/events/core.c (ffffffff81005c39)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81031ae3)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/smp.c (ffffffff8105099c)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810528f8)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81053448)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/cred.c (ffffffff810a257e)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/smpboot.c (ffffffff810a40dd)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_wait_death
  - kernel/smpboot.c:cpu_report_death
```
```
In kernel/sched/fair.c (ffffffff810badff)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff81821996)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
```
In kernel/locking/spinlock.c (ffffffff81823fbf)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
```
```
In kernel/locking/osq_lock.c (ffffffff810ca3c2)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
```
```
In kernel/locking/lglock.c (ffffffff810ca4d4)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/locking/lglock.c:lg_local_lock
  - kernel/locking/lglock.c:lg_local_lock_cpu
  - kernel/locking/lglock.c:lg_global_lock
  - kernel/locking/lglock.c:lg_double_lock
  - kernel/locking/lglock.c:lg_double_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810ca6eb)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810cbd36)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810cfa53)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810d55e1)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/module.c (ffffffff811052f3)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
  - kernel/module.c:SyS_delete_module
```
```
In kernel/cgroup.c (ffffffff81114d54)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81133816)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff8113fe17)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8114629d)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_read_start
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
```
```
In kernel/trace/trace.c (ffffffff8114aa1d)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:trace_find_cmdline
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81157384)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff81157e1d)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/events/core.c (ffffffff8117a071)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/events/core.c:perf_lock_task_context
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In kernel/events/ring_buffer.c (ffffffff811857ff)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff81187b9f)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff8118aecf)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
```
```
In mm/filemap.c (ffffffff8118cfae)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_pages
```
```
In mm/swap.c (ffffffff8119d36b)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/swap.c:__get_page_tail
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff811a0275)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/shmem.c (ffffffff811a87cd)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/mmap.c (ffffffff811c73df)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff811cbc4d)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:page_lock_anon_vma_read
```
```
In mm/swapfile.c (ffffffff811d5861)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff811d7e11)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff811dfab9)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff811e4afb)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff8181a635)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
```
```
In mm/migrate.c (ffffffff811f1488)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff811f3ce5)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff811faa45)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812016c9)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/balloon_compaction.c (ffffffff81207508)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_isolate
```
```
In mm/page_idle.c (ffffffff81208160)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/open.c (ffffffff81209907)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
  - fs/open.c:do_dentry_open
```
```
In fs/super.c (ffffffff8120f113)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/super.c:grab_super
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
```
```
In fs/exec.c (ffffffff81212152)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff8121ab80)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff81249431)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/userfaultfd.c (ffffffff8125aca2)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8125b38d)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/aio.c:get_reqs_available
```
```
In fs/proc/task_mmu.c (ffffffff812772ce)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff8127927b)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_follow_link
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_reg_open
```
```
In fs/proc/base.c (ffffffff8127a7cc)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_net.c (ffffffff8128640f)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_net
```
```
In fs/kernfs/mount.c (ffffffff81288a10)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/kernfs/dir.c (ffffffff8128a5a7)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
```
```
In fs/ext4/balloc.c (ffffffff8128f059)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81292ea3)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
```
```
In fs/ext4/super.c (ffffffff812ba759)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/mballoc.c (ffffffff812cd613)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In ipc/util.c (ffffffff81324c33)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/keyring.c (ffffffff813318e9)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff813751b3)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:profile_remove
```
```
In security/apparmor/context.c (ffffffff81377381)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_get_task_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_restore_previous_label
```
```
In security/apparmor/domain.c (ffffffff8137a6d7)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/policy.c (ffffffff8137fc67)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_may_open_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/procattr.c (ffffffff81382dc9)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81383ae8)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/resource.c (ffffffff81387557)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81388bb9)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff81389271)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
```
In security/apparmor/net.c (ffffffff81390ab9)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81392b08)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
```
```
In block/blk-mq-tag.c (ffffffff813c6cee)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_clear_tag
  - block/blk-mq-tag.c:bt_clear_tag
  - block/blk-mq-tag.c:bt_get
```
```
In lib/dec_and_lock.c (ffffffff813e9311)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
```
```
In lib/dump_stack.c (ffffffff813e9361)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/kobject.c (ffffffff813ebf8d)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
```
```
In drivers/phy/phy-core.c (ffffffff8141bd40)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/gpio/gpio-intel-mid.c (ffffffff81429f92)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_probe
```
```
In drivers/pci/pci-driver.c (ffffffff8143a726)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b6610)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff814fdde3)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff8151aa98)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff8153bbea)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff81555e29)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_disable
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815a3479)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff815a5063)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
```
In drivers/scsi/scsi_scan.c (ffffffff815b32f5)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/usb/core/hcd.c (ffffffff8160c367)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81613c1f)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8161fbe3)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81662414)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/thermal/thermal_core.c (ffffffff816877a1)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff816c9c47)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff816ca76e)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In net/core/sock.c (ffffffff817007f9)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff817068f0)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/neighbour.c (ffffffff817245da)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/fib_rules.c (ffffffff81739c46)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/ipv4/route.c (ffffffff8175431a)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/inetpeer.c (ffffffff8175817b)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff8176006e)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81762636)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81763899)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177cbe9)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177f31c)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81788ece)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817adf58)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/ipv6/addrlabel.c (ffffffff817d2f61)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff817d546e)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff817da421)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/udp.c (ffffffff817e2471)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
```
```
In net/ipv6/raw.c (ffffffff817e5e6f)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f0655)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f6778)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81801ebe)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In lib/klist.c (ffffffff8181746e)
Location: arch/x86/include/asm/atomic.h:175
Inline: True
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
In arch/x86/events/core.c (ffffffff810059f0)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81030bf3)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/smp.c (ffffffff81050b69)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81052a18)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81053564)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff8119e68f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/cred.c (ffffffff810a5cbe)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/smpboot.c (ffffffff810a78b2)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/sched/fair.c (ffffffff810be0a8)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff8189be00)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
```
In kernel/locking/spinlock.c (ffffffff8189ec6f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/osq_lock.c (ffffffff810ced86)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/lglock.c (ffffffff810ceed6)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/locking/lglock.c:lg_global_lock
  - kernel/locking/lglock.c:lg_double_lock
  - kernel/locking/lglock.c:lg_double_lock
  - kernel/locking/lglock.c:lg_local_lock_cpu
  - kernel/locking/lglock.c:lg_local_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810cf420)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810d0846)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810d45f5)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810da41e)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/printk/nmi.c (ffffffff810df22c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/printk/nmi.c:__printk_nmi_flush
```
```
In kernel/irq/chip.c (ffffffff810e4494)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/futex.c (ffffffff811077ca)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff8110cbd3)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
  - kernel/module.c:SyS_delete_module
```
```
In kernel/kexec_core.c (ffffffff811154bc)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup.c (ffffffff8111b55f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8113bc52)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff81148487)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8114f435)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_start
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/trace/trace.c (ffffffff811557f4)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81161c04)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8116269d)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/events/core.c (ffffffff811907c7)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff81197dc0)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff8119a24f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff8119d53f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In mm/filemap.c (ffffffff811a1753)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/oom_kill.c (ffffffff811a4a94)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task
```
```
In mm/swap.c (ffffffff811b3a68)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff811b89c7)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811bf5cf)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/mmap.c (ffffffff811e398f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff811e8edf)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff811f3885)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff811f6b6c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff811fe159)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812035ce)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff818940e5)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In mm/migrate.c (ffffffff81211ab0)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81217fbe)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff8121ada1)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8121db1a)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81225fa4)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff8122db91)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/open.c (ffffffff8122fde9)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff81236719)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff81238c24)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812423bd)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff81272001)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/userfaultfd.c (ffffffff81282bde)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81283f6d)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/aio.c:get_reqs_available
```
```
In fs/posix_acl.c (ffffffff8129955f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff812a387e)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff812a5fd7)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/proc/base.c (ffffffff812a7484)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_net.c (ffffffff812b35af)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_net
```
```
In fs/kernfs/mount.c (ffffffff812b5ed0)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/kernfs/dir.c (ffffffff812b7a9e)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
```
```
In fs/ext4/balloc.c (ffffffff812bd25c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812c316c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/super.c (ffffffff812ec04a)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/mballoc.c (ffffffff81305564)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In ipc/util.c (ffffffff81359823)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/keyring.c (ffffffff81366690)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff813acd04)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_abi_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/context.c (ffffffff813b059c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff813b7d4b)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff813bad3d)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff813bd06d)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813be38d)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/resource.c (ffffffff813c1ffa)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813c371e)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff813c8b5d)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff813ca28e)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff813cc050)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813ceaf7)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq-tag.c (ffffffff8140aef1)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_clear_tag
  - block/blk-mq-tag.c:bt_clear_tag
  - block/blk-mq-tag.c:bt_get
```
```
In lib/dec_and_lock.c (ffffffff8142f51a)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In lib/dump_stack.c (ffffffff8142f570)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/kobject.c (ffffffff81431b6d)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
```
```
In drivers/phy/phy-core.c (ffffffff814643a0)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81486646)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/rapidio/rio.c (ffffffff814a73f2)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/acpi/apei/ghes.c (ffffffff81505fe2)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8154eb13)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff8155307c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
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
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/hw_random/core.c (ffffffff8156d7c8)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff81583246)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff8159072a)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/power/runtime.c (ffffffff815a9d7e)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815fa545)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff815fc112)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/scsi/scsi_scan.c (ffffffff8160b755)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/usb/core/hcd.c (ffffffff8166bf31)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81674106)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81680578)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816c2640)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/thermal/thermal_core.c (ffffffff816e8242)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81716f39)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff8172cc17)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8172d71e)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In net/core/sock.c (ffffffff817671c5)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff8176ecd4)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/neighbour.c (ffffffff8178dfaa)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/fib_rules.c (ffffffff817a5fa0)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/ipv4/route.c (ffffffff817c317b)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff817c442b)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cc301)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ce6fb)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cfd6c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff817d7a7f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ec154)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec820)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff817f8029)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181af38)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/ipv6/addrlabel.c (ffffffff81840961)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff8184337e)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81847875)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/udp.c (ffffffff818507b7)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_queue_rcv_skb
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff8185428f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860cd2)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81865158)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/calipso.c (ffffffff818702df)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8187357c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/klist.c (ffffffff81890f2e)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
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
In arch/x86/events/core.c (ffffffff81006298)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810307d3)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8103822f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103dd96)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051c3a)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff8105341a)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055337)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056254)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In arch/x86/kernel/hpet.c (ffffffff810658a2)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In kernel/panic.c (ffffffff811ae0bb)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/cred.c (ffffffff810ab91e)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/smpboot.c (ffffffff810ad562)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810ad9fe)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810b7046)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_show_task
```
```
In kernel/sched/fair.c (ffffffff810c35a6)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810d524f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff818d412f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/osq_lock.c (ffffffff810d59c6)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810d5e10)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810d72b6)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810db1a4)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810e0eee)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/printk/nmi.c (ffffffff810e57f4)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/printk/nmi.c:__printk_nmi_flush
```
```
In kernel/irq/chip.c (ffffffff810ead34)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/futex.c (ffffffff8110ef95)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff81114613)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
  - kernel/module.c:SyS_delete_module
```
```
In kernel/kexec_core.c (ffffffff8111cbdc)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/cgroup.c (ffffffff8112389f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81145a02)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff81152337)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811595c8)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_read_start
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/trace/trace.c (ffffffff8115fcc4)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116c764)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8116d9dd)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/events/core.c (ffffffff811a36d4)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff811a77a0)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff811a99bf)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff811acf5f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In mm/filemap.c (ffffffff811b15c3)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/oom_kill.c (ffffffff811b4c17)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/swap.c (ffffffff811c40f8)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff811c8ff7)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811cfc05)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/mmap.c (ffffffff811f396f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff811fa3bf)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812043b8)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81207520)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff8120ec29)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812155d8)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff818c87e1)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In mm/migrate.c (ffffffff81223c88)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8122a55e)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8122c5a0)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff812300fa)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81238584)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812400d6)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/open.c (ffffffff81242389)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812493c9)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff8124b8d4)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff81255292)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff812855a1)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/userfaultfd.c (ffffffff812966fe)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81297bdd)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/aio.c:get_reqs_available
```
```
In fs/posix_acl.c (ffffffff812ae07f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff812b926e)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff812bb8f7)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/proc/base.c (ffffffff812bcdb4)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_net.c (ffffffff812c8dff)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_net
```
```
In fs/kernfs/mount.c (ffffffff812cb760)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/kernfs/dir.c (ffffffff812cd237)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
```
```
In fs/ext4/balloc.c (ffffffff812d28ac)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812d875c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/super.c (ffffffff8130200a)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/mballoc.c (ffffffff8131b52b)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In ipc/util.c (ffffffff8136fd03)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/keyring.c (ffffffff8137ceb0)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff813c3b11)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_abi_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/context.c (ffffffff813c771c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff813cf167)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff813d2105)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff813d449d)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813d580d)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/resource.c (ffffffff813d949a)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813dacae)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff813e0175)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff813e190e)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff813e36d0)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813e6177)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq-tag.c (ffffffff81425a88)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In block/bsg-lib.c (ffffffff81437da3)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In block/blk-wbt.c (ffffffff8144aba3)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
```
```
In lib/dec_and_lock.c (ffffffff8144b74a)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In lib/dump_stack.c (ffffffff8144b7a0)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/kobject.c (ffffffff8144dddd)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
```
```
In lib/syscall.c (ffffffff81479f85)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/sbitmap.c (ffffffff8148248c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/phy/phy-core.c (ffffffff814836a0)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814a7e06)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/rapidio/rio.c (ffffffff814c9502)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/acpi/apei/ghes.c (ffffffff8152a1e2)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8157b393)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff8157fb71)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
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
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/hw_random/core.c (ffffffff81599f2c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815b0556)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff815bdfbb)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff815c808c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff815d85c5)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81628815)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff8162ad1f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
```
```
In drivers/scsi/hosts.c (ffffffff8162f5e7)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff8163aff5)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/usb/core/hcd.c (ffffffff81699c31)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff816a1d96)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816ae2a8)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816f0600)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/thermal/thermal_core.c (ffffffff81716baf)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81748d19)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff8175ebe5)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff817606de)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In net/core/sock.c (ffffffff81794245)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff8179b960)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/dev.c (ffffffff817ac611)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In net/core/neighbour.c (ffffffff817bb95a)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/fib_rules.c (ffffffff817d4a79)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/ipv4/route.c (ffffffff817f1903)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ip_idents_reserve
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff817f3f4b)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fbe6a)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fe50b)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ffb5c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81807a1f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181b442)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181d110)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81828ec9)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184c7f8)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854323)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81859312)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/addrlabel.c (ffffffff818725e1)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff818750ee)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff818796b5)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/udp.c (ffffffff81882606)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81885fb1)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188f512)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81897828)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/calipso.c (ffffffff818a324f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7bec)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/klist.c (ffffffff818c56be)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
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
In arch/x86/kernel/dumpstack.c (ffffffff8102eaa3)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105175a)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81052fab)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81054c5a)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81055b3c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In arch/x86/kernel/hpet.c (ffffffff81064c92)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In kernel/panic.c (ffffffff810847ea)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/kmod.c (ffffffff8109c5a7)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/smpboot.c (ffffffff810aa142)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810aa5da)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/locking/spinlock.c (ffffffff8190b2bf)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/osq_lock.c (ffffffff810d4946)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810d4d92)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810d62f6)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff810e4c5c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff810f5c5f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/module.c (ffffffff81115220)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/module.c:module_put
```
```
In kernel/kexec_core.c (ffffffff8111e48c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/trace_clock.c (ffffffff81154917)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8115eeda)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/trace/trace.c (ffffffff8116315c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116fb08)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff81170d3b)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/events/core.c (ffffffff811a60e3)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In kernel/jump_label.c (ffffffff811b440f)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In mm/vmscan.c (ffffffff811d2d7b)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811d9344)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/mmap.c (ffffffff811fe994)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/migrate.c (ffffffff81230bb2)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81235cf7)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81238e2c)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/open.c (ffffffff8124d8cd)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff81254cb1)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
```
```
In fs/exec.c (ffffffff812579f9)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812612da)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff812930b2)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/aio.c (ffffffff812a5a0d)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/aio.c:get_reqs_available
```
```
In fs/proc/inode.c (ffffffff812c8e37)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff812da4d2)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In block/blk-mq.c (ffffffff814319b4)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff81433b30)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-wbt.c (ffffffff81458e24)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
```
```
In lib/sbitmap.c (ffffffff8148b8d8)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
  - lib/sbitmap.c:sbitmap_queue_clear
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/rapidio/rio.c (ffffffff814d5362)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c5757)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff8172eafc)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In net/core/dev.c (ffffffff817cadb1)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
```
```
In net/ipv4/route.c (ffffffff8180ecf1)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff8189f025)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In lib/dump_stack.c (ffffffff818ebf46)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/nmi_backtrace.c (ffffffff818efd19)
Location: arch/x86/include/asm/atomic.h:184
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
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
In arch/x86/kernel/dumpstack.c (ffffffff81030973)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81055400)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81056cdb)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81058a1a)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81059672)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In arch/x86/kernel/hpet.c (ffffffff81068e23)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
```
```
In kernel/panic.c (ffffffff8108b2a3)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810b099f)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810b0e3a)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/kmod.c (ffffffff810b1119)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/rt.c (ffffffff810caa6c)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/locking/spinlock.c (ffffffff8199566f)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/osq_lock.c (ffffffff810dc8c6)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810dcb55)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810de2a6)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff810ecef8)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff810ffa5f)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/module.c (ffffffff811207c0)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/module.c:module_put
```
```
In kernel/kexec_core.c (ffffffff81129bd6)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/trace_clock.c (ffffffff81161137)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8116922a)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/trace/trace.c (ffffffff8117011c)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117cc1e)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8117defb)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/events/core.c (ffffffff811b9cd9)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
```
```
In kernel/jump_label.c (ffffffff811c8278)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
```
In mm/vmscan.c (ffffffff811e7fe2)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811ee624)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/mmap.c (ffffffff81216f4a)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/migrate.c (ffffffff8124e938)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81254a5c)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8125752a)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/open.c (ffffffff8126f933)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff81276e41)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
```
```
In fs/exec.c (ffffffff81279cc9)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff81283a0d)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff812b5eb3)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/aio.c (ffffffff812c8f2d)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - fs/aio.c:get_reqs_available
```
```
In fs/proc/inode.c (ffffffff812ed6a7)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff812fed32)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
```
```
In block/blk-mq.c (ffffffff8145d629)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff8145f7f0)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-wbt.c (ffffffff81484b7f)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
```
```
In lib/sbitmap.c (ffffffff814c79f8)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear
  - lib/sbitmap.c:sbitmap_queue_clear
  - lib/sbitmap.c:sbitmap_queue_clear
```
```
In drivers/rapidio/rio.c (ffffffff81515812)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff8162a0b8)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/thermal/thermal_core.c (ffffffff817a0130)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
```
```
In net/core/dev.c (ffffffff818445f5)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
```
```
In net/ipv4/route.c (ffffffff8188e2b1)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff819216f5)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81971f36)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In lib/nmi_backtrace.c (ffffffff81976159)
Location: arch/x86/include/asm/atomic.h:185
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
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
In arch/x86/kernel/dumpstack.c (ffffffff81031b83)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105828c)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81059b3a)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105b987)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105c941)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In arch/x86/kernel/hpet.c (ffffffff8106b5c6)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
```
```
In kernel/panic.c (ffffffff8108ea1d)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810b77b7)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810b7c4a)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/kmod.c (ffffffff810b7f1e)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/rt.c (ffffffff810d3cdb)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/locking/spinlock.c (ffffffff819f1b9f)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/osq_lock.c (ffffffff810e4f12)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810e5349)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff810e6996)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff810f5312)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff81107d74)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/module.c (ffffffff8112ed70)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81137b3a)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/trace_clock.c (ffffffff81170067)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8117b3d0)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/trace/trace.c (ffffffff8117f89c)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118bc84)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8118d01b)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/events/core.c (ffffffff811d909b)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/jump_label.c (ffffffff811e867a)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
```
In mm/vmscan.c (ffffffff81209488)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/mmap.c (ffffffff81237e51)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/migrate.c (ffffffff8127274a)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81278878)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8127b458)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff8129418a)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff81295300)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff8129d733)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
```
```
In fs/exec.c (ffffffff812a08a7)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812aaba0)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff812ddb13)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/aio.c (ffffffff812f201d)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - fs/aio.c:get_reqs_available
```
```
In fs/proc/inode.c (ffffffff8131a582)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff8132c182)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
```
```
In block/blk-mq.c (ffffffff81490d26)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff8149318e)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-wbt.c (ffffffff814b994f)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
```
```
In lib/sbitmap.c (ffffffff814f86bd)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff8154c342)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff81664dc4)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/thermal/thermal_core.c (ffffffff817e7ad3)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff8188e375)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
```
```
In net/ipv4/route.c (ffffffff818e1fd4)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff8197996b)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff819ce35f)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105df2a)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff8105f7ba)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810625c1)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff81096d5d)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810c08b7)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810c0bc2)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810dd97b)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/locking/osq_lock.c (ffffffff810f04f3)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810f0929)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff810f1fa7)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff81100ab2)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff81113294)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff81143355)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff81185385)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/jump_label.c (ffffffff811f933f)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff8121c16a)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff81286d27)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8128cf2d)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8128ffa3)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/aio.c (ffffffff813076bd)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff814a9ee3)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814ad114)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff814bd7a3)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In lib/sbitmap.c (ffffffff8150c944)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff815636d2)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff816833c4)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/thermal/thermal_core.c (ffffffff81813376)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff818af285)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
```
```
In net/ipv4/route.c (ffffffff8190ee74)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff819af53b)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81a07818)
Location: include/asm-generic/atomic-instrumented.h:55
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8106132a)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81062c3f)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81065c36)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff8109b2d9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810c69ac)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810c6cc9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810e496b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (ffffffff810f6535)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/locking/osq_lock.c (ffffffff810f8b72)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810f8c49)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff810fa407)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff8110925e)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff8111ce64)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff8114e69c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff81192521)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/jump_label.c (ffffffff812112bf)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff8122bec1)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff81292bd2)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812a12b9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a7bc2)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812aae26)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/aio.c (ffffffff81328cb1)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff814d7e71)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814db3b9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff814ebe51)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In lib/sbitmap.c (ffffffff8153b04b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff81593a72)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff816ba979)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/thermal/thermal_core.c (ffffffff818554b1)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff818fb0c2)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In net/ipv4/route.c (ffffffff81970985)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1d75b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81a771a8)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061b9a)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81063313)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066266)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff810a17f9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810cfa8c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810cfd99)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810efb3b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (ffffffff811022d5)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/locking/osq_lock.c (ffffffff81104982)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff81104a59)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff811061e7)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff8111563e)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff81129344)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff8115a3ac)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff8119e1d1)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/jump_label.c (ffffffff8121ef6f)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In mm/vmscan.c (ffffffff81239d8b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff812a2952)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812b26d9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b908b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812bc54f)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff8133ba61)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff814f1203)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814f47e9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff81505211)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff8150fcc9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff8155be6b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff815b4cf2)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff816dd7c8)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/vfio/vfio.c (ffffffff817d1455)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff81887db9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff8192d212)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In net/ipv4/route.c (ffffffff819a7385)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5438b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81aae588)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81067aba)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81069336)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106cb66)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff810a8612)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810d9989)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810d9d92)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/psi.c (ffffffff8110ca25)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In kernel/locking/qspinlock.c (ffffffff8110fb85)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In kernel/printk/printk_safe.c (ffffffff81120f47)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff81137d2a)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff8116b17c)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff811b4a81)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/irq_work.c (ffffffff811f7524)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff8124adbf)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff81266247)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff812d70d2)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812e7c79)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812edc5d)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812f1a6c)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/page_reporting.c (ffffffff8130d512)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/aio.c (ffffffff813756af)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff81551a24)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff81554fb7)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff81565ae1)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff81570d1d)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff815e5960)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In lib/dump_stack.c (ffffffff815e82e5)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In drivers/rapidio/rio.c (ffffffff8165dda2)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff817945a4)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/vfio/vfio.c (ffffffff8189d5be)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff81956ca4)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff81a00873)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4c31b)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_update_sernum
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810698ba)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff8106af56)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106e316)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff81bdb1ca)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810d4b39)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810d4f42)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/psi.c (ffffffff8110a8ce)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
```
```
In kernel/locking/qspinlock.c (ffffffff8110cd45)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In kernel/printk/printk_safe.c (ffffffff8111bba7)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff811335ca)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff811678bc)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff811b2331)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/irq_work.c (ffffffff811f6093)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff812551af)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff81270c41)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff812f3059)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f9332)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812fdff3)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/page_reporting.c (ffffffff81319462)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/aio.c (ffffffff8138358c)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff8156db78)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff8157166c)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff81580a61)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff8158bd1b)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff81609d20)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In lib/dump_stack.c (ffffffff81bf49e5)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In drivers/rapidio/rio.c (ffffffff8167f4c2)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff818463fe)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff818ac1ee)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff8195ae6e)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff81a00c83)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5af5b)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_update_sernum
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8106a30a)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff8106bb53)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106ed35)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff81bcd2bc)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810d6759)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810d6c22)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/psi.c (ffffffff8110c2bd)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
```
```
In kernel/locking/qspinlock.c (ffffffff8110ea35)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In kernel/printk/printk_safe.c (ffffffff8111bffe)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff811340ea)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff8116864c)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff811b2e31)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/irq_work.c (ffffffff811f6f83)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff812596af)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff8127572a)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/migrate.c (ffffffff812f93e8)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ff8ff)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81304be0)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/page_reporting.c (ffffffff8131f611)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/aio.c (ffffffff8138cab8)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff81575658)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff8157969c)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff815885d1)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff81592bdb)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff815ecf00)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In lib/dump_stack.c (ffffffff81be68dd)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
```
In drivers/rapidio/rio.c (ffffffff81662d52)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff818296ce)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff8188f31a)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff8193fc23)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In net/core/dev.c (ffffffff819e7453)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b491db)
Location: include/asm-generic/atomic-instrumented.h:652
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_update_sernum
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81074a8a)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81076623)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107a6da)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff81ca3a5c)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810e9c23)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/sched/psi.c (ffffffff8112b09d)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
```
```
In kernel/locking/qspinlock.c (ffffffff8112e262)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8118e38c)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff811dcd61)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/irq_work.c (ffffffff81228553)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff8129537b)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff812b32d8)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/hugetlb.c (ffffffff8131ca0b)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/migrate.c (ffffffff813429f9)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8134953b)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8134e970)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/page_reporting.c (ffffffff8136ca48)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/aio.c (ffffffff813da108)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In security/integrity/ima/ima_policy.c (ffffffff8159efef)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy_flags
```
```
In block/blk-mq.c (ffffffff815da358)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff815de8b5)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff815ee271)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff815fa079)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff81659e20)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff816d5c2f)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b50be)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff819228fa)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff819e4473)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In net/core/dev.c (ffffffff81a97e43)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81c104eb)
Location: include/linux/atomic/atomic-instrumented.h:473
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_update_sernum
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8108325a)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_nmi_unknown
```
```
In arch/x86/kernel/smp.c (ffffffff81085166)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81088f13)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff81e53231)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/smpboot.c (ffffffff811048b3)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/sched/build_utility.c (ffffffff81143cc0)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_poll_worker
```
```
In kernel/locking/qspinlock.c (ffffffff8114f382)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
```
```
In kernel/kexec_core.c (ffffffff811bd91c)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff81213231)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/irq_work.c (ffffffff812695d3)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff812eb148)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
  - kernel/jump_label.c:static_key_slow_inc_cpuslocked
```
```
In mm/vmscan.c (ffffffff8130e63a)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/rmap.c (ffffffff8135db1a)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
```
```
In mm/hugetlb.c (ffffffff8138839e)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_page
```
```
In mm/migrate.c (ffffffff813b4eff)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff813bfacd)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff813c50f2)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/page_reporting.c (ffffffff813eac83)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/aio.c (ffffffff81460a26)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In security/integrity/ima/ima_policy.c (ffffffff81644964)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy_flags
```
```
In block/blk-mq.c (ffffffff81688419)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff8168cb14)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff8169ea61)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff816ac287)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff817724e1)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817abe95)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/rapidio/rio.c (ffffffff817fde62)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a0008c)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81b4970b)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In net/core/dev.c (ffffffff81c0f813)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81dab74b)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_update_sernum
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81095dda)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_nmi_unknown
```
```
In arch/x86/kernel/smp.c (ffffffff810985d6)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109cb8b)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff810ea3a6)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/sched/build_utility.c (ffffffff8116f629)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_poll_worker
```
```
In kernel/locking/qspinlock.c (ffffffff820d63a2)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/kexec_core.c (ffffffff811ff94c)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff8125ca81)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/irq_work.c (ffffffff812be473)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff813551a8)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
```
In mm/vmscan.c (ffffffff81380608)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/rmap.c (ffffffff813d899d)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
```
```
In mm/hugetlb.c (ffffffff81405929)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_folio
```
```
In mm/migrate.c (ffffffff8143409e)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81441eec)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81449a14)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/page_reporting.c (ffffffff81472e33)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/mbcache.c (ffffffff81514ab6)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fcde4)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy_flags
```
```
In block/blk-mq.c (ffffffff817468d1)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff8174b309)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In io_uring/poll.c (ffffffff8179d491)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c47d5)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/rapidio/rio.c (ffffffff8192b032)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7e60c)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81ce0cc9)
Location: include/linux/atomic/atomic-instrumented.h:500
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81098c9a)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_nmi_unknown
```
```
In arch/x86/kernel/smp.c (ffffffff8109b873)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In kernel/panic.c (ffffffff810f5fb2)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/sched/build_utility.c (ffffffff81180f08)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:psi_rtpoll_worker
```
```
In kernel/locking/qspinlock.c (ffffffff82159782)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/kexec_core.c (ffffffff81214dbc)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/irq_work.c (ffffffff812e50b3)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff81386698)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
```
In mm/vmscan.c (ffffffff813b1f37)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/rmap.c (ffffffff8140bd76)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - mm/rmap.c:flush_tlb_batched_pending
```
```
In mm/hugetlb.c (ffffffff81438e2f)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_folio
```
```
In mm/migrate.c (ffffffff814699de)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81477838)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/page_reporting.c (ffffffff814a75a3)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/mbcache.c (ffffffff8154c4c5)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
```
```
In security/integrity/ima/ima_policy.c (ffffffff81736e14)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy_flags
```
```
In block/blk-mq.c (ffffffff81783b31)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff81787a29)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In io_uring/poll.c (ffffffff817de6c1)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff819078a5)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/rapidio/rio.c (ffffffff8196f2a2)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd23f2)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81d4901c)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
In arch/x86/kernel/smp.c (ffffffff810a2e13)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In kernel/sched/build_utility.c (ffffffff8118ec58)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:psi_rtpoll_worker
```
```
In kernel/locking/qspinlock.c (ffffffff8223d002)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/irq_work.c (ffffffff81303163)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/jump_label.c (ffffffff813afb58)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
```
In mm/vmscan.c (ffffffff813dafe8)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/rmap.c (ffffffff81438626)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - mm/rmap.c:flush_tlb_batched_pending
```
```
In mm/hugetlb.c (ffffffff8391ad11)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:hugetlb_folio_init_tail_vmemmap
  - mm/hugetlb.c:__prep_compound_gigantic_folio
```
```
In mm/migrate.c (ffffffff81498925)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a6fbb)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/page_reporting.c (ffffffff814d85d2)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/mbcache.c (ffffffff815822f5)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
```
```
In security/integrity/ima/ima_policy.c (ffffffff817778d4)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy_flags
```
```
In block/blk-mq.c (ffffffff817c5eb4)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
```
```
In block/blk-mq-tag.c (ffffffff817ca0f9)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In io_uring/poll.c (ffffffff81822a91)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - io_uring/poll.c:__io_arm_poll_handler
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950d2c)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
```
```
In drivers/rapidio/rio.c (ffffffff819b9192)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c27062)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81dff4bd)
Location: include/linux/atomic/atomic-instrumented.h:1191
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
In kernel/panic.c (ffff8000100f69d0)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/cred.c (ffff80001012cbb8)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/smpboot.c (ffff80001012fc88)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffff800010130378)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/kmod.c (ffff80001013077c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/psi.c (ffff800010166fb4)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/locking/mutex.c (ffff800010168854)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/printk/printk_safe.c (ffff800010176a6c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/irq/chip.c (ffff800010180128)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/rcu/tree.c (ffff800010190950)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/module.c (ffff8000101c27bc)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:__arm64_sys_delete_module
```
```
In kernel/kexec_core.c (ffff8000101c99d0)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/debug/kdb/kdb_main.c (ffff800010200390)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/ring_buffer.c (ffff8000102176bc)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/bpf/syscall.c (ffff800010264458)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/events/core.c (ffff800010297658)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_free_event
```
```
In kernel/events/uprobes.c (ffff8000102a650c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffff8000102ab290)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_disable_cpuslocked
```
```
In mm/filemap.c (ffff8000102afe18)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffff8000102c2d80)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffff8000102c9b98)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/gup.c (ffff8000102f1190)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffff8000103036b4)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffff80001030b004)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffff8000103265e8)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffff800010335fdc)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffff800010342380)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffff800010352f10)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffff800010359b30)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffff80001035d854)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memcontrol.c (ffff800010363f74)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffff80001036e4d8)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffff80001037911c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffff80001037b0f0)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In mm/memfd.c (ffff80001037c578)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffff80001037dd38)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffff800010386f54)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffff80001038c84c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffff8000103982bc)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/userfaultfd.c (ffff8000103f890c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/aio.c (ffff8000103faba0)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In fs/io_uring.c (ffff800010406318)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/verity/enable.c (ffff800010411a40)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/proc/task_mmu.c (ffff80001043a5f4)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffff80001043b7ec)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/proc/base.c (ffff800010440558)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_sysctl.c (ffff80001044aa48)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/dir.c (ffff8000104530d0)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/ext4/balloc.c (ffff800010460a2c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffff800010473db4)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In fs/ext4/mballoc.c (ffff800010495384)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In fs/ext4/super.c (ffff8000104bd038)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In block/blk-mq.c (ffff8000105f0620)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffff8000105f45c4)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffff800010607238)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffff8000106154ec)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffff80001066a318)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/irqchip/irq-mvebu-icu.c (ffff800010679828)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_write_msg
```
```
In drivers/phy/phy-core.c (ffff8000106879d0)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffff8000106ec540)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/rapidio/rio.c (ffff80001073cdbc)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/amba/bus.c (ffff8000107b9548)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/tty/hvc/hvc_console.c (ffff800010879c60)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffff80001087e29c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
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
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff8000108915f4)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_remove
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892d7c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
```
```
In drivers/tty/serdev/core.c (ffff8000108a9ff0)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/iommu/iova.c (ffff8000108cdc8c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/base/core.c (ffff8000108e6610)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffff8000108fe0d4)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/power/wakeup.c (ffff800010905080)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/scsi/hosts.c (ffff80001096fb7c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffff8000109c95f8)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cdac0)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/loopback.c (ffff8000109d0270)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e67c8)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/cdrom/cdrom.c (ffff800010a10188)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In drivers/usb/core/hcd.c (ffff800010a1c360)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffff800010a25934)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a37144)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a90f34)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010aba1fc)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba664)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abca5c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
```
In drivers/thermal/thermal_core.c (ffff800010ad583c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In drivers/cpufreq/cpufreq_governor.c (ffff800010b25bf8)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a40c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b21c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/mmc/core/block.c (ffff800010b41748)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/firmware/efi/efi.c (ffff800010d9f398)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e9e8)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In drivers/perf/arm-cci.c (ffff800010b91ba0)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_event_init
```
```
In net/core/sock.c (ffff800010bac17c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb479c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffff800010bd1ad0)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffff800010be761c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffff800010c01104)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffff800010c22154)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffff800010c55dfc)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffff800010c5bf94)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/ip_options.c (ffff800010c60eec)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffff800010c62364)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffff800010c6686c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8bb2c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f974)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c940e4)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffff800010c9e318)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffff800010ca1a90)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In net/ipv4/icmp.c (ffff800010ca3d44)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010ccb4a0)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0f60)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffff800010ceb0e0)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec084)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffff800010cfc5e8)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffff800010d11200)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/ip6_fib.c (ffff800010d18e94)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_sernum
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d371b4)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3fc8c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffff800010d43e38)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffff800010d4b190)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffff800010d50e1c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In lib/dec_and_lock.c (ffff800010d84724)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In lib/dump_stack.c (ffff800010d84b88)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In kernel/panic.c (c03549d4)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (c037f7e4)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (c037fd0c)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
  - kernel/ucount.c:inc_ucount
```
```
In kernel/kmod.c (c0380000)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/psi.c (c03b2f5c)
Location: include/linux/atomic-fallback.h:893
Inline: True
```
```
In kernel/locking/rwsem.c (c0e9d44c)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/printk/printk_safe.c (c03c89f4)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (c03de4a8)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/module.c (c0408210)
Location: include/linux/atomic-fallback.h:893
Inline: True
```
```
In kernel/kexec_core.c (c04109f8)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (c0455e9c)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/events/core.c (c04c78e4)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event
```
```
In kernel/events/ring_buffer.c (c04d22c8)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/vmscan.c (c04f5000)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/mmap.c (c0521eac)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/ksm.c (c05480e0)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (c0552654)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memfd.c (c0566eb0)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (c0567860)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/exec.c (c0574404)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (c057e8b4)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/nsfs.c (c05ae5a8)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In fs/aio.c (c05cdf3c)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In fs/io_uring.c (c05d1e9c)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - fs/io_uring.c:io_account_mem
```
```
In fs/verity/enable.c (c05de114)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/proc/inode.c (c0601ce0)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (c0615cf4)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
```
```
In block/blk-mq.c (c079c658)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (c07a0220)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (c07b2490)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (c07be66c)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (c0811c04)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (c08c0dcc)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/tty/tty_ldsem.c (c0966ab0)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read_trylock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/base/power/wakeup.c (c09eeeb4)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/thermal/thermal_core.c (c0bb4b1c)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/skbuff.c (c0cd0034)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/ipv4/route.c (c0d679fc)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (c0e1dc7c)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_new_sernum
```
```
In net/xdp/xdp_umem.c (c0e7b95c)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dump_stack.c (c0e7fe5c)
Location: include/linux/atomic-fallback.h:893
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffe0000c25a6)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/ucount.c (ffffffe0000e3824)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/psi.c (ffffffe00010916a)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
```
```
In kernel/printk/printk_safe.c (ffffffe000111cd0)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffe000123ede)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/trace/ring_buffer.c (ffffffe000176996)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/events/core.c (ffffffe0001ca116)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
```
```
In mm/vmscan.c (ffffffe0001e9b6c)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/mmap.c (ffffffe0002101fa)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/ksm.c (ffffffe0002365a8)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffe00023f912)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memfd.c (ffffffe000252916)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffe0002538ec)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/exec.c (ffffffe00025d0d8)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffe000265eda)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/aio.c (ffffffe0002a90ec)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In fs/verity/enable.c (ffffffe0002b9c2c)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/proc/inode.c (ffffffe0002d3bbe)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffe0002e5796)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_get_active
```
```
In block/blk-mq.c (ffffffe00042f4ca)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffe0004325aa)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffe000441f36)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffe00044ae4a)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffe000494294)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffe0004ecbac)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/thermal/thermal_core.c (ffffffe0006d08e6)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
```
In net/ipv4/route.c (ffffffe0007c0fe6)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffe00085d380)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffe0008aee54)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8106171a)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81062e03)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81065d56)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff8109b119)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810c9e0c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810ca119)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810e942b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (ffffffff810fb5e5)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/locking/osq_lock.c (ffffffff810fdc92)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810fdd69)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff810ff4f7)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff8110dc1e)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff81121924)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff811529cc)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff811967f1)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/jump_label.c (ffffffff812175bf)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In mm/vmscan.c (ffffffff812323db)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff8129af32)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812aacb9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b166b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812b4b2f)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81334041)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff814e97e3)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814ecdc9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff814fd7f1)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff815082a9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff8155445b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff815a8f62)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff816a3218)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/thermal/thermal_core.c (ffffffff8182dc39)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff818cd212)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In net/ipv4/route.c (ffffffff819471f5)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff819f3a1b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81a4d3d8)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051b8a)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff810530b3)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810560d6)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff81089b53)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810b862c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810b8933)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810d8efb)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (ffffffff810eb805)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/locking/osq_lock.c (ffffffff810ede92)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810edf69)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff810ef6e7)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff810fe97e)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff81114004)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff81145cac)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff81189901)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/jump_label.c (ffffffff8120a31f)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In mm/vmscan.c (ffffffff81225487)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff8128caf2)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff8129c5fc)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a2a3b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812a5b81)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81323e5e)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff814d9d53)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814dd319)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff814edd01)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff814f8759)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff815446db)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff81598102)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff81680c08)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/vfio/vfio.c (ffffffff8177b505)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff817f52c9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff818872a2)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In net/ipv4/route.c (ffffffff81900ce5)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff819b07db)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81a0a4fa)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061b4a)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff810632b3)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066206)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff8109b0c9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810c933c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810c9649)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810e606b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (ffffffff810f87a5)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/locking/osq_lock.c (ffffffff810fae52)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810faf29)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff810fc6b7)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff8110bb0e)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff8111f814)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff8115087c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff811945c1)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/jump_label.c (ffffffff8121535f)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In mm/vmscan.c (ffffffff8123017b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff81298d42)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812a8ac9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812af47b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812b293f)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81331b11)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff814e5873)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff814e8e59)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff814f9881)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff81504339)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff8155019b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff815a94f2)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff816d1488)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/vfio/vfio.c (ffffffff817c62d5)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff8187d269)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff8191e212)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In net/ipv4/route.c (ffffffff819b19c5)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5e49b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81ab97c8)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810630fa)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81064873)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810677e6)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff810a2d40)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/smpboot.c (ffffffff810d189c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/ucount.c (ffffffff810d1b97)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/rt.c (ffffffff810efd6b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/psi.c (ffffffff811038e5)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/locking/osq_lock.c (ffffffff81106022)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff811060f9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In kernel/locking/qrwlock.c (ffffffff811078e7)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/printk/printk_safe.c (ffffffff8111701e)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_log_store
```
```
In kernel/rcu/tree.c (ffffffff8112b964)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_eqs_special_set
```
```
In kernel/kexec_core.c (ffffffff8115d69c)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff811a21a1)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/jump_label.c (ffffffff8122434f)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In mm/vmscan.c (ffffffff8123f5c4)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/ksm.c (ffffffff812a8b22)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
```
```
In mm/migrate.c (ffffffff812b8de9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812bf7cb)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812c2b78)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff81344931)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-mq.c (ffffffff814fe7d9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
```
In block/blk-mq-tag.c (ffffffff81501df9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-rq-qos.c (ffffffff815128e1)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff8151d8e9)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff81569fdb)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/rapidio/rio.c (ffffffff815c22c2)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_unregister_mport
```
```
In drivers/iommu/iova.c (ffffffff816ebd98)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In drivers/vfio/vfio.c (ffffffff817e0575)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/thermal/thermal_core.c (ffffffff81898c99)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
```
```
In net/core/dev.c (ffffffff8193f8a2)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
```
```
In net/ipv4/route.c (ffffffff819bb065)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6aa4b)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_update_sernum_upto_root
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In lib/dump_stack.c (ffffffff81ac5c18)
Location: include/asm-generic/atomic-instrumented.h:651
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
```
</details>
</li>
</ul>

## Differences
