# Function: <code>atomic_try_cmpxchg</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006048)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/process.c (ffffffff810363a4)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103be22)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
```
```
In kernel/cred.c (ffffffff810a851e)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b3376)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810bdd70)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810d423f)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff810da2c7)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810e0053)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff810ea40c)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/futex.c (ffffffff81110167)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff81115bd5)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:SyS_delete_module
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811477b2)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/bpf/syscall.c (ffffffff811926a2)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811aad3f)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff811aef40)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff811b104a)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff811b785e)
Location: arch/x86/include/asm/atomic.h:190
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
In mm/oom_kill.c (ffffffff811bc5dc)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/swap.c (ffffffff811cc4ea)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff811d1b31)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff811f0ba0)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/rmap.c (ffffffff812050af)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8120fb22)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81212c39)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff8121a4d9)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81220bf8)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff818ffde1)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
```
```
In mm/migrate.c (ffffffff8122f395)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812361b8)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff8123b296)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812440c4)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff8124bf96)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff81254073)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/notify/mark.c (ffffffff812992a3)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark_safe
```
```
In fs/userfaultfd.c (ffffffff812a3ea5)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/posix_acl.c (ffffffff812bb5df)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff812c6329)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812cccc2)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_sysctl.c (ffffffff812d4419)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff812d6554)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
```
```
In fs/kernfs/mount.c (ffffffff812d8bb0)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/configfs/item.c (ffffffff812e1c38)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff812e3f70)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812f6c9d)
Location: arch/x86/include/asm/atomic.h:190
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
In fs/ext4/mballoc.c (ffffffff813130ff)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
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
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/super.c (ffffffff81337053)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In ipc/util.c (ffffffff81383193)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8138f41f)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff81390c4a)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff813d9f84)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/context.c (ffffffff813dd003)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff813e2f17)
Location: arch/x86/include/asm/atomic.h:190
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
In security/apparmor/policy.c (ffffffff813e493d)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff813e7350)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813e9c8c)
Location: arch/x86/include/asm/atomic.h:190
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
In security/apparmor/resource.c (ffffffff813ea7c7)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813ebda6)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff813ef638)
Location: arch/x86/include/asm/atomic.h:190
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
In security/apparmor/mount.c (ffffffff813f06df)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff813f1bb6)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813f3770)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/bsg-lib.c (ffffffff81445563)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff8146c4c1)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff8148328e)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff8148d928)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814b1db6)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153c9b2)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8158fa43)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff815938b0)
Location: arch/x86/include/asm/atomic.h:190
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
In drivers/char/hw_random/core.c (ffffffff815adf0c)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff815d3663)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff815dcd23)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff815ecb95)
Location: arch/x86/include/asm/atomic.h:190
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
In drivers/dma-buf/dma-buf.c (ffffffff8163e478)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff81640425)
Location: arch/x86/include/asm/atomic.h:190
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
In drivers/scsi/hosts.c (ffffffff816446b2)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff8164f6d2)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/usb/core/hcd.c (ffffffff816af643)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff816b760f)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816c3d02)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81705f2e)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81726fb0)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817673d6)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff8177e4e5)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8177f2d9)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In net/core/sock.c (ffffffff817b261a)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/skbuff.c (ffffffff817bd0b2)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/dev.c (ffffffff817c7e2a)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff817da1aa)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff817e9f28)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/fib_rules.c (ffffffff817f3d98)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/dst_cache.c (ffffffff817f95cf)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/ipv4/route.c (ffffffff81812b73)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff818147f1)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffff81817653)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181c1fc)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181e8b3)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fd43)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81828466)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff81832a8c)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183bf26)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d922)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818416f6)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff8184a2f6)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/icmp.c (ffffffff8184dda8)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81870248)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff818777b1)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_flo_get
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff8187d29f)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/anycast.c (ffffffff81887659)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/ip6_output.c (ffffffff81889949)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/addrconf.c (ffffffff8188ee7e)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81897370)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff8189db71)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_ins_rt
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff818a95d7)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff818ac6c5)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b5a36)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818bdc38)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/fib6_rules.c (ffffffff818c7200)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff818c9ad7)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce487)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff818ebe0a)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
```
```
In lib/klist.c (ffffffff818edb9e)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
```
```
In lib/kobject.c (ffffffff818ee062)
Location: arch/x86/include/asm/atomic.h:190
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/events/core.c (ffffffff810063c8)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/process.c (ffffffff81038734)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e928)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In kernel/cred.c (ffffffff810aecbe)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b3a6d)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810c5a60)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810dc1a6)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff810e246f)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810e82ff)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff810f291c)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/futex.c (ffffffff8111df60)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff81121165)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:SyS_delete_module
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81154046)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/bpf/syscall.c (ffffffff811a0467)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/events/core.c (ffffffff811be65b)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff811c2ad0)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff811c4c2a)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff811cbdde)
Location: arch/x86/include/asm/atomic.h:191
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
In mm/swap.c (ffffffff811e14db)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff811e6fd0)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff8120571f)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
```
```
In mm/rmap.c (ffffffff8121e05f)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8122b401)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff8122d6fd)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff81235649)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8123be83)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff81989f2c)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8124cf75)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81254ffb)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff8125ab26)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81263f44)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff8126c34c)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff81276183)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/notify/mark.c (ffffffff812bcb38)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark_safe
```
```
In fs/userfaultfd.c (ffffffff812c7328)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/posix_acl.c (ffffffff812deed3)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff812ea209)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812f1562)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff812f4937)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff812f8c49)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff812fada4)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
```
```
In fs/kernfs/mount.c (ffffffff812fd410)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/kernfs/dir.c (ffffffff812ff2ba)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/configfs/item.c (ffffffff81306578)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff81308966)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff8131b2cd)
Location: arch/x86/include/asm/atomic.h:191
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
In fs/ext4/mballoc.c (ffffffff813378bf)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff8135b5ac)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff813a24fc)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff813a7513)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff813b492f)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff813b61ef)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff81400e6e)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/context.c (ffffffff81403aed)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81409d88)
Location: arch/x86/include/asm/atomic.h:191
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
In security/apparmor/policy.c (ffffffff8140b95b)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff8140e57c)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8140fd3e)
Location: arch/x86/include/asm/atomic.h:191
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
In security/apparmor/resource.c (ffffffff81412049)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8141363c)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff81417458)
Location: arch/x86/include/asm/atomic.h:191
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
In security/apparmor/mount.c (ffffffff814185a9)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81419be7)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8141b928)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/bsg-lib.c (ffffffff81472013)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff814987c1)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff814bf2d2)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff814c9a88)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814f149b)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159f4c2)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff815f4543)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff815f8721)
Location: arch/x86/include/asm/atomic.h:191
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
In drivers/char/hw_random/core.c (ffffffff81614924)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff8163a35e)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff81643d23)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff81653f45)
Location: arch/x86/include/asm/atomic.h:191
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
In drivers/dma-buf/dma-buf.c (ffffffff816a7294)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff816a942e)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816aacfc)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff816ad645)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff816b8990)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/net/loopback.c (ffffffff816f7443)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff8171aca0)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81722ecf)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8172fae2)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817770fe)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81798600)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81798916)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817dd308)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff817f4a87)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff817f588e)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81811991)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff8182a7da)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81833a76)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/net_namespace.c (ffffffff8183d202)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
```
```
In net/core/dev.c (ffffffff8184a0cb)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81855dba)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818655b8)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff8186f4b3)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/dst_cache.c (ffffffff81876ee2)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffffffff8188d8e6)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff818921b3)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff8189360c)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff81896891)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81897a3c)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189b152)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189dacc)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189ed0e)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff818a78ea)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff818b1eb4)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b99ab)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bd038)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0f0e)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff818c9e96)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff818cb6a5)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff818cda97)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818e9ec6)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f0c0c)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8fcb)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff818fe046)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff45a)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffaa9)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/anycast.c (ffffffff81908889)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/ip6_output.c (ffffffff8190c634)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff819104ce)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff8191d91e)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_ins_rt
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff8192baf8)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff8192ed45)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819387a3)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81940cd8)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81944a35)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff8194a720)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff8194d163)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff8194fbc7)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8195330f)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81971e01)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
```
```
In lib/klist.c (ffffffff81973a2e)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
```
```
In lib/kobject.c (ffffffff819742a2)
Location: arch/x86/include/asm/atomic.h:191
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In kernel/locking/qspinlock.c (ffffffff810e51e6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/bpf/btf.c (ffffffff811c968e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/sockmap.c (ffffffff811cf7a3)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendpage
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
```
```
In mm/zswap.c (ffffffff812507c9)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In fs/notify/mark.c (ffffffff812e5833)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/posix_acl.c (ffffffff8130aee0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/proc_net.c (ffffffff8132832c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff81334358)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff813d18ec)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff813d68b3)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff813e510f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff813e6a2b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff814321e0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff81434c25)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8143b530)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
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
In security/apparmor/policy.c (ffffffff8143d202)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/procattr.c (ffffffff8144015b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8144232b)
Location: include/asm-generic/atomic-instrumented.h:69
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
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff814441f6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81445985)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff814498d0)
Location: include/asm-generic/atomic-instrumented.h:69
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
In security/apparmor/mount.c (ffffffff8144aa48)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8144c02f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8144d808)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff8148f683)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In block/bsg-lib.c (ffffffff814a6373)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff814cd9b0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8162d856)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff8164e53c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e34f3)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff816e54aa)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e71ed)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f3ae8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In net/core/sock.c (ffffffff81875b64)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In net/core/skbuff.c (ffffffff8187def2)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81887aab)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff818a00bf)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818b8372)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff818c054f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/ipv4/route.c (ffffffff818e3784)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff818e783d)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f1c6e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f376e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff818fca3a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff8191fe49)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81939390)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8194752c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194e4da)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81954b27)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/route.c (ffffffff81975663)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81983de8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff819879eb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff819a681b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819acd47)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/klist.c (ffffffff819cfe0e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In lib/kobject.c (ffffffff819d0b92)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/events/core.c (ffffffff81006a7a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81032e93)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8103b13f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81041513)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81061607)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff81071642)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/cred.c (ffffffff810be86e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/ucount.c (ffffffff810c0d2d)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810c1009)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810c4123)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810d5f7a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810efdd6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81a2d15f)
Location: include/asm-generic/atomic-instrumented.h:69
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
In kernel/locking/qspinlock.c (ffffffff810f07c5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810f1f96)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810f5e6e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810fbd08)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff811064dc)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/futex.c (ffffffff81136a94)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff8113a65d)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8116f683)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff8117dc17)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81185710)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8118d17c)
Location: include/asm-generic/atomic-instrumented.h:69
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
In kernel/trace/trace_sched_wakeup.c (ffffffff811996a4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8119a99b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/syscall.c (ffffffff811c4b20)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/btf.c (ffffffff811dcf8e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff811eecd8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
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
In kernel/events/ring_buffer.c (ffffffff811f32f0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff811f5b00)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff811fd00d)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_entries_tag
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff812155ba)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8121b1bd)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81239c78)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffffffff8124b7eb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff81254620)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff81260b4b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81264c9e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff8126cc5b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81273b47)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff81a21b75)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8128509a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8128d4f5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff81292e89)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8129d192)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812a5f09)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memfd.c (ffffffff812a8e4f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812aa052)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812b26c8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff812b64e1)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812bf972)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff812f30f1)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/notify/mark.c (ffffffff812fa425)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff81305059)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/posix_acl.c (ffffffff81320720)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff8132efd6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81331ac3)
Location: include/asm-generic/atomic-instrumented.h:69
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
In fs/proc/base.c (ffffffff81334c85)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff813390b0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff8133d3fa)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff8133f50c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/mount.c (ffffffff813423c0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/kernfs/dir.c (ffffffff81344088)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/configfs/item.c (ffffffff8134b6c8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff8134db65)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8136126c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/mballoc.c (ffffffff8137e27e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
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
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff813a2645)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff813ebfec)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff813f0f43)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff813ff8df)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8140122b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8144df5c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff81451808)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8145826c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
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
In security/apparmor/policy.c (ffffffff8145a066)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/procattr.c (ffffffff8145d043)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8145f25d)
Location: include/asm-generic/atomic-instrumented.h:69
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
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff814612b1)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814628a0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff81466860)
Location: include/asm-generic/atomic-instrumented.h:69
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
In security/apparmor/mount.c (ffffffff814679b8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81469008)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8146a7c5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff814a9101)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In block/bsg-lib.c (ffffffff814c0373)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff814e2080)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff81504252)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff8150e962)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff815374bb)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f07e7)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8164b442)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164f3f1)
Location: include/asm-generic/atomic-instrumented.h:69
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
In drivers/tty/serdev/core.c (ffffffff81661058)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff8166c7cc)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff81694c79)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff8169f595)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816b0873)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81706873)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff8170849a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8170a57d)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff8170d9f5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81717680)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff81756087)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff81757729)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff8177d56f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff8178562c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8179297f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817de4a4)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818021e3)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8180294b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81851e58)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81868f07)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8186ad22)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81a2345c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187aa42)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81895337)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8189eac2)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/net_namespace.c (ffffffff818a831b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff818b4cc8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818c3c35)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818d7f0c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff818e949f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff818f2011)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In net/core/dst_cache.c (ffffffff818f3540)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/sched/cls_api.c (ffffffff818fdb47)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff8190e09d)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819130d6)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff819146ed)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff819178e8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81919042)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191d237)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f812)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8192128e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8192abaa)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f667)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8194164f)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819451d8)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff8194eaa7)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff819509a2)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81952c88)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81968f6a)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81970165)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81977708)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819790fc)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81983061)
Location: include/asm-generic/atomic-instrumented.h:69
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
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81989389)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a9b0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b1b0)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81998a86)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff8199a8e5)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819adfac)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff819ba32c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff819be32d)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c7e7c)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d0798)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff819d4150)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff819da354)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff819dd37b)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff819df596)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3707)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81a07681)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In lib/klist.c (ffffffff81a0944e)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
```
```
In lib/kobject.c (ffffffff81a09e32)
Location: include/asm-generic/atomic-instrumented.h:69
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/events/core.c (ffffffff81006c9b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81034ca3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8103d734)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064cf7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff810754c3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/cred.c (ffffffff810c486f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/ucount.c (ffffffff810c6e38)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810c70f1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810c9f20)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810debe2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810f7830)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81a9d32f)
Location: include/asm-generic/atomic-instrumented.h:691
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
In kernel/locking/qspinlock.c (ffffffff810f900e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810fa3f6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810fe404)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff811043d8)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff8110fa67)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff81126079)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff81141d74)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:get_pi_state
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff81145f46)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117c882)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff8118ab17)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81192a50)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811a0527)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a72c4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811a8632)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/syscall.c (ffffffff811d5d3c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff811e67a1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff811f25ee)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff8120659c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
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
In kernel/events/ring_buffer.c (ffffffff8120affd)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff8120d887)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff812110d5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In mm/filemap.c (ffffffff8121548e)
Location: include/asm-generic/atomic-instrumented.h:691
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
In mm/swap.c (ffffffff81224fd9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8122ae4f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff8124aefa)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffffffff8125dcae)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff812668f2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8127b738)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff8127f8bc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff8128808b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8128fc06)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff8129c532)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8129f70a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a7e8c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812adb8c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b8807)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812c1661)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff812c2e87)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
  - mm/hmm.c:hmm_mirror_register
  - mm/hmm.c:hmm_invalidate_range_end
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:hmm_release
```
```
In mm/memfd.c (ffffffff812c5978)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812c680e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812cf129)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff812d3254)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812dcb03)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/block_dev.c (ffffffff81314b66)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/notify/mark.c (ffffffff8131ae2a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff81326d7c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff81330cfa)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/posix_acl.c (ffffffff81347fcd)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff81356a56)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff813598a6)
Location: include/asm-generic/atomic-instrumented.h:691
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
In fs/proc/base.c (ffffffff8135d478)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff8136176e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff81365711)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff8136782d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff8136c2d9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/configfs/item.c (ffffffff81374287)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff8137654b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8138a316)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/mballoc.c (ffffffff813a770e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/super.c (ffffffff813ca50d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff81418246)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8141d212)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8142c01e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8142da47)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8147b8cc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff8147f237)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81485a29)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
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
In security/apparmor/policy.c (ffffffff814876e1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff8148a5e2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8148c6dd)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff8148e5a4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8148fb6c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff81491904)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/mount.c (ffffffff81494a31)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81496064)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814977e5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff814d6aa9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In block/bsg-lib.c (ffffffff814eeb72)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff8150df30)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff815323cb)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff8153df54)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81566e0d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff816227b7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81680442)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff816840e5)
Location: include/asm-generic/atomic-instrumented.h:691
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
In drivers/tty/serdev/core.c (ffffffff816971c2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff816a23c3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff816cd627)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff816d7d4d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816ea49b)
Location: include/asm-generic/atomic-instrumented.h:691
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
In drivers/dma-buf/dma-buf.c (ffffffff817419da)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff817434e6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/dma-buf/reservation.c (ffffffff8174403f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81745e7a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff817493d0)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81752373)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff817921b3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff81793ee1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/cdrom/cdrom.c (ffffffff817b1eb9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817bc493)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817c43a8)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817d1abd)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8181ef34)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81843a2f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81843ec9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818953a4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff818add58)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818aec33)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81a935c4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818c0aa9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff818e1c2c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818e9333)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff818f389a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff8190164e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff8191354c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81925c8c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff81938ed7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81944597)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/core/dst_cache.c (ffffffff819459f9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/core/bpf_sk_storage.c (ffffffff8195373e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff8195d486)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff8196fc02)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819756c5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81976c4e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff81979f6e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8197b043)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8197f407)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982161)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983c49)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8198ddf9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a39e5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5c4c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a97b7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff819b3286)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff819b5288)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819b74d4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819c8f76)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfe75)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819d4fac)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819d9a18)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e123a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e2c0a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ecccc)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff819f31c0)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff819f5655)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f66e1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a048f3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81a068a5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a1bd72)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81a294a6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a2d5f5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3696f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3fd7c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a42ff6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a48f4e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81a4c37a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e13d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a52432)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81a76ffb)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In lib/klist.c (ffffffff81a78de9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In lib/kobject.c (ffffffff81a796a6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/events/core.c (ffffffff81006d29)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810354d3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8103def4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065367)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff81076493)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810993e4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/cred.c (ffffffff810cd91f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/ucount.c (ffffffff810cff08)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810d01c1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810d3130)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e9132)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff81103660)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81ad4b0f)
Location: include/asm-generic/atomic-instrumented.h:691
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
In kernel/locking/qspinlock.c (ffffffff81104e1e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff811061d6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff8110a809)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff8111078f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff8111bd27)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff81132049)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8114c0d1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/module.c (ffffffff81151ad6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81188702)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff81196a07)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8119e6d0)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811abf57)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2ab4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811b3e42)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/syscall.c (ffffffff811e06b2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff811f2ef1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff811fed0e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff8121393f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
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
In kernel/events/ring_buffer.c (ffffffff812182dd)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff8121aeb7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff8121ed15)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In mm/filemap.c (ffffffff8122281e)
Location: include/asm-generic/atomic-instrumented.h:691
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
In mm/swap.c (ffffffff81232da9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff81238d1f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff812593ea)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffffffff8126c47e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff81275212)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8128b218)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff8128f6ac)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff81297c8b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8129f996)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812abf91)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b0aaa)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b9380)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812bf6dc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812ca6e7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812d3591)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff812d4d1e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In mm/memfd.c (ffffffff812d7388)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812d8212)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812e01a9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff812e4de4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812ee652)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/notify/mark.c (ffffffff8132da1a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff81339b0c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff813446f7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/crypto/keyring.c (ffffffff8134c6c9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/verity/enable.c (ffffffff8134fe83)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff8136026d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff8136f08e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81371af6)
Location: include/asm-generic/atomic-instrumented.h:691
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
In fs/proc/base.c (ffffffff81374eb8)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff813799ce)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff8137d9a1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff8137faad)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff81384489)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/configfs/item.c (ffffffff8138c507)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff8138e7bb)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813a2d4e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/mballoc.c (ffffffff813c05ae)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/super.c (ffffffff813e38bd)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff81432106)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81437062)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff81445d6e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff81447797)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8149559c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff81498f37)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8149f912)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff814a1591)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff814a44a2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814a659d)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff814a8464)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814a9a2c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff814ab834)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/mount.c (ffffffff814ae961)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff814aff94)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814b1715)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff814efe0e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In block/bsg-lib.c (ffffffff81507fd2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff8152bd80)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff8155320b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff8155ed74)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8158816d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff81644297)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8169e16a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816a2af2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a6795)
Location: include/asm-generic/atomic-instrumented.h:691
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
In drivers/tty/serdev/core.c (ffffffff816b9d72)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff816c5164)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff816f1467)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff816fbd1c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff8170e4fb)
Location: include/asm-generic/atomic-instrumented.h:691
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
In drivers/base/power/wakeup.c (ffffffff81713ac6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81765b5f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8176748e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8176819d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81769fd3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff8176d520)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff817765f3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff817b5d84)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff817b7a11)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff817d06ab)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In drivers/cdrom/cdrom.c (ffffffff817e2209)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817eccb3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817f4d48)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8180298d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff818503f4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818753b0)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875839)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff818bce92)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818c73bc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff818e0208)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818e10df)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81acad7c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818f350b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81913dec)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8191b493)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff8192584a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff8193397c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81945bac)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff819582dc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff8196bd97)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81979597)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/core/dst_cache.c (ffffffff8197aa15)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/core/bpf_sk_storage.c (ffffffff81989ade)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81993986)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff819a6581)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819ac0e1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff819ad5de)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff819b08ce)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819b19b3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b5947)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b89c1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba429)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819c49c9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da6e7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dca0c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e0477)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff819ea009)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff819ebfb2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819ee1d4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819ffb36)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06a05)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a0bb0c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a10878)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a185fa)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a19bfa)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23cdc)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2a090)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c305)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d361)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b4e4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81a3d415)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a529f2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81a60002)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a6415b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6d48f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a769ec)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a79b56)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a7fb3e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81a82f4a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff81a84d8e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a89042)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81aae3db)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In lib/klist.c (ffffffff81ab0199)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In lib/kobject.c (ffffffff81ab0a06)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
```
</details>
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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117f7a3)
Location: include/linux/atomic/atomic-instrumented.h:501
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/requeue.c (ffffffff811b6452)
Location: include/linux/atomic/atomic-instrumented.h:530
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
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
In kernel/smpboot.c (ffffffff8112a0fe)
Location: include/linux/atomic/atomic-instrumented.h:530
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/futex/requeue.c (ffffffff811f7592)
Location: include/linux/atomic/atomic-instrumented.h:530
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/bpf/ringbuf.c (ffffffff81304af9)
Location: include/linux/atomic/atomic-instrumented.h:530
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
```
```
In kernel/jump_label.c (ffffffff81354c54)
Location: include/linux/atomic/atomic-instrumented.h:530
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_fast_inc_not_disabled
```
```
In fs/aio.c (ffffffff814f0990)
Location: include/linux/atomic/atomic-instrumented.h:530
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-rq-qos.c (ffffffff8175d263)
Location: include/linux/atomic/atomic-instrumented.h:530
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff8176b279)
Location: include/linux/atomic/atomic-instrumented.h:530
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff818a2d3e)
Location: include/linux/atomic/atomic-instrumented.h:530
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In net/core/dev.c (ffffffff81dbf423)
Location: include/linux/atomic/atomic-instrumented.h:530
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7d80f)
Location: include/linux/atomic/atomic-instrumented.h:530
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum
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
In arch/x86/kernel/apic/apic.c (ffffffff8109fa60)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/cpu.c (ffffffff810f96f1)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_kick_ap_alive
  - kernel/cpu.c:cpuhp_wait_for_sync_state
```
```
In kernel/futex/requeue.c (ffffffff8120bd32)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/trace/ring_buffer.c (ffffffff81273bbf)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/bpf/ringbuf.c (ffffffff813334b2)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
```
```
In kernel/jump_label.c (ffffffff81386144)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_fast_inc_not_disabled
```
```
In mm/rmap.c (ffffffff8140ad9d)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - mm/rmap.c:set_tlb_ubc_flush_pending
```
```
In fs/aio.c (ffffffff81527730)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-rq-qos.c (ffffffff8179bfc7)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff817aa359)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff818e5217)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In net/core/dev.c (ffffffff81e2f0d3)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdda1f)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum
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
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810a033a)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_nmi_unknown
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a6fc5)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In kernel/panic.c (ffffffff810ff346)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/cpu.c (ffffffff81102b01)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_kick_ap_alive
  - kernel/cpu.c:cpuhp_wait_for_sync_state
```
```
In kernel/printk/nbcon.c (ffffffff811b39b7)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - kernel/printk/nbcon.c:__nbcon_context_update_unsafe
  - kernel/printk/nbcon.c:nbcon_context_can_proceed
```
```
In kernel/futex/requeue.c (ffffffff812232c7)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/kexec_core.c (ffffffff8122cd5c)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/trace/ring_buffer.c (ffffffff8128e1bf)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/bpf/ringbuf.c (ffffffff81357ba2)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
```
```
In kernel/jump_label.c (ffffffff813af604)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_fast_inc_not_disabled
```
```
In mm/rmap.c (ffffffff814374d8)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
```
```
In fs/aio.c (ffffffff8155c570)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In block/blk-rq-qos.c (ffffffff817dfa27)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/blk-iocost.c (ffffffff817ee0e1)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In lib/sbitmap.c (ffffffff8192c217)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In net/core/dev.c (ffffffff81eedd53)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff820aaacf)
Location: include/linux/atomic/atomic-instrumented.h:1270
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum
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
In kernel/cred.c (ffff80001012cbb8)
Location: include/linux/atomic-fallback.h:915
Inline: True
```
```
In kernel/ucount.c (ffff800010130378)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffff80001013077c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/locking/mutex.c (ffff800010168854)
Location: include/linux/atomic-fallback.h:915
Inline: True
```
```
In kernel/irq/chip.c (ffff800010180128)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/module.c (ffff8000101c27bc)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:__arm64_sys_delete_module
```
```
In kernel/debug/kdb/kdb_main.c (ffff800010200390)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/bpf/syscall.c (ffff800010264458)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/events/core.c (ffff800010297658)
Location: include/linux/atomic-fallback.h:915
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
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffff8000102ab124)
Location: include/linux/atomic-fallback.h:915
Inline: True
```
```
In mm/filemap.c (ffff8000102afe18)
Location: include/linux/atomic-fallback.h:915
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
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffff8000102c9b98)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffff8000102f1190)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffff8000103036b4)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffff80001030b004)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffff8000103265e8)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffff800010335fdc)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffff80001033f048)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffff800010350dac)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffff800010359b30)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffff800010363f74)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffff80001036e4d8)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffff80001037911c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffff80001037b0f0)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In mm/memfd.c (ffff80001037c578)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffff80001037dd38)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffff800010386f54)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffff80001038c84c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffff8000103982bc)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/userfaultfd.c (ffff8000103f890c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffff800010406318)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/verity/enable.c (ffff800010411a40)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/proc/task_mmu.c (ffff80001043a5f4)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffff80001043b7ec)
Location: include/linux/atomic-fallback.h:915
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
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/proc_sysctl.c (ffff80001044aa48)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/dir.c (ffff8000104530d0)
Location: include/linux/atomic-fallback.h:915
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
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffff800010473db4)
Location: include/linux/atomic-fallback.h:915
Inline: True
```
```
In fs/ext4/mballoc.c (ffff800010495384)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In fs/ext4/super.c (ffff8000104bd038)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In drivers/phy/phy-core.c (ffff8000106879d0)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffff8000106ec540)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/amba/bus.c (ffff8000107b9548)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/tty/hvc/hvc_console.c (ffff800010879c60)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffff80001087e29c)
Location: include/linux/atomic-fallback.h:915
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
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_remove
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892d7c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
```
```
In drivers/tty/serdev/core.c (ffff8000108a9ff0)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffff8000108e6610)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffff8000108fe0d4)
Location: include/linux/atomic-fallback.h:915
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
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/scsi/hosts.c (ffff80001096fb7c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffff8000109c95f8)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cdac0)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/loopback.c (ffff8000109d0270)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e67c8)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/cdrom/cdrom.c (ffff800010a10188)
Location: include/linux/atomic-fallback.h:915
Inline: True
```
```
In drivers/usb/core/hcd.c (ffff800010a1c360)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffff800010a25934)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a37144)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a90f34)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010aba1fc)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba664)
Location: include/linux/atomic-fallback.h:915
Inline: True
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abca5c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
```
In drivers/cpufreq/cpufreq_governor.c (ffff800010b25bf8)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a40c)
Location: include/linux/atomic-fallback.h:915
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b21c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/mmc/core/block.c (ffff800010b41748)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/firmware/efi/efi.c (ffff800010d9f398)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e9e8)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In drivers/perf/arm-cci.c (ffff800010b91ba0)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_event_init
```
```
In net/core/sock.c (ffff800010bac17c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffff800010bb479c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_dump
```
```
In net/core/dev.c (ffff800010bd1ad0)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffff800010be761c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffff800010c01104)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffff800010c22154)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffff800010c55dfc)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffff800010c5bf94)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffff800010c60eec)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffff800010c62364)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffff800010c6686c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8bb2c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f974)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c940e4)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffff800010c9e318)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffff800010ca1a90)
Location: include/linux/atomic-fallback.h:915
Inline: True
```
```
In net/ipv4/icmp.c (ffff800010ca3d44)
Location: include/linux/atomic-fallback.h:915
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010ccb4a0)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0f60)
Location: include/linux/atomic-fallback.h:915
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
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec084)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffff800010cfc5e8)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/route.c (ffff800010d11200)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d371b4)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3fc8c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffff800010d43e38)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffff800010d4b190)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffff800010d50e1c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In lib/dec_and_lock.c (ffff800010d84724)
Location: include/linux/atomic-fallback.h:915
Inline: True
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
In kernel/ucount.c (c037fd0c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (c0380000)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/locking/rwsem.c (c0e9d44c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/module.c (c0408210)
Location: include/linux/atomic-fallback.h:915
Inline: True
```
```
In kernel/events/core.c (c04c78e4)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (c0521eac)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (c0566eb0)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (c0567860)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/exec.c (c0574404)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (c057e8b4)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/verity/enable.c (c05de114)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/proc/inode.c (c0601ce0)
Location: include/linux/atomic-fallback.h:915
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
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
```
```
In drivers/tty/tty_ldsem.c (c0966ab0)
Location: include/linux/atomic-fallback.h:915
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
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In net/core/skbuff.c (c0cd0034)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
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
In kernel/events/core.c (c000000000346f64)
Location: include/linux/atomic-fallback.h:915
Inline: True
```
```
In mm/mmap.c (c0000000003d0300)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (c0000000004717d0)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (c000000000472a20)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/exec.c (c00000000048479c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (c0000000004921d0)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/verity/enable.c (c00000000051f5f8)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/proc/inode.c (c00000000054f48c)
Location: include/linux/atomic-fallback.h:915
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
In fs/kernfs/dir.c (c00000000056c364)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
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
In kernel/events/core.c (ffffffe0001ca116)
Location: include/linux/atomic-fallback.h:915
Inline: True
```
```
In mm/mmap.c (ffffffe0002101fa)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffe000252916)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffe0002538ec)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/exec.c (ffffffe00025d0d8)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffe000265eda)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/verity/enable.c (ffffffe0002b9c2c)
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/proc/inode.c (ffffffe0002d3bbe)
Location: include/linux/atomic-fallback.h:915
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
Location: include/linux/atomic-fallback.h:915
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_get_active
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
In arch/x86/events/core.c (ffffffff81006d29)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81035633)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8103e074)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064e57)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff81075493)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/cred.c (ffffffff810c7c9f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/ucount.c (ffffffff810ca288)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810ca541)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810cd450)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e32e2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810fc970)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81a7397f)
Location: include/asm-generic/atomic-instrumented.h:691
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
In kernel/locking/qspinlock.c (ffffffff810fe12e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810ff4e6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81102a69)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff81108d5f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff81114307)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff8112a7f9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff811446f1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/module.c (ffffffff8114a0f6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81180d22)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff8118f027)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81196cf0)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811a4577)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab0d4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811ac462)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/syscall.c (ffffffff811d8cd2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff811eb511)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff811f732e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff8120bf8f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
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
In kernel/events/ring_buffer.c (ffffffff8121092d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff81213507)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff81217365)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In mm/filemap.c (ffffffff8121ae6e)
Location: include/asm-generic/atomic-instrumented.h:691
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
In mm/swap.c (ffffffff8122b3f9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8123136f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81251a3a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffffffff81264ace)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff8126d862)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812837f8)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81287c8c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff8129026b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81297f76)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812a4571)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a908a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b1960)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812b7cbc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c2cc7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812cbb71)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff812cd2fe)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In mm/memfd.c (ffffffff812cf968)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812d07f2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812d8789)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff812dd3c4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812e6c32)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/notify/mark.c (ffffffff81325ffa)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff813320ec)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8133ccd7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/crypto/keyring.c (ffffffff81344ca9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/verity/enable.c (ffffffff81348463)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff8135884d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff8136766e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff8136a0d6)
Location: include/asm-generic/atomic-instrumented.h:691
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
In fs/proc/base.c (ffffffff8136d498)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff81371fae)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff81375f81)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff8137808d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff8137ca69)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/configfs/item.c (ffffffff81384ae7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff81386d9b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8139b32e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/mballoc.c (ffffffff813b8b8e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/super.c (ffffffff813dbe9d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff8142a6e6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8142f642)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8143e34e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8143fd77)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8148db7c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff81491517)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81497ef2)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81499b71)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff8149ca82)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149eb7d)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff814a0a44)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814a200c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff814a3e14)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/mount.c (ffffffff814a6f41)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff814a8574)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814a9cf5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff814e83ee)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In block/bsg-lib.c (ffffffff815005b2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff81524360)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff8154b7eb)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff81557364)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8157bffd)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/tty/vt/vt.c (ffffffff81663bca)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81668552)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166c1f5)
Location: include/asm-generic/atomic-instrumented.h:691
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
In drivers/tty/serdev/core.c (ffffffff8167f7d2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff8168abb4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff816b6c57)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff816c150c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff816d3c4b)
Location: include/asm-generic/atomic-instrumented.h:691
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
In drivers/base/power/wakeup.c (ffffffff816d9df6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8171a24f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8171bb7e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171c88d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8171e6c3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff81721c10)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172ace3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/nvme/host/core.c (ffffffff81746fb8)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_find_get_ns
  - drivers/nvme/host/core.c:nvme_init_subsystem
  - drivers/nvme/host/core.c:nvme_ns_head_open
  - drivers/nvme/host/core.c:nvme_open
```
```
In drivers/spi/spi.c (ffffffff8177a864)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff8177c4e9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/cdrom/cdrom.c (ffffffff8179a5e9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817a5093)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817ad128)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817bad6d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff818061c4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8186badc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81883bc8)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81884a9f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81a69bec)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8189483b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff818b3dec)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818bb493)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff818c584a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff818d397c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818e5b7c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818f82ac)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff8190bd67)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81919407)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/core/dst_cache.c (ffffffff8191a885)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/core/bpf_sk_storage.c (ffffffff8192994e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff819337f6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff819463f1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff8194bf51)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff8194d44e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff8195073e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81951823)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff819557b7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81958831)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a299)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81964839)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a557)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c87c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819802e7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81989e79)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff8198bde2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8198df74)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8199f8d6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819a67a5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819ab8ac)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b0288)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7c8a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b928a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c336c)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff819c9720)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb995)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc9f1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819dab74)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff819dcaa5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819f2082)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff819ff692)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a037eb)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0cb1f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a1607c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a191e6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a1f1ce)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81a225da)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff81a2441e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a286d2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81a4d22b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In lib/klist.c (ffffffff81a4efe9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In lib/kobject.c (ffffffff81a4f856)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/events/core.c (ffffffff81005449)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81024f86)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8102d884)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055127)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff8106528f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/cred.c (ffffffff810b64bf)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/ucount.c (ffffffff810b8a98)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810b8d51)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810bfa15)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_tick_remote
```
```
In kernel/sched/fair.c (ffffffff810d23f2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810ecb80)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81a2fcdf)
Location: include/asm-generic/atomic-instrumented.h:691
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
In kernel/locking/qspinlock.c (ffffffff810ee32e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810ef6d6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810f3cd9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810f9c4f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff81105017)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff8111d069)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff81136f21)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/module.c (ffffffff8113d3a6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81173e62)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff81182199)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81189fbe)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff81197547)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e3e4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8119f31c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/syscall.c (ffffffff811cba92)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff811de2b4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff811ea07e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff811fed5f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
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
In kernel/events/ring_buffer.c (ffffffff812036bd)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff81206277)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff8120a0c5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In mm/filemap.c (ffffffff8120e06e)
Location: include/asm-generic/atomic-instrumented.h:691
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
In mm/swap.c (ffffffff8121e4e9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8122442f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff812448e2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffffffff81256eee)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff8125f892)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812756b7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81279aec)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff81281efb)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81289b36)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff81296041)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8129aa00)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a2d30)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812a8e8c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b3d17)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812bc9f1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff812be16e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In mm/memfd.c (ffffffff812c05e8)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812c1472)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812c9409)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff812ce044)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812d7872)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/notify/mark.c (ffffffff81316b9a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff81322cac)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8132d9a7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/crypto/keyring.c (ffffffff81335989)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/verity/enable.c (ffffffff81339143)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff813494fd)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff8135830e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff8135ab66)
Location: include/asm-generic/atomic-instrumented.h:691
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
In fs/proc/base.c (ffffffff8135df28)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff81362a87)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff81366a51)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff81368b5d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff8136d539)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/configfs/item.c (ffffffff81375577)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff8137782b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8138bdbe)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/mballoc.c (ffffffff813a961e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/super.c (ffffffff813cc91d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff8141b166)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814200c2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8142edbe)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff814307e7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8147e59c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff81481f37)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81488912)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8148a591)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff8148d4a2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8148f59d)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81491464)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81492a2c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff81494834)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/mount.c (ffffffff81497961)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81498f94)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8149a715)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff814d895e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In block/bsg-lib.c (ffffffff814f0ac2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff81514640)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff8153bacb)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff81547824)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8156adcd)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/tty/vt/vt.c (ffffffff81643f4a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816488d2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164b495)
Location: include/asm-generic/atomic-instrumented.h:691
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
In drivers/char/hw_random/core.c (ffffffff816685b4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff81694897)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff8169c7bc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff816aeeeb)
Location: include/asm-generic/atomic-instrumented.h:691
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
In drivers/base/power/wakeup.c (ffffffff816b4476)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816f36b9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff816f4fde)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f5ced)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816f7b0d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff816fb040)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81704103)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/nvme/host/core.c (ffffffff81728c33)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_find_get_ns
  - drivers/nvme/host/core.c:nvme_init_subsystem
  - drivers/nvme/host/core.c:nvme_ns_head_open
  - drivers/nvme/host/core.c:nvme_open
```
```
In drivers/spi/spi.c (ffffffff8175a614)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff8175c299)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/vxlan.c (ffffffff81770d7b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/net/vxlan.c:__vxlan_sock_add
```
```
In drivers/vfio/vfio.c (ffffffff8177a75b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In drivers/cdrom/cdrom.c (ffffffff8178c2b9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81796ba3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff8179eb28)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817ac78d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff817b5d2f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817cd944)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8183478c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/firmware/efi/efi.c (ffffffff81a260bc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8184cd15)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff8186dd3c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818753d3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff8187f78a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff8188d80c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff8189f9bc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818b20dc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff818c5b27)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff818d31b7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/core/dst_cache.c (ffffffff818d4635)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/core/bpf_sk_storage.c (ffffffff818e36fe)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff818ed2f6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff818ffee1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff81905a41)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81906f3e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff8190a22e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8190b313)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8190f2a7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81912321)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913d89)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8191e329)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934017)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8193633c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939da7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81943939)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff819458a2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81947a34)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81959396)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81960265)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff8196536c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196c8b8)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974a7a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8197607a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff8198015c)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81986510)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff81988785)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819897e1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81997934)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81999865)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819aee42)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff819bc452)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff819c05ab)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c98df)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d2e3c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff819d5fa6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff819dbf8e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff819df39a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff819e11de)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e5492)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81a0a35b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In lib/klist.c (ffffffff81a0c0e9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In lib/kobject.c (ffffffff81a0c956)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/events/core.c (ffffffff81006ce9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81035493)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8103deb4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065307)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff81075443)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/cred.c (ffffffff810c71ef)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/ucount.c (ffffffff810c97b8)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810c9a71)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810cc930)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810df662)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810f9b30)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81adfd8f)
Location: include/asm-generic/atomic-instrumented.h:691
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
In kernel/locking/qspinlock.c (ffffffff810fb2ee)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810fc6a6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81100cd9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff81106c5f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff811121f7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff81128519)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff811425a1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/module.c (ffffffff81147fa6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117eaf2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff8118cdf7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81194ac0)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811a2347)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8ea4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811aa232)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/syscall.c (ffffffff811d6aa2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff811e92e1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff811f50fe)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff81209d2f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
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
In kernel/events/ring_buffer.c (ffffffff8120e6cd)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff812112a7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff81215105)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In mm/filemap.c (ffffffff81218c0e)
Location: include/asm-generic/atomic-instrumented.h:691
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
In mm/swap.c (ffffffff81229199)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8122f10f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff8124f7da)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffffffff8126286e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff8126b602)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff81281608)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81285a9c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff8128e07b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81295d86)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812a2381)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a6e9a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812af770)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812b5acc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c0ad7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812c9981)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff812cb10e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In mm/memfd.c (ffffffff812cd778)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812ce602)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812d6599)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff812db1d4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812e4a42)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/notify/mark.c (ffffffff81323aca)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff8132fbbc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8133a7a7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/crypto/keyring.c (ffffffff81342779)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/verity/enable.c (ffffffff81345f33)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff8135631d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff8136513e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81367ba6)
Location: include/asm-generic/atomic-instrumented.h:691
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
In fs/proc/base.c (ffffffff8136af68)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff8136fa7e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff81373a51)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff81375b5d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff8137a539)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/configfs/item.c (ffffffff813825b7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff8138486b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81398b8e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/mballoc.c (ffffffff813b63ee)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/super.c (ffffffff813d933d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff81426886)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8142b7e2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8143a4ee)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8143bf17)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff81489c1c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff8148d5b7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81493f92)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81495c11)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff81498b22)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149ac1d)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff8149cae4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8149e0ac)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff8149feb4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/mount.c (ffffffff814a2fe1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff814a4614)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814a5d95)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff814e447e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In block/bsg-lib.c (ffffffff814fc642)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff815203f0)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff8154752b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff815530a4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8157bebd)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff816380d7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81691faa)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81696932)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169a5d5)
Location: include/asm-generic/atomic-instrumented.h:691
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
In drivers/tty/serdev/core.c (ffffffff816adbb2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff816b8e24)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff816e5127)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff816ef9dc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817021bb)
Location: include/asm-generic/atomic-instrumented.h:691
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
In drivers/base/power/wakeup.c (ffffffff81707786)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8175901f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8175a94e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175b65d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8175d493)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff817609e0)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81769ab3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff817aac04)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff817ac891)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff817c552b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In drivers/cdrom/cdrom.c (ffffffff817d7089)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817e1b33)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817e9bc8)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817f780d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81845274)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a860)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186ace9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff818b2342)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818bc86c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff818d5068)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818d5f3f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81ad5ffc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818e833b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81904dec)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8190c493)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff8191684a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff8192497c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81936bac)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff819492dc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff8195cd97)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff8196a597)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/core/dst_cache.c (ffffffff8196ba15)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/core/bpf_sk_storage.c (ffffffff8197aade)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81984986)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81997581)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b377)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:instance_lookup_get
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199e4db)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:gc_worker
  - net/netfilter/nf_conntrack_core.c:early_drop
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a17b9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_show
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a2e33)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_find_expectation
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_find_get
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a3369)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_try_module_get
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b0043)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_ct_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_list
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
```
```
In net/ipv4/route.c (ffffffff819b6721)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff819b7c1e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff819baf0e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819bbff3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff819bff87)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3001)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4a69)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819cf009)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e4d27)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e704c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819eaab7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff819f4649)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff819f65f2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819f8814)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0a176)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a11045)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a1614c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1ab28)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2270a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a23d0a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2ddec)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81a341a0)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff81a36415)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37471)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a455f4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81a47525)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a5cb02)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81a6a112)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a6e26b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7759f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a80afc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a83c66)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a89c4e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81a8d05a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ee9e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a94282)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81ab961b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In lib/klist.c (ffffffff81abb3d9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In lib/kobject.c (ffffffff81abbc46)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/events/core.c (ffffffff81006e49)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81036473)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8103f014)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810668e7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff810774a3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a8b4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/cred.c (ffffffff810cf72b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/ucount.c (ffffffff810d1cf8)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810d1fc5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810d52c2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810eb20a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff81104ca0)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81aec5b2)
Location: include/asm-generic/atomic-instrumented.h:691
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
In kernel/locking/qspinlock.c (ffffffff811064be)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff811078d6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff8110c0a9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff8111201f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff8111d817)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff81134ba9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8114e619)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/module.c (ffffffff81154bbf)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118c412)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff8119a937)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811a26d0)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811b00d7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6ce4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811b8072)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/syscall.c (ffffffff811e4e12)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff811f7698)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff81203627)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff81218b00)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
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
In kernel/events/ring_buffer.c (ffffffff8121d5dd)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff812201f7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff812240d5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In mm/filemap.c (ffffffff81227d03)
Location: include/asm-generic/atomic-instrumented.h:691
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
In mm/swap.c (ffffffff812384f9)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8123e51f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff8125f14a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffffffff8127222e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff8127af80)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff81291345)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff812957d5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff8129de1d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812a5b96)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812b26e1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b71cc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812bfab0)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812c5fec)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812d1597)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812da681)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff812dbe6e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In mm/memfd.c (ffffffff812de588)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812df412)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812e70d7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff812ec154)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812f59c2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/notify/mark.c (ffffffff8133580a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff8134253c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8134d302)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/crypto/keyring.c (ffffffff81355a79)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/verity/enable.c (ffffffff81359213)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff81369a29)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff8137881e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff8137b1f6)
Location: include/asm-generic/atomic-instrumented.h:691
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
In fs/proc/base.c (ffffffff8137c609)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff8138340e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff81386fe3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff8138960d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff8138e029)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/configfs/item.c (ffffffff813960d7)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff813983e6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813acfb6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/ext4/mballoc.c (ffffffff813cb10e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
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
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/super.c (ffffffff813ee634)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff8143d746)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814427f2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff81451620)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff81453097)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff814a18a8)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff814a5522)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff814abfb9)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff814adca1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff814b0c8c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814b3478)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff814b51ab)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814b67bb)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff814b857f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/mount.c (ffffffff814bb8b5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff814bcea6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814be634)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff814fd9fe)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In block/bsg-lib.c (ffffffff815156f2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff81539d70)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff8156137b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff8156cf34)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8159636d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652410)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff816ac59a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816b0ee2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b51d5)
Location: include/asm-generic/atomic-instrumented.h:691
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
In drivers/tty/serdev/core.c (ffffffff816c8012)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff816d33f4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff816ff7f5)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff8170a21c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff8171c9db)
Location: include/asm-generic/atomic-instrumented.h:691
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
In drivers/base/power/wakeup.c (ffffffff817221b6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817745f0)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81775f13)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81776917)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81778b26)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff8177c040)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81785203)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff817c4b7e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff817c6821)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff817df7cb)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In drivers/cdrom/cdrom.c (ffffffff817f1329)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817fbf23)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818040f8)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81811a4d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8185f7f4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818847f0)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884c79)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff818ce5f2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818d8b5c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff818f1b88)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818f2a5f)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81ae24bc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81904fa3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81925eb6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8192d5c3)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff81937a5c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81945e18)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81958362)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff8196abec)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff8197efeb)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff8198c9cb)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/core/dst_cache.c (ffffffff8198de93)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/core/bpf_sk_storage.c (ffffffff8199d00e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff819a7161)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff819ba261)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819bff53)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff819c148e)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff819c481b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819c5903)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c9960)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff819ccad1)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce4fa)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819d8b99)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ee087)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0d1a)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f4987)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff819fe809)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81a00802)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81a02b82)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a14956)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b9a6)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a20b8c)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a25988)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2dafc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2f129)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a395cc)
Location: include/asm-generic/atomic-instrumented.h:691
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
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3fafc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41d66)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42e01)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a512c4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81a532ef)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a68ee4)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81a76727)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a7a81d)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a83de8)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8d3bc)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a90586)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a968ae)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81a99d27)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bc22)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa03d2)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81ac5a6b)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In lib/klist.c (ffffffff81ac7849)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
```
```
In lib/kobject.c (ffffffff81ac8084)
Location: include/asm-generic/atomic-instrumented.h:691
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
```
</details>
</li>
</ul>

## Differences
