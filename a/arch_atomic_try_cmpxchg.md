# Function: <code>arch_atomic_try_cmpxchg</code>

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
In arch/x86/events/core.c (ffffffff81006b3a)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/process.c (ffffffff81039be4)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103fee5)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In kernel/cred.c (ffffffff810b5a2e)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
```
```
In kernel/sched/core.c (ffffffff810baca3)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810d0be2)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810e47e6)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
```
```
In kernel/locking/qspinlock.c (ffffffff810e51e6)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810ea83e)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810f0678)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff810fad1c)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/futex.c (ffffffff8112a954)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff8112ea7d)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811627a3)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/bpf/syscall.c (ffffffff811b5568)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/btf.c (ffffffff811c968e)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/sockmap.c (ffffffff811cf7a3)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendpage
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
```
```
In kernel/events/core.c (ffffffff811de8f5)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff811e2e80)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff811e5183)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff811eceb2)
Location: arch/x86/include/asm/atomic.h:195
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
In mm/swap.c (ffffffff81202c3a)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8120852d)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81226b77)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
```
```
In mm/rmap.c (ffffffff8123ff20)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8124c601)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff812507c9)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff81258589)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8125f407)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff819e669a)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff81270a81)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81278e45)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff8127e756)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81288240)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff81290ee9)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff8129c9f3)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/notify/mark.c (ffffffff812e5833)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff812f0119)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/posix_acl.c (ffffffff8130aee0)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff813180b6)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8131d995)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff81321fa0)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff81326542)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff8132832c)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/mount.c (ffffffff8132b050)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/kernfs/dir.c (ffffffff8132cf79)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/configfs/item.c (ffffffff81334358)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff813368e5)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813490ac)
Location: arch/x86/include/asm/atomic.h:195
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
In fs/ext4/mballoc.c (ffffffff81365e1e)
Location: arch/x86/include/asm/atomic.h:195
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
In fs/ext4/super.c (ffffffff81389ac8)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff813d18ec)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff813d68b3)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff813e510f)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff813e6a2b)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff814321e0)
Location: arch/x86/include/asm/atomic.h:195
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
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8143b530)
Location: arch/x86/include/asm/atomic.h:195
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
Location: arch/x86/include/asm/atomic.h:195
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
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8144232b)
Location: arch/x86/include/asm/atomic.h:195
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
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81445985)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff814498d0)
Location: arch/x86/include/asm/atomic.h:195
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
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8144c02f)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8144d808)
Location: arch/x86/include/asm/atomic.h:195
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
Location: arch/x86/include/asm/atomic.h:195
Inline: True
```
```
In block/bsg-lib.c (ffffffff814a6373)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff814cd9b0)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff814f0332)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff814f9d92)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8152168b)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d71a2)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8162d312)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff81631331)
Location: arch/x86/include/asm/atomic.h:195
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
In drivers/char/hw_random/core.c (ffffffff8164e53c)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff816759a7)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff8167f14b)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff81690213)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e34f3)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff816e54aa)
Location: arch/x86/include/asm/atomic.h:195
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
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff816e9f85)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f3ae8)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff81733609)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff817345d1)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff81758fff)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff8176106c)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8176e2ff)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817b7db0)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817db313)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db59b)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81825f78)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff8183cf77)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8183ed72)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8185b542)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81874937)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8187def2)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/net_namespace.c (ffffffff81887aab)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff818942aa)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818a12d5)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818b30bc)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff818c054f)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/dst_cache.c (ffffffff818c8609)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffffffff818e14f1)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff818e61be)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff818e783d)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff818eab6a)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff818ebd72)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff818ef677)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f1c6e)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f376e)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff818fca3a)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81910248)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912e92)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81916a28)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff8191fe49)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81921b82)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81923eac)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81939390)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819402e5)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8194752c)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194fa40)
Location: arch/x86/include/asm/atomic.h:195
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
In net/xfrm/xfrm_state.c (ffffffff81954b27)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff81955f8d)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819566ba)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81963adc)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81965465)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819783bc)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81983de8)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff819879eb)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199160c)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81999bc8)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff8199d5f0)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff819a3a34)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff819a681b)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff819a8a68)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819acd47)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff819ce1c1)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
```
```
In lib/klist.c (ffffffff819cfe0e)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
```
```
In lib/kobject.c (ffffffff819d0b92)
Location: arch/x86/include/asm/atomic.h:195
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81032e93)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8103b13f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81041513)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81061607)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff81071642)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/cred.c (ffffffff810be86e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/ucount.c (ffffffff810c0d2d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810c1009)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810c4123)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810da422)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810efdd6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81a2d15f)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810f1f96)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810f5e6e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810fbd08)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff811064dc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/futex.c (ffffffff81136a94)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff8113a65d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8116f683)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff8117dc17)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81185710)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8118d17c)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8119a99b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/bpf/syscall.c (ffffffff811c4b20)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/btf.c (ffffffff811dcf8e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff811eecd8)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff811f5b00)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff811fd00d)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8121b1bd)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81239c78)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffffffff8124b7eb)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff81254620)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff81260b4b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81264c9e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff8126cc5b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81273b47)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff81a21b75)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8128509a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8128d4f5)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff81292e89)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8129d192)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812a5f09)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memfd.c (ffffffff812a8e4f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812aa052)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812b26c8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff812b64e1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812bf972)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/block_dev.c (ffffffff812f30f1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/notify/mark.c (ffffffff812fa425)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff81305059)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff8132efd6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81331ac3)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff813390b0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff8133d3fa)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff8133f50c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/mount.c (ffffffff813423c0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/kernfs/dir.c (ffffffff81344088)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff8134db65)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8136126c)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff813ebfec)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff813f0f43)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff813ff8df)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8140122b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8144df5c)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8145826c)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8145f25d)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814628a0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff81466860)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81469008)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8146a7c5)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In block/bsg-lib.c (ffffffff814c0373)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff814e2080)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff81504252)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff8150e962)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff815374bb)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81552307)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f07e7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8164b442)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164f3f1)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff8166c7cc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff81694c79)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff8169f595)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816b0873)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff8170849a)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff8170d9f5)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81717680)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff81756087)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff81757729)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff8177d56f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff8178562c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8179297f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817de4a4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818021e3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8180294b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81851e58)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81868f07)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8186ad22)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81a2345c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187aa42)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81895337)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8189eac2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/net_namespace.c (ffffffff818a831b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff818b4cc8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818c3c35)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818d7f0c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff818e949f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff818f2011)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/core/dst_cache.c (ffffffff818f3540)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/sched/cls_api.c (ffffffff818fdb47)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff8190e09d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819130d6)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff819178e8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81919042)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191d237)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f812)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8192128e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8192abaa)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f667)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8194164f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819451d8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff8194eaa7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff819509a2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81952c88)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff81968f6a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81970165)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81977708)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819790fc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81983061)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a9b0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b1b0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81998a86)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff8199a8e5)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819adfac)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff819be32d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c7e7c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d0798)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff819d4150)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff819da354)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff819dd37b)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3707)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81a07681)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In lib/klist.c (ffffffff81a0944e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In lib/kobject.c (ffffffff81a09e32)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81034ca3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8103d734)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064cf7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff810754c3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/cred.c (ffffffff810c486f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/ucount.c (ffffffff810c6e38)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810c70f1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810c9f20)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e1737)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810f7830)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81a9d32f)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810fa3f6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810fe404)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff811043d8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff8110fa67)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff81126079)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff81141d74)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:get_pi_state
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff81145f46)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117c882)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff8118ab17)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81192a50)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811a0527)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811a8632)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/syscall.c (ffffffff811d5d3c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff811e67a1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff811f25ee)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff8120659c)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff8120d887)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff812110d5)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In mm/filemap.c (ffffffff8121548e)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8122ae4f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff8124aefa)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffffffff8125dcae)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff812668f2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8127b738)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff8127f8bc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff8128808b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8128fc06)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff8129c532)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8129f70a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a7e8c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812adb8c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b8807)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812c1661)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff812c2e87)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812c680e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812cf129)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff812d3254)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812dcb03)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/block_dev.c (ffffffff81314b66)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In fs/notify/mark.c (ffffffff8131ae2a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff81326d7c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff81330cfa)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/posix_acl.c (ffffffff81347fcd)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff81356a56)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff813598a6)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff8136176e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff81365711)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff8136782d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff8136c2d9)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff8137654b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8138a316)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff81418246)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8141d212)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8142c01e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8142da47)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8147b8cc)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81485a29)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8148c6dd)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8148fb6c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff81491904)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81496064)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814977e5)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In block/bsg-lib.c (ffffffff814eeb72)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff8150df30)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff815323cb)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff8153df54)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81566e0d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81582256)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (ffffffff816227b7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81680442)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff816840e5)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff816a23c3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff816cd627)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff816d7d4d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816ea49b)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff817434e6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/dma-buf/reservation.c (ffffffff8174403f)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff817493d0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81752373)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff817921b3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff81793ee1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/cdrom/cdrom.c (ffffffff817b1eb9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817bc493)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817c43a8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817d1abd)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8181ef34)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81843a2f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81843ec9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818953a4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff818add58)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818aec33)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81a935c4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818c0aa9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff818e1c2c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818e9333)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff8190164e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff8191354c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81925c8c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff81938ed7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81944597)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/core/dst_cache.c (ffffffff819459f9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/core/bpf_sk_storage.c (ffffffff8195373e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff8195d486)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff8196fc02)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819756c5)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff81979f6e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8197b043)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8197f407)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982161)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983c49)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8198ddf9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a39e5)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5c4c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a97b7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff819b3286)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff819b5288)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819b74d4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819c8f76)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfe75)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819d4fac)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819d9a18)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e123a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e2c0a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ecccc)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff819f5655)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f66e1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a048f3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81a068a5)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a1bd72)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a2d5f5)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3696f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3fd7c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a42ff6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a48f4e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81a4c37a)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a52432)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81a76ffb)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In lib/klist.c (ffffffff81a78de9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In lib/kobject.c (ffffffff81a796a6)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810354d3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8103def4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065367)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff81076493)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810993e4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/cred.c (ffffffff810cd91f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/ucount.c (ffffffff810cff08)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810d01c1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810d3130)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810ebdd7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff81103660)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81ad4b0f)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff811061d6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff8110a809)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff8111078f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff8111bd27)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff81132049)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8114c0d1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/module.c (ffffffff81151ad6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81188702)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff81196a07)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8119e6d0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811abf57)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811b3e42)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/syscall.c (ffffffff811e06b2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff811f2ef1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff811fed0e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff8121393f)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff8121aeb7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff8121ed15)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In mm/filemap.c (ffffffff8122281e)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff81238d1f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff812593ea)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffffffff8126c47e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff81275212)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8128b218)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff8128f6ac)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff81297c8b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8129f996)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812abf91)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b0aaa)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b9380)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812bf6dc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812ca6e7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812d3591)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff812d4d1e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In mm/memfd.c (ffffffff812d7388)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812d8212)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812e01a9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff812e4de4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812ee652)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/notify/mark.c (ffffffff8132da1a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff81339b0c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff813446f7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/crypto/keyring.c (ffffffff8134c6c9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/verity/enable.c (ffffffff8134fe83)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff8136026d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff8136f08e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81371af6)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff813799ce)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff8137d9a1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff8137faad)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff81384489)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff8138e7bb)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813a2d4e)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff81432106)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81437062)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff81445d6e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff81447797)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8149559c)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8149f912)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814a659d)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814a9a2c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff814ab834)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff814aff94)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814b1715)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In block/bsg-lib.c (ffffffff81507fd2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff8152bd80)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff8155320b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff8155ed74)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8158816d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a3c90)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (ffffffff81644297)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8169e16a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816a2af2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a6795)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff816c5164)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff816f1467)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff816fbd1c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff8170e4fb)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81765b5f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8176748e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8176819d)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff8176d520)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff817765f3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff817b5d84)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff817b7a11)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff817d06ab)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In drivers/cdrom/cdrom.c (ffffffff817e2209)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817eccb3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817f4d48)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8180298d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff818503f4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818753b0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875839)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff818bce92)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818c73bc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff818e0208)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818e10df)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81acad7c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818f350b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81913dec)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8191b493)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff8193397c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81945bac)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff819582dc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff8196bd97)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81979597)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/core/dst_cache.c (ffffffff8197aa15)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/core/bpf_sk_storage.c (ffffffff81989ade)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81993986)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff819a6581)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819ac0e1)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff819b08ce)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819b19b3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b5947)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b89c1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba429)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819c49c9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da6e7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dca0c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e0477)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff819ea009)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff819ebfb2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819ee1d4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819ffb36)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06a05)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a0bb0c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a10878)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a185fa)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a19bfa)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23cdc)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c305)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d361)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b4e4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81a3d415)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a529f2)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a6415b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6d48f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a769ec)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a79b56)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a7fb3e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81a82f4a)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a89042)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81aae3db)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In lib/klist.c (ffffffff81ab0199)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In lib/kobject.c (ffffffff81ab0a06)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/events/core.c (ffffffff81007d89)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810374b3)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/alternative.c (ffffffff81bbe07f)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/process.c (ffffffff81040fab)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106bcc7)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff8107d4b3)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109eab4)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In kernel/cred.c (ffffffff810d757f)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In kernel/ucount.c (ffffffff810d9e1b)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810da112)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810dd8dd)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff810e9020)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/mutex.c (ffffffff8110e182)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/locking/spinlock.c (ffffffff81bcca4f)
Location: arch/x86/include/asm/atomic.h:202
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
In kernel/locking/qspinlock.c (ffffffff8110fcbb)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff81111206)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81114cc6)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff8112805a)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff81141472)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8115c399)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/module.c (ffffffff81160f03)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119ce42)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff811abd37)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811b5c40)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811c18f1)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_resize_saved_cmdlines
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cafb4)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811ccba2)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/irq_work.c (ffffffff811f750d)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
```
In kernel/bpf/helpers.c (ffffffff81214eb1)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff812260e3)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123014c)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff81234521)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_ctx_lock_double
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff81243e2a)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff81245831)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff8124a905)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
```
```
In mm/filemap.c (ffffffff8124ff4c)
Location: arch/x86/include/asm/atomic.h:202
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
In mm/swap.c (ffffffff812602f9)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff81267823)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81287e75)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In mm/mmap.c (ffffffff8129c20c)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff812a662e)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812be3ef)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff812c232e)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_find_get
  - mm/zswap.c:zswap_pool_last_get
```
```
In mm/hugetlb.c (ffffffff812cb34b)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812d400b)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812e13f2)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In mm/migrate.c (ffffffff812e6bea)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812ededf)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff812f5e75)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mc_handle_present_pte
```
```
In mm/memory-failure.c (ffffffff81300387)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff8130925c)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memfd.c (ffffffff8130c2f8)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff8130e2b4)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff81317a3d)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/super.c:grab_super
  - fs/super.c:deactivate_super
```
```
In fs/exec.c (ffffffff8131c674)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff813213f4)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/namei.c:handle_truncate
```
```
In fs/notify/mark.c (ffffffff81367b09)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff8137352e)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff81385e5d)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/io-wq.c (ffffffff8138b63a)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_get
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/crypto/keyring.c (ffffffff81392671)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/verity/enable.c (ffffffff813966f3)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff813a5d98)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff813b675e)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff813b95f9)
Location: arch/x86/include/asm/atomic.h:202
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
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813bdb68)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff813c2a6c)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff813c9a78)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_net
```
```
In fs/kernfs/dir.c (ffffffff813cf1b7)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:kernfs_get_active
```
```
In fs/configfs/item.c (ffffffff813d78f0)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff813d9f79)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813eee86)
Location: arch/x86/include/asm/atomic.h:202
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
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8140c6de)
Location: arch/x86/include/asm/atomic.h:202
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
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81430d2d)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff8148250b)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8148716c)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff81497686)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff81498f04)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff814ed7be)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff814f15da)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff814f8fa9)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
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
In security/apparmor/policy.c (ffffffff814fb734)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:update_to_newest_parent
  - security/apparmor/policy.c:update_to_newest_parent
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff814ff348)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8150143d)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81505934)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff815074b8)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8150a497)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:labelset_next_stale
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff8150dc79)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8150f3f9)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8150f9c9)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In block/blk-mq.c (ffffffff8154f202)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In block/bsg-lib.c (ffffffff815695c9)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff8158f875)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff815dc5d7)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/dec_and_lock.c (ffffffff815e8162)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In lib/klist.c (ffffffff815ea0db)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In lib/kobject.c (ffffffff815eaadb)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/phy/phy-core.c (ffffffff815ffed7)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8162eead)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164c8b0)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f23c3)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816fcaef)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81707811)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81750fd8)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817548ca)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff817586e5)
Location: arch/x86/include/asm/atomic.h:202
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
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serdev/core.c (ffffffff8176d9f2)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff817791bb)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/iommu/intel/svm.c (ffffffff817a975a)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff817b55e4)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817c9eab)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/power/wakeup.c (ffffffff817cf596)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81825e09)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81827b40)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818296cc)
Location: arch/x86/include/asm/atomic.h:202
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
In drivers/dma-buf/sw_sync.c (ffffffff8182bf3a)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/hosts.c (ffffffff8182faea)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff818398d4)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff81877d1d)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/spi/spi.c:pm_runtime_put_noidle
```
```
In drivers/net/loopback.c (ffffffff8187eb51)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff8189b807)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a2854)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In drivers/cdrom/cdrom.c (ffffffff818b0d8f)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff818bbac3)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818c41eb)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818d2921)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819499b1)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a169)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/edac/ghes_edac.c (ffffffff8198d4cf)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8199969c)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff819b3290)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b41df)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81bc327c)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8df2)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff819e3877)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819ee2da)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:skb_dump
```
```
In net/core/net_namespace.c (ffffffff819f99c4)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81a08623)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81a1622d)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a2d11e)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff81a3f9bc)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81a4efe3)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link_no_progs
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/dst_cache.c (ffffffff81a4fed3)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6118d)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81a6c91d)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f916)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a93f52)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81a97571)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff81a9a75e)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a9c1f7)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9fefa)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa3316)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4f06)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0b82)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5d5f)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9aef)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acdaa5)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81ad7c3d)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81ad9d21)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81adbf98)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81aef22b)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81af6419)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81afcfa3)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/ipmr.c (ffffffff81b022b1)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b09322)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0b256)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15cfc)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1c83c)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e77d)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1ff7b)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b30aa3)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b316b3)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b332ba)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b49c62)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv6/route.c:__rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81b58af5)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81b5cbbb)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6708f)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b70c50)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b747fb)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7a94e)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81b7d402)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff81b80123)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b847a7)
Location: arch/x86/include/asm/atomic.h:202
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In arch/x86/events/core.c (ffffffff81006e39)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81038573)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/alternative.c (ffffffff81c3691f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/process.c (ffffffff81040f0b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8106897f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106d5a7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff8107d423)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a614)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In kernel/cred.c (ffffffff810d2242)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In kernel/ucount.c (ffffffff810d4fcb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810d58f5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810da1ed)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff810e6dd5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/mutex.c (ffffffff8110b442)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/locking/spinlock.c (ffffffff81c455af)
Location: arch/x86/include/asm/atomic.h:200
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
In kernel/locking/qspinlock.c (ffffffff8110ce7b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff8110e386)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff811114f6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff81123b6a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff8113d712)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff81158699)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/module.c (ffffffff8115f93e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/kprobes.c (ffffffff81193420)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81199e82)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff811a95f7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811b3520)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811bf501)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_resize_saved_cmdlines
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8694)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811ca0e2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/irq_work.c (ffffffff811f5ece)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff81216aa1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff8122cc73)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812385fc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff8123ee52)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_ctx_lock_double
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8124e4ba)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff8124fe51)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff81254ca5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
```
```
In mm/filemap.c (ffffffff8125a156)
Location: arch/x86/include/asm/atomic.h:200
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
In mm/swap.c (ffffffff8126a429)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8127260b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff8128cb99)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81291835)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In mm/mmap.c (ffffffff812a7555)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff812b1ac3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812ca004)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff812ce027)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_find_get
  - mm/zswap.c:zswap_pool_last_get
```
```
In mm/hugetlb.c (ffffffff812d6f84)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812df9fb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812ec2aa)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In mm/migrate.c (ffffffff812f1f3a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812f954f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff81301275)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8130c637)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff813150b0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memfd.c (ffffffff8131823c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff8131a397)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff81322c9d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/super.c:grab_super
  - fs/super.c:deactivate_super
```
```
In fs/exec.c (ffffffff813281c5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff8132c994)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/namei.c:handle_truncate
```
```
In fs/kernel_read_file.c (ffffffff81365b73)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/notify/mark.c (ffffffff81374e89)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff813813de)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff813919fa)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/io-wq.c (ffffffff8139c81a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_get
  - fs/io-wq.c:io_impersonate_work
```
```
In fs/crypto/keyring.c (ffffffff813a39f2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/verity/enable.c (ffffffff813a8413)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff813b6ad9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff813c86be)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff813cb009)
Location: arch/x86/include/asm/atomic.h:200
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
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813cf8b8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff813d4bfa)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff813dbace)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff813e0de7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:kernfs_get_active
```
```
In fs/configfs/item.c (ffffffff813e94f0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff813ebc30)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff814015fa)
Location: arch/x86/include/asm/atomic.h:200
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
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8141fb4e)
Location: arch/x86/include/asm/atomic.h:200
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
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81449afd)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff8149fb9b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814a478c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff814b5136)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff814b6984)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8150ae3e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff8150e87a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff815160e9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
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
In security/apparmor/policy.c (ffffffff81518781)
Location: arch/x86/include/asm/atomic.h:200
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
In security/apparmor/procattr.c (ffffffff8151c588)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8152161d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81522a69)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81524568)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8152730d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:labelset_next_stale
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff8152aadf)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8152c239)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8152c80d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In block/blk-mq.c (ffffffff8156b1b2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In block/bsg-lib.c (ffffffff81584049)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff815ac3a5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff815fa257)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/dec_and_lock.c (ffffffff8160d322)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In lib/klist.c (ffffffff8160ea1b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In lib/kobject.c (ffffffff8160f3fb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/phy/phy-core.c (ffffffff81624dc7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8165456d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670c00)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170f783)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81719a2f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81724a61)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/events/events_base.c (ffffffff817324f1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:channels_on_cpu_inc
```
```
In drivers/tty/vt/vt.c (ffffffff8176ca08)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8176fbca)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff817737a5)
Location: arch/x86/include/asm/atomic.h:200
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
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serdev/core.c (ffffffff817883d2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff817939cb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/iommu/intel/svm.c (ffffffff817b5b2c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff817c9d90)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817dde46)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/power/wakeup.c (ffffffff817e3b96)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818367fb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818385b5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818393bd)
Location: arch/x86/include/asm/atomic.h:200
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
In drivers/dma-buf/sw_sync.c (ffffffff8183cf9a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/hosts.c (ffffffff81c165fc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184a154)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff8188652d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/spi/spi.c:pm_runtime_put_noidle
```
```
In drivers/spi/spi-mem.c (ffffffff8188bef5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/net/loopback.c (ffffffff8188d0d1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff818aa417)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2574)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In drivers/cdrom/cdrom.c (ffffffff81c1a585)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff818c88a3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818d00db)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818dcd11)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f571)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fcf9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/edac/ghes_edac.c (ffffffff8199109c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8199c77c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff819b57e0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b682f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81c3c1a9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81c2dbe6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff819e33cc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819edf7a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/net_namespace.c (ffffffff819f950a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81a09bd1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81a16e8e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a2eea2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff81a42682)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81a54bb1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link_no_progs
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/dst_cache.c (ffffffff81a55f10)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69fe5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_frag.c (ffffffff81a6f3ff)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/sched/cls_api.c (ffffffff81a752c7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81a99906)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a9de8e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81aa1531)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff81aa46b6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81aa6057)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaa786)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aad846)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf569)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81abbbd2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1bef)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5a3f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad9ae7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81ae428d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81ae6781)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ae8af4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81afc173)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81b0328a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81b0af5e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/ipmr.c (ffffffff81b10652)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17b45)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b194f6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b2416c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2b018)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2d0bf)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e88b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f6d3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b402a3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b41be2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b58882)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/route.c:__rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81b6712a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81b6b3fd)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b7566a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7f660)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b8356b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b8989e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81b8c5a2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f2a6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b94107)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81bc5ab0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
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
In arch/x86/events/core.c (ffffffff81007559)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103a0b3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/alternative.c (ffffffff81c28dc2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/process.c (ffffffff8104290b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068bc7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106e017)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff8107e7c1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109add4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In kernel/cred.c (ffffffff810d3e22)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In kernel/ucount.c (ffffffff810d6ca8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810d756e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810dbe60)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff810f6a68)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/mutex.c (ffffffff8110d262)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/locking/spinlock.c (ffffffff81c3883f)
Location: arch/x86/include/asm/atomic.h:200
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
In kernel/locking/qspinlock.c (ffffffff8110ebc0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff8110ee96)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81111f46)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff81123eca)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff8113e962)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff81159919)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/module.c (ffffffff811601fe)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
```
```
In kernel/kprobes.c (ffffffff811943d0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119acb2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff811aa1bd)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811b5720)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811bde18)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:trace_save_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c994d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811cb4a2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/irq_work.c (ffffffff811f6dbe)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff812197e1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff81231a23)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff81237c94)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123cdec)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff8124de96)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff81252dba)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff81254731)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff81259255)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
```
```
In mm/filemap.c (ffffffff8125e120)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
```
```
In mm/swap.c (ffffffff8126f53c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff812777d8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff812919f0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8129755a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In mm/mmap.c (ffffffff812ad28c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff812b7193)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff812c69c9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In mm/swapfile.c (ffffffff812d0a80)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff812d4c58)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff812de586)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812e6c1b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812f8275)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff813003b1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff81307575)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813143dc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff8131b7a7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memfd.c (ffffffff8131e429)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff81320477)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff81328d5d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/super.c:grab_super
  - fs/super.c:deactivate_super
```
```
In fs/exec.c (ffffffff8132e0e9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff813367b7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/kernel_read_file.c (ffffffff8136c5b3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/notify/mark.c (ffffffff8137b849)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff81387d86)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8139775d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/io-wq.c (ffffffff813a2382)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_activate_free_worker
```
```
In fs/crypto/keyring.c (ffffffff813aac32)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/verity/enable.c (ffffffff813af46c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff813bdb39)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff813cf6fe)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff813d2046)
Location: arch/x86/include/asm/atomic.h:200
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
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813d6986)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff813dba36)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff813e29ee)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff813e7917)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:kernfs_get_active
```
```
In fs/configfs/item.c (ffffffff813f0060)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff813f2170)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81407c32)
Location: arch/x86/include/asm/atomic.h:200
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
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8142641b)
Location: arch/x86/include/asm/atomic.h:200
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
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff8144f47d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff814a5b9b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814aa75c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff814bafe6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff814bc7d0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff815115ba)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff81515276)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8151ca6f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
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
In security/apparmor/policy.c (ffffffff8151efd9)
Location: arch/x86/include/asm/atomic.h:200
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
In security/apparmor/procattr.c (ffffffff81522d5c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81527a0d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81528c45)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8152a742)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8152cfd9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff81530cec)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff815324d9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81532b49)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/fs.c (ffffffff815390f0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In block/blk-mq-tag.c (ffffffff81578ebf)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In block/bsg-lib.c (ffffffff8158ae49)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff815b7075)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff815dce37)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/dec_and_lock.c (ffffffff815f0a82)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In lib/klist.c (ffffffff815f21ab)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In lib/kobject.c (ffffffff815f2b3b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/phy/phy-core.c (ffffffff81608777)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81636f1d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816530b6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0fc7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816fad2f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81705d21)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/events/events_base.c (ffffffff81717b2a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/tty/vt/vt.c (ffffffff81750598)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81753582)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff81757165)
Location: arch/x86/include/asm/atomic.h:200
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
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serdev/core.c (ffffffff8176bd22)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff81776b81)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/iommu/intel/svm.c (ffffffff81798e4e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff817ad5a8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817c21c6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/power/wakeup.c (ffffffff817c7fd6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/mfd/arizona-irq.c (ffffffff817ee0ba)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818199cb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181b895)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c675)
Location: arch/x86/include/asm/atomic.h:200
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
In drivers/dma-buf/sw_sync.c (ffffffff8181ff76)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/hosts.c (ffffffff81c08187)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182d8d4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff81868d9d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/spi/spi.c:pm_runtime_put_noidle
```
```
In drivers/spi/spi-mem.c (ffffffff8186e855)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/net/loopback.c (ffffffff8186fa11)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff8188d92e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
  - drivers/vfio/vfio.c:vfio_group_get_device
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895894)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In drivers/cdrom/cdrom.c (ffffffff81c0c471)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff818a9dee)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff818abee3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818b370b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818c0081)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81933a04)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933bb9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/edac/ghes_edac.c (ffffffff8197560c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8198144c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81999e70)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8199afdf)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81c2e649)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81c1fd95)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff819cae81)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819d773a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/net_namespace.c (ffffffff819df66a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff819f0562)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff819fdb36)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a16452)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff81a2738e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/dst_cache.c (ffffffff81a38f20)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/core/sock_map.c (ffffffff81a515a2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81a524e5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_frag.c (ffffffff81a57cd2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/sched/cls_api.c (ffffffff81a5dc67)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81a84c16)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a88db3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c481)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff81a8f7ab)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a91217)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a95d35)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98911)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a879)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6b92)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abcbff)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0a9e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac4b35)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81acf428)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81ad1a51)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ad3daf)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae7883)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81aeea32)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af62fa)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/ipmr.c (ffffffff81afe262)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0571d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81b05d1b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b06f86)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11d9c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81b18c49)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1ad04)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c5e9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d571)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e8b3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b2f8ce)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b46b6d)
Location: arch/x86/include/asm/atomic.h:200
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
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81b55304)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81b59750)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6409a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6e180)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b721de)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b786ee)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81b7b5d8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ec66)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83217)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81bb662f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
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
In arch/x86/events/core.c (ffffffff81007dc5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103fa63)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/alternative.c (ffffffff81d46f52)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/process.c (ffffffff81048c79)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072f92)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81079837)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff8108d441)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab0b4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In kernel/fork.c (ffffffff810b3320)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/cred.c (ffffffff810e6ef2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/kmod.c (ffffffff810eae1e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810f01bc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
  - kernel/sched/core.c:sched_core_put
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/sched/fair.c (ffffffff811109ec)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/mutex.c (ffffffff8112caa2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/locking/spinlock.c (ffffffff81d5711f)
Location: arch/x86/include/asm/atomic.h:200
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
In kernel/locking/qspinlock.c (ffffffff8112e3f0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff8112e736)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81131f66)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff811444aa)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff81161df2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8117f7a3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:get_pi_state
```
```
In kernel/module.c (ffffffff811853ae)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/module.c:module_put
  - kernel/module.c:try_module_get
```
```
In kernel/kprobes.c (ffffffff811bd270)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811c4c52)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff811d3d2d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811df840)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811edf2a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:trace_save_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f541d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811f7932)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/irq_work.c (ffffffff8122838e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff8124f956)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
```
```
In kernel/bpf/btf.c (ffffffff8126a9c3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff81272264)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8127786c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff81288be7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8128e6aa)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff81290161)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff81294f15)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
```
```
In mm/filemap.c (ffffffff8129a84b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
```
```
In mm/oom_kill.c (ffffffff812a31dc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
```
```
In mm/swap.c (ffffffff812ac68c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff812b5187)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff812d12b7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff812d7f0e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In mm/mmap.c (ffffffff812ee9af)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff812f95b3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff8130b470)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In mm/swapfile.c (ffffffff8131615b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff8131afc6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff81325876)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8132eb4b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff813428cb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8134a019)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff813512e5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8135f7c9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff81368a77)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memfd.c (ffffffff8136b7ff)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff8136da30)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff8137638d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/super.c:grab_super
  - fs/super.c:deactivate_super
```
```
In fs/exec.c (ffffffff8137b8dd)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff81384197)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/kernel_read_file.c (ffffffff813bb283)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/notify/mark.c (ffffffff813c8606)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff813d5093)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff813df07f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/io-wq.c (ffffffff813f18f3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:io_wqe_activate_free_worker
```
```
In fs/crypto/keyring.c (ffffffff813fa4c2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/verity/enable.c (ffffffff813ff01c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff8140d929)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff81420ade)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81423576)
Location: arch/x86/include/asm/atomic.h:200
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
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff814280b6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff8142d0d0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff814344fe)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff81439627)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:kernfs_get_active
```
```
In fs/configfs/item.c (ffffffff81441f50)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff81444150)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8145a4fd)
Location: arch/x86/include/asm/atomic.h:200
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
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8147a0cb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff814a2ffd)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/orphan.c (ffffffff814b1096)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/fuse/file.c (ffffffff814edea9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In fs/debugfs/file.c (ffffffff814fdd3b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81502c1c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff8150c510)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff81513816)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff815151f0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8156f1ba)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff81573226)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8157ab40)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
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
In security/apparmor/policy.c (ffffffff8157d179)
Location: arch/x86/include/asm/atomic.h:200
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
In security/apparmor/procattr.c (ffffffff81580fcc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81585c9d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81586f6e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81588ae2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8158b3c9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff8158f12c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81590a59)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff815910c9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/fs.c (ffffffff81597930)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In block/blk-mq-tag.c (ffffffff815de112)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In block/bsg-lib.c (ffffffff815efe39)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff8161d685)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff81648797)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/dec_and_lock.c (ffffffff8165dbc2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In lib/klist.c (ffffffff8165f31b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In lib/kobject.c (ffffffff8165fd1b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/phy/phy-core.c (ffffffff816773b7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff816a715d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c4e26)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176b0d7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8177571f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81781601)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/events/events_base.c (ffffffff81795348)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/tty/vt/vt.c (ffffffff817d2e37)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d69b2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff817da9a5)
Location: arch/x86/include/asm/atomic.h:200
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
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serdev/core.c (ffffffff817f1452)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff817fc551)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/iommu/iommu-sva-lib.c (ffffffff8182fb93)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva-lib.c:__mmget_not_zero
```
```
In drivers/base/core.c (ffffffff8183685a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff8184bb26)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_release_supplier
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/power/wakeup.c (ffffffff81852406)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a5d25)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a6a3e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa636)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/hosts.c (ffffffff81d0c00b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b9324)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff818f894d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/spi/spi.c:pm_runtime_put_noidle
```
```
In drivers/spi/spi-mem.c (ffffffff818fe963)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/net/loopback.c (ffffffff818fffb5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff81920f78)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
  - drivers/vfio/vfio.c:vfio_group_get_device
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81929804)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In drivers/cdrom/cdrom.c (ffffffff81d12edf)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff8193ecfe)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81940f68)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81948b9b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81956706)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81994f09)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6dd4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d6fe9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/edac/ghes_edac.c (ffffffff81a1e318)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81a2a83e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81a4668c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81a4791d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81d4cd09)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d316f7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81a7a4b1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81a85f7a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/net_namespace.c (ffffffff81a8fa4a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81aa1990)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81aaf103)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81acccfc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81ad1be6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81adc121)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/dst_cache.c (ffffffff81aeedf0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/core/devlink.c (ffffffff81b027f6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/core/sock_map.c (ffffffff81b09522)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b5ee)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_frag.c (ffffffff81b10c9a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/sched/cls_api.c (ffffffff81b16e27)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f349)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81b43523)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81b4749f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff81b4a9eb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81b4c5ab)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b51195)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b53df1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55ce9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81b63192)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7998f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e462)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b832e5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81b8de48)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81b90681)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81b92a6f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba779e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81baee02)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb7daa)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/ipmr.c (ffffffff81bbf4f2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc826d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc8a09)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc9e06)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd591a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdd039)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf271)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0f2b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/unix_bpf.c (ffffffff81beb794)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3721)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4c7e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81bf5c4e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81c0ddbd)
Location: arch/x86/include/asm/atomic.h:200
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
In net/ipv6/udp.c (ffffffff81c1ddd1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81c20d79)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2bb5a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c361a9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c68e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81c4322e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81c46591)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a3cf)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4f2e7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81c8563f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
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
In arch/x86/events/core.c (ffffffff81007308)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810471d1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/alternative.c (ffffffff81f15512)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/process.c (ffffffff81051f7e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e7db)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8108160a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810885c4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff8109d693)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c0d14)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In kernel/fork.c (ffffffff810c9540)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/cred.c (ffffffff8110119a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/kmod.c (ffffffff81105c80)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff8110d77c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
  - kernel/sched/core.c:sched_core_put
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/sched/fair.c (ffffffff8112cbc0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/mutex.c (ffffffff8114dcee)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/locking/spinlock.c (ffffffff8114ed2b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_nested
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8114f603)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff8114fa38)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81153c76)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff81167f11)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/rcu/tree.c (ffffffff81180042)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/module/main.c (ffffffff8118ae4a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
```
```
In kernel/stacktrace.c (ffffffff81194cfc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff811b242b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff811b4b46)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/futex/requeue.c (ffffffff811b6452)
Location: arch/x86/include/asm/atomic.h:200
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
In kernel/debug/kdb/kdb_main.c (ffffffff811f85f2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff81208898)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81213609)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff8122628c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:trace_save_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122ec77)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff812314c1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/rethook.c (ffffffff81268c73)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
```
```
In kernel/irq_work.c (ffffffff8126931e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff81296bb4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
```
```
In kernel/bpf/btf.c (ffffffff812b7809)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff812c1592)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c750b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff812dde96)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff812e3577)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff812e5221)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff812eaae4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
```
```
In mm/filemap.c (ffffffff812f1494)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/vmscan.c (ffffffff8130d68b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff81330a66)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81337e1a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/gup.c:try_get_folio
```
```
In mm/mmap.c (ffffffff81351d81)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff8135fe90)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff813741c2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In mm/swapfile.c (ffffffff813812f0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff8138604e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff81394470)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/ksm.c (ffffffff8139ec13)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff813b3010)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff813c0a60)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff813c9d31)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813dd08f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff813e65d8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memfd.c (ffffffff813e997a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff813ebb5b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff813f5551)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff813fc175)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff814052e8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/kernel_read_file.c (ffffffff814411ee)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/notify/mark.c (ffffffff8144fbd6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff8145d699)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/crypto/keyring.c (ffffffff8146d642)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/verity/enable.c (ffffffff81472bbc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff81482c10)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff81498913)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff8149c196)
Location: arch/x86/include/asm/atomic.h:200
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
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff8149df70)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff814a6a88)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff814ae617)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff814b46a7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:kernfs_get_active
```
```
In fs/configfs/item.c (ffffffff814bdbb0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff814c0044)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff814d8219)
Location: arch/x86/include/asm/atomic.h:200
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
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff814fc36b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff8152a4a4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/orphan.c (ffffffff81539b41)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/fuse/file.c (ffffffff8157d2a7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In fs/debugfs/file.c (ffffffff8158e92b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff815941db)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff8159e480)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff815a5cb0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff815a797f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8160d6f3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff81610529)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81618dd7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
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
In security/apparmor/policy.c (ffffffff8161b7f7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff81620183)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81626824)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/resource.c (ffffffff81627397)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff816291b3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8162c935)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff81630161)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81631bb6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81632c46)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/fs.c (ffffffff8163c09f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In block/blk-mq-tag.c (ffffffff8168c00a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In block/bsg-lib.c (ffffffff816a0f36)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io_uring.c (ffffffff816ce692)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_link_timeout_fn
```
```
In io_uring/io-wq.c (ffffffff816da2b2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wqe_activate_free_worker
```
```
In lib/refcount.c (ffffffff816eb175)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff8175ebc7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/dec_and_lock.c (ffffffff817771de)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In lib/klist.c (ffffffff81778eeb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In lib/kobject.c (ffffffff8177985b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/phy/phy-core.c (ffffffff81792441)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff817c9be6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817eab26)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189fcc0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/clk/clk.c (ffffffff818aba60)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff818b7faf)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/events/events_base.c (ffffffff818ce06e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/tty/vt/vt.c (ffffffff81910df0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81914a92)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff81919910)
Location: arch/x86/include/asm/atomic.h:200
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
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serdev/core.c (ffffffff81931a5f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff8193b1af)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/iommu/iommu-sva-lib.c (ffffffff81970d93)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva-lib.c:__mmget_not_zero
```
```
In drivers/base/core.c (ffffffff81978869)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/power/runtime.c (ffffffff819915bf)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/power/wakeup.c (ffffffff81998276)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819efc97)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f07b7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4e28)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/hosts.c (ffffffff81ed4f41)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a04fa9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff81a4d71f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff81a502ca)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/net/loopback.c (ffffffff81a51a74)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff81a786e1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:__vfio_register_dev
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a810c7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
```
```
In drivers/cdrom/cdrom.c (ffffffff81eddd0a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81a96dcf)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81a99386)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81aa16d9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81ab0313)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81af1b9c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b39982)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39c27)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81b86a52)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81b94b7e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb4336)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81bb58a4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81f1c949)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81efdbbc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81bedee2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81bf880a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/net_namespace.c (ffffffff81c03d47)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81c19ac3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81c27e7e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81c499dc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81c4f459)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81c5d46b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/dst_cache.c (ffffffff81c71d4a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/core/devlink.c (ffffffff81c86c51)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_try_get
```
```
In net/core/sock_map.c (ffffffff81c8f640)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91bee)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_frag.c (ffffffff81c97e1c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/sched/cls_api.c (ffffffff81c9e7d6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81ccbaa7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81ccffe9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81cd463f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff81cd784f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81cd9bff)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cddf3b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce1a0e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce39ec)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1e47)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09721)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e44c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d138ee)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81d1f08b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81d21b05)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81d2408b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39fdb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81d42153)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81d4bb5e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/ipmr.c (ffffffff81d5428c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5dafc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5dfd0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5f4f8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c174)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81d73e01)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75fd7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77c7a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/unix_bpf.c (ffffffff81d8397c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81d89e8f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81d8daa4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81d8ee1e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81da8dc3)
Location: arch/x86/include/asm/atomic.h:200
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
In net/ipv6/udp.c (ffffffff81dba366)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81dbdb41)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc90dc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd3da8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81ddaa6b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81de1fae)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81de5a30)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff81de9ac3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81defcef)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81e2b853)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/device.c (ffffffff81e387c4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff81e3ac3c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
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
In arch/x86/events/core.c (ffffffff81008b78)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81051431)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/alternative.c (ffffffff820bc9de)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/process.c (ffffffff8105f7ae)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810902c4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093eea)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c077)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff810b47a4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/mm/kmmio.c (ffffffff810d1f72)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dcd24)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In kernel/fork.c (ffffffff810e6a9c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/cred.c (ffffffff811262aa)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/smpboot.c (ffffffff8112a0fe)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:cpu_wait_death
```
```
In kernel/kmod.c (ffffffff8112b79c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff81133f1c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
  - kernel/sched/core.c:sched_core_put
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/sched/fair.c (ffffffff811568c0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/mutex.c (ffffffff8117ceae)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/locking/spinlock.c (ffffffff8117df3e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_nested
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qspinlock.c (ffffffff820d68d3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff820d6d98)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff811831c6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff8119c3c1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/rcu/tree.c (ffffffff811ba50d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/module/main.c (ffffffff811c750a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
```
```
In kernel/stacktrace.c (ffffffff811d29fc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff811f32ab)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff811f5c16)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/futex/requeue.c (ffffffff811f7592)
Location: arch/x86/include/asm/atomic.h:200
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
In kernel/debug/kdb/kdb_main.c (ffffffff8123fa52)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff81250da8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8125cdd8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff81271572)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:trace_save_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127ac98)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8127da41)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/rethook.c (ffffffff812baf33)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
```
```
In kernel/irq_work.c (ffffffff812be14e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff812f1b29)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
```
```
In kernel/bpf/ringbuf.c (ffffffff81304af9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
```
```
In kernel/bpf/btf.c (ffffffff81318e69)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff81324e92)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132cedb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff8133fb1e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:get_pmu_ctx
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8134bc07)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff8134ebce)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff81354a44)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
  - kernel/jump_label.c:static_key_fast_inc_not_disabled
```
```
In mm/filemap.c (ffffffff8135be34)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/vmscan.c (ffffffff81379c0a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/compaction.c (ffffffff813a7694)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813af491)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/mmap.c (ffffffff813cb999)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff813dad79)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff813f1c95)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In mm/swapfile.c (ffffffff813ffb33)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81403e7e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff81412ecd)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/ksm.c (ffffffff8141e253)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81433450)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff814387f9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
```
```
In mm/huge_memory.c (ffffffff8144296b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff8144f301)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81463e99)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff8146e0c8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/memfd.c (ffffffff8147199a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff81473fcd)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff8147e7c1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff81485be5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff8148f735)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/kernel_read_file.c (ffffffff814d012f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/notify/mark.c (ffffffff814de506)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff814ed1b9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/aio.c (ffffffff814f0990)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In fs/crypto/keyring.c (ffffffff814fee72)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/verity/enable.c (ffffffff81504913)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/mbcache.c (ffffffff81514f99)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/posix_acl.c (ffffffff815159c0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff8152cbd1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81530ab6)
Location: arch/x86/include/asm/atomic.h:200
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
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff81532c30)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff8153c0c8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff81544c57)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff8154b5a8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:kernfs_get_active
```
```
In fs/configfs/item.c (ffffffff815558f0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff8155815d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81570f9a)
Location: arch/x86/include/asm/atomic.h:200
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
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81596b36)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/super.c (ffffffff815c8e64)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/orphan.c (ffffffff815d8071)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/fuse/file.c (ffffffff81622f07)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In fs/debugfs/file.c (ffffffff816359bb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8163cdcb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff81647b00)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff8164fad0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff816519df)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff816bf673)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff816c2f89)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff816cbc39)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff816ce8cc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff816d366d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff816da6c4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/resource.c (ffffffff816db3a2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff816ddaa1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff816e13e5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff816e4de3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff816e68de)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff816e7a96)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff816ea013)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/landlock/fs.c (ffffffff816f3879)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In block/blk-mq-tag.c (ffffffff8174a77a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In block/blk-rq-qos.c (ffffffff8175d263)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/bsg-lib.c (ffffffff8175fb06)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In block/blk-iocost.c (ffffffff8176b279)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/io_uring.c (ffffffff8178882e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_unregister
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/timeout.c (ffffffff81798f2e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
```
```
In io_uring/poll.c (ffffffff8179c560)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_get_ownership_slowpath
```
```
In io_uring/io-wq.c (ffffffff817a6362)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wqe_activate_free_worker
```
```
In lib/refcount.c (ffffffff817db7f5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff8188c4e7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/sbitmap.c (ffffffff818a2d3e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/phy/phy-core.c (ffffffff818a6e61)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff818e7616)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81910d56)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e90c0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/clk/clk.c (ffffffff819f7160)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81a0527f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/events/events_base.c (ffffffff81a1f6d1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/tty/vt/vt.c (ffffffff81a6bcb0)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a6fc72)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a755a0)
Location: arch/x86/include/asm/atomic.h:200
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
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serdev/core.c (ffffffff81a903df)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff81a9b86f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/iommu/iommu-sva.c (ffffffff81adbe88)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
  - drivers/iommu/iommu-sva.c:__mmget_not_zero
```
```
In drivers/base/core.c (ffffffff81ae5024)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/power/runtime.c (ffffffff81b0196f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/power/wakeup.c (ffffffff81b092c6)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d2e7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6e6f7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b722d8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/hosts.c (ffffffff81b76f11)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b83c59)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff81bd7b32)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81bd943a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/net/loopback.c (ffffffff81bdacb4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/cdrom/cdrom.c (ffffffff81c0c347)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c19975)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81c1d356)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81c26f69)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c38415)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81c7ed66)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccf07a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf587)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81d25a23)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d34c7e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81d58996)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81d5a10b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff820c49a2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d75348)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81d9a7b2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81da768a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/net_namespace.c (ffffffff81db3417)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81dcaa78)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81ddaa5e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81dfec10)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81e04a40)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81e13c1b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/dst_cache.c (ffffffff81e29e4a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/core/devlink.c (ffffffff81e418f1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_try_get
```
```
In net/core/sock_map.c (ffffffff81e4aa6c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4d1be)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_frag.c (ffffffff81e53dbc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/sched/cls_api.c (ffffffff81e5af66)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b8f7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81e901c5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81e9490f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff81e97ecd)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81e9a38f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1833)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea2bce)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea642b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp.c (ffffffff81eacc87)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_read_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81eb66b7)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece9f1)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3efc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed98ae)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81ee61a3)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81ee8f45)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81eeb71b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f0293b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0af93)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81f1516e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/ipmr.c (ffffffff81f1e46c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f277ac)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81f287b9)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f29bb8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f374d4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3fd79)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42717)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f444bc)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/unix_bpf.c (ffffffff81f5117c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81f57e39)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bbd4)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f5d30e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81f784c3)
Location: arch/x86/include/asm/atomic.h:200
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
In net/ipv6/ip6_fib.c (ffffffff81f7d80f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In net/ipv6/udp.c (ffffffff81f8a42a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81f8e050)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f99f1c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa53b8)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81fac77a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb44de)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81fb8250)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/seg6_local.c (ffffffff81fbd203)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3def)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff82003a23)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/device.c (ffffffff82011a94)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff8201420c)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In lib/dec_and_lock.c (ffffffff8201fc6e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In lib/klist.c (ffffffff82021d0b)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In lib/kobject.c (ffffffff820227fb)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
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
In arch/x86/events/core.c (ffffffff810083a8)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81052191)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/alternative.c (ffffffff8213e24e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/process.c (ffffffff81060f0e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810931db)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096e73)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109efd7)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109fa60)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In arch/x86/kernel/hpet.c (ffffffff810b7882)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/mm/kmmio.c (ffffffff810d53e2)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e8304)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In kernel/fork.c (ffffffff810f2456)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/cpu.c (ffffffff810f96f1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_kick_ap_alive
  - kernel/cpu.c:cpuhp_wait_for_sync_state
```
```
In kernel/cred.c (ffffffff8113375a)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff81142c1b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
  - kernel/sched/core.c:sched_core_put
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/sched/fair.c (ffffffff8116693a)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/mutex.c (ffffffff8118db5e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/locking/spinlock.c (ffffffff8118ebde)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_nested
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qspinlock.c (ffffffff82159cc3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff8215a128)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81194036)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff811ae211)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/rcu/tree.c (ffffffff811cce4d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/module/main.c (ffffffff811da39f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
```
```
In kernel/stacktrace.c (ffffffff811e6cec)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff81207a2b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff8120a416)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/futex/requeue.c (ffffffff8120bd32)
Location: arch/x86/include/asm/atomic.h:113
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
In kernel/debug/kdb/kdb_main.c (ffffffff81256ac2)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff81268128)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81273dc8)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/trace/trace.c (ffffffff81288862)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:trace_save_cmdline
  - kernel/trace/trace.c:tracing_stop
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812927b8)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8129a4c1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/rethook.c (ffffffff812deb33)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_try_get
```
```
In kernel/irq_work.c (ffffffff812e4d0e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff81321361)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_acquire
  - kernel/bpf/helpers.c:bpf_refcount_acquire_impl
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
```
```
In kernel/bpf/ringbuf.c (ffffffff813334b2)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
```
```
In kernel/bpf/btf.c (ffffffff81348c89)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff813550f2)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/core.c (ffffffff81370ae5)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:get_pmu_ctx
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8137cc57)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff8137fd64)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff81385dd4)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
  - kernel/jump_label.c:static_key_fast_inc_not_disabled
```
```
In mm/filemap.c (ffffffff8138e113)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
```
```
In mm/vmscan.c (ffffffff813a927e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/compaction.c (ffffffff813daeb2)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813e3ba1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813ea8de)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
```
```
In mm/mmap.c (ffffffff8140026d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff8140ad9d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/rmap.c:set_tlb_ubc_flush_pending
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff81425841)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/swapfile.c (ffffffff814329c3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81436ce7)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff814464f1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_hugetlb_folio
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/ksm.c (ffffffff81452ee3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81469144)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8146e4f9)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
```
```
In mm/huge_memory.c (ffffffff8147829f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff81484d31)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814999ae)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff814a2ad5)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
```
```
In mm/memfd.c (ffffffff814a62ec)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff814a8879)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff814b34f1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff814b98d5)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff814c1f21)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/kernel_read_file.c (ffffffff815063d2)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/notify/mark.c (ffffffff81514d36)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff815262fa)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/aio.c (ffffffff81527730)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In fs/crypto/keyring.c (ffffffff81536480)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/verity/enable.c (ffffffff8153c015)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/mbcache.c (ffffffff8154c999)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/posix_acl.c (ffffffff8154d49c)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff81565007)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81568c36)
Location: arch/x86/include/asm/atomic.h:113
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
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff8156ae23)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff815743f3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff8157c847)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff815831f8)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:kernfs_get_active
```
```
In fs/configfs/item.c (ffffffff8158d690)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff8158fe80)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815a8d2d)
Location: arch/x86/include/asm/atomic.h:113
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
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff815cd4e8)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
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
In fs/ext4/super.c (ffffffff81600c24)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/orphan.c (ffffffff8160fc01)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/fuse/file.c (ffffffff8165b387)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In fs/debugfs/file.c (ffffffff8166dccb)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff816752db)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff81680023)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff816883b0)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8168a28f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff816f8183)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff816fbb39)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff817049ac)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
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
In security/apparmor/policy.c (ffffffff817074e7)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff8170c53d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff817136b4)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_uring_sqpoll
  - security/apparmor/lsm.c:apparmor_uring_override_creds
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/resource.c (ffffffff81714a8a)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff817170c1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8171a9e5)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff8171e44d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81720013)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81721216)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff81724263)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/landlock/fs.c (ffffffff8172d9a9)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In crypto/ahash.c (ffffffff81744cae)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff817461bd)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
```
```
In block/blk-mq-tag.c (ffffffff81786e5a)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In block/blk-rq-qos.c (ffffffff8179bfc7)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/bsg-lib.c (ffffffff8179e9e6)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In block/blk-iocost.c (ffffffff817aa359)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/io_uring.c (ffffffff817c8f0e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_unregister
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/timeout.c (ffffffff817d9dde)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
```
```
In io_uring/poll.c (ffffffff817dd790)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_get_ownership_slowpath
```
```
In io_uring/io-wq.c (ffffffff817e72cb)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wq_activate_free_worker
```
```
In lib/refcount.c (ffffffff8181aa65)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff818ce957)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/sbitmap.c (ffffffff818e5217)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/phy/phy-core.c (ffffffff818e9cd1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8192ac36)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81954476)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a317d0)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81a3f360)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81a4e2bf)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/events/events_base.c (ffffffff81a688d1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/tty/vt/vt.c (ffffffff81ab63d0)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba422)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abfd90)
Location: arch/x86/include/asm/atomic.h:113
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
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serdev/core.c (ffffffff81adbbef)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff81ae71cf)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b2a0ab)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In drivers/base/core.c (ffffffff81b3353e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/power/runtime.c (ffffffff81b4fa9f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/power/wakeup.c (ffffffff81b572e6)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0a18)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc1f07)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5ce8)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/hosts.c (ffffffff81bcaba1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd79b1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff81c2e555)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81c2fe3a)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/cdrom/cdrom.c (ffffffff81c73c17)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c80995)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81c84255)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81c8df29)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c9f7d5)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81ce5fe6)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d3713f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37657)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81d8ec43)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9dfee)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc3326)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc4aab)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff82148a12)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de3288)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81e09012)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff81e1972a)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81e23ad7)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81e2f0d3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In net/core/neighbour.c (ffffffff81e47f12)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81e701d3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81e77290)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81e8754d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81ea616c)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea88da)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81eb6d36)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81ee9941)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81eed666)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81ef30df)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f013ee)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04c0b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp.c (ffffffff81f0b404)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_read_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81f14ad7)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81f459a3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81f62444)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6aae0)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81f74e2e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f8746d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81f88320)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f89768)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9520c)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9f4f6)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/unix_bpf.c (ffffffff81fb0ae0)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fbd02d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81fd86c3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdda1f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In net/ipv6/udp.c (ffffffff81fea033)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81fee83c)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82005d51)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/calipso.c (ffffffff820189d1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024e1f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/devlink/core.c (ffffffff82042271)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_try_get
```
```
In net/mptcp/token.c (ffffffff8207fbb3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/device.c (ffffffff8208e884)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff8209108e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In lib/dec_and_lock.c (ffffffff8209fb7e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In lib/klist.c (ffffffff820a1d5b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In lib/kobject.c (ffffffff820a286b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
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
In arch/x86/events/core.c (ffffffff8100dac8)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810593b1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/alternative.c (ffffffff8222023e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/process.c (ffffffff81067fbe)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a64b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e3e3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810a033a)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_nmi_unknown
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6457)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a6fc5)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_eilvt
```
```
In arch/x86/kernel/hpet.c (ffffffff810becc2)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:read_hpet
```
```
In arch/x86/mm/kmmio.c (ffffffff810ddbb2)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f06a4)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In kernel/fork.c (ffffffff810fc026)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/panic.c (ffffffff810ff346)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/cpu.c (ffffffff81102b01)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_kick_ap_alive
  - kernel/cpu.c:cpuhp_wait_for_sync_state
```
```
In kernel/sched/core.c (ffffffff81151b61)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_tick_remote
  - kernel/sched/core.c:nohz_csd_func
  - kernel/sched/core.c:sched_core_put
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/sched/fair.c (ffffffff8117367a)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/mutex.c (ffffffff8119c50e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/locking/spinlock.c (ffffffff8119d58e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_nested
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8223d543)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff8223d9a8)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff811a2a26)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/printk/nbcon.c (ffffffff811b39b7)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/printk/nbcon.c:__nbcon_context_update_unsafe
  - kernel/printk/nbcon.c:nbcon_context_can_proceed
```
```
In kernel/irq/chip.c (ffffffff811bde11)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/rcu/tree.c (ffffffff811e184b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_report_cpu_dead
  - kernel/rcu/tree.c:rcutree_report_cpu_starting
  - kernel/rcu/tree.c:rcu_gp_init
```
```
In kernel/module/main.c (ffffffff811f004f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
```
```
In kernel/stacktrace.c (ffffffff811fca3c)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/tick-sched.c (ffffffff8121c920)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_dep_set_signal
  - kernel/time/tick-sched.c:tick_nohz_dep_set_task
  - kernel/time/tick-sched.c:tick_nohz_dep_set_cpu
  - kernel/time/tick-sched.c:tick_nohz_dep_set
```
```
In kernel/futex/core.c (ffffffff8121ec3b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff81221976)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/futex/requeue.c (ffffffff812232c7)
Location: arch/x86/include/asm/atomic.h:113
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
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_kexec
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81270982)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/seccomp.c (ffffffff81279a3b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/seccomp.c:recv_wait_event
  - kernel/seccomp.c:recv_wait_event
```
```
In kernel/trace/trace_clock.c (ffffffff81282398)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff8128e3e6)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_record_on
  - kernel/trace/ring_buffer.c:ring_buffer_record_off
```
```
In kernel/trace/trace.c (ffffffff812a3bc5)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:trace_save_cmdline
  - kernel/trace/trace.c:tracing_stop_tr
  - kernel/trace/trace.c:tracing_snapshot_cond_disable
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
  - kernel/trace/trace.c:tracing_cond_snapshot_data
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ade9e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff812b5b81)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/irq_work.c (ffffffff81302dbe)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff813439f1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_acquire
  - kernel/bpf/helpers.c:bpf_refcount_acquire_impl
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
```
```
In kernel/bpf/ringbuf.c (ffffffff81357ba2)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
```
```
In kernel/bpf/btf.c (ffffffff8136f3b9)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff8137dac2)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/core.c (ffffffff81399de5)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:get_pmu_ctx
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff813a5eb7)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff813a8fb3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff813af294)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
  - kernel/jump_label.c:static_key_fast_inc_not_disabled
```
```
In mm/filemap.c (ffffffff813b9069)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
```
```
In mm/vmscan.c (ffffffff813d63f3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/shrinker.c (ffffffff813e4dcb)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/shrinker.c:shrink_slab
  - mm/shrinker.c:shrink_slab_memcg
```
```
In mm/compaction.c (ffffffff81404da9)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8140e411)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff8141700a)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
```
```
In mm/mmap.c (ffffffff8142cbf6)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff8143be88)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff81452a93)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/swapfile.c (ffffffff8146bde3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81470942)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_current_get
```
```
In mm/hugetlb.c (ffffffff8147ff91)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_hugetlb_folio
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/ksm.c (ffffffff8148d743)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81498064)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8149ee89)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
```
```
In mm/huge_memory.c (ffffffff814a79df)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff814b4261)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In mm/memory-failure.c (ffffffff814c914e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff814d3965)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
```
```
In mm/memfd.c (ffffffff814d723c)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff814d9972)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff814e4799)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/super.c:get_bdev_super
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff814ebdc5)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff814f43e1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
```
In fs/kernel_read_file.c (ffffffff8153b0f2)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/notify/mark.c (ffffffff81549116)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff8155954b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/aio.c (ffffffff8155c570)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/aio.c:__get_reqs_available
```
```
In fs/crypto/keyring.c (ffffffff8156b4ae)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/verity/enable.c (ffffffff815712f5)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/mbcache.c (ffffffff815827c9)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/posix_acl.c (ffffffff815832cc)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff8159c407)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff815a1256)
Location: arch/x86/include/asm/atomic.h:113
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
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff815a3803)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff815ace7f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff815b5167)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff815bbe48)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
  - fs/kernfs/dir.c:kernfs_get_active
```
```
In fs/configfs/item.c (ffffffff815c63d0)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff815c8a0f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815e19a2)
Location: arch/x86/include/asm/atomic.h:113
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
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81605d68)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
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
In fs/ext4/super.c (ffffffff81639974)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/ext4/orphan.c (ffffffff816489c1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In fs/fuse/file.c (ffffffff81695057)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In fs/debugfs/file.c (ffffffff816a842e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff816b169b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff816bc413)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff816c2ec0)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff816c678f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff81734ef9)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff81739234)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81742264)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
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
In security/apparmor/policy.c (ffffffff81744f77)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff8174a298)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81752917)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getlsmblob_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_uring_sqpoll
  - security/apparmor/lsm.c:apparmor_uring_override_creds
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff8175349d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81755c24)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff81759495)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff8175ce8d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8175ea49)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8175fd39)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/af_inet.c (ffffffff817623d9)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff81765569)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/landlock/fs.c (ffffffff8176e06f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In crypto/ahash.c (ffffffff817874e4)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff817887fd)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
```
```
In block/bdev.c (ffffffff817a771d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - block/bdev.c:bdev_thaw
```
```
In block/blk-mq-tag.c (ffffffff817c953a)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In block/blk-rq-qos.c (ffffffff817dfa27)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
```
In block/bsg-lib.c (ffffffff817e2496)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In block/blk-iocost.c (ffffffff817ee0e1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_delay
```
```
In io_uring/io_uring.c (ffffffff8180dc52)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_signal
```
```
In io_uring/timeout.c (ffffffff8181dfee)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
```
```
In io_uring/poll.c (ffffffff81821ae0)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_get_ownership_slowpath
```
```
In io_uring/register.c (ffffffff8182b74e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - io_uring/register.c:io_eventfd_unregister
```
```
In io_uring/io-wq.c (ffffffff8182d08b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wq_activate_free_worker
```
```
In lib/refcount.c (ffffffff8185fde5)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_not_one
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/rcuref.c (ffffffff818600f1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - lib/rcuref.c:rcuref_put_slowpath
```
```
In lib/syscall.c (ffffffff81920737)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/stackdepot.c (ffffffff819289b7)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_save_flags
  - lib/stackdepot.c:stack_depot_save_flags
```
```
In lib/sbitmap.c (ffffffff8192c217)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_wake_up
```
```
In drivers/phy/phy-core.c (ffffffff81931171)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff819734c6)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199d906)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7cc40)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81a8ac90)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81a99f5f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/xen/events/events_base.c (ffffffff81ab9bf2)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/tty/vt/vt.c (ffffffff81b090b0)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0d162)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b12c10)
Location: arch/x86/include/asm/atomic.h:113
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
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:__uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serdev/core.c (ffffffff81b2ef4f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff81b3a59f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b8127b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In drivers/base/core.c (ffffffff81b8ae7d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/power/runtime.c (ffffffff81ba801f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/power/wakeup.c (ffffffff81baf8d6)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15198)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16697)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a6f7)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/hosts.c (ffffffff81c1f7d1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2c651)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c8746d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_mode_get_tile_group
  - drivers/gpu/drm/drm_connector.c:drm_connector_list_iter_next
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c45a)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_lru_scan
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca41b7)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_object.c:__drm_mode_object_find
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb1fea)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
```
```
In drivers/spi/spi.c (ffffffff81ce0fa5)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81ce2cfa)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/cdrom/cdrom.c (ffffffff81d285d7)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d35365)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81d38c55)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81d42a49)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81d5442c)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81d9b096)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded377)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ded8d7)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81e46553)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e55d6e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7bc06)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7d38b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff8222b432)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e99378)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81ec5a82)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff81ed6b7a)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81ee1a37)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81eedd53)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In net/core/neighbour.c (ffffffff81f06bc2)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81f2a434)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81f37250)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81f4955d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81f68c2c)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6b39a)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81f79ad6)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/sched/act_api.c (ffffffff81f80a0e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
```
```
In net/netfilter/nf_queue.c (ffffffff81fad6e0)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81fb16d6)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81fb706f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc573e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8f13)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp.c (ffffffff81fce438)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81fd9001)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff8200baf3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/igmp.c (ffffffff8201ee7b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_start_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff82028a14)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff82031190)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff8203b76b)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cfba)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204eaed)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff8204fa40)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82050ec8)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff820625fc)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff8206c856)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/unix_bpf.c (ffffffff8207e180)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8208a45d)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff820a6043)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff820aaacf)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In net/ipv6/udp.c (ffffffff820b7c0f)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff820bc416)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d4ba3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/calipso.c (ffffffff820e79a1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f40ff)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/devlink/core.c (ffffffff82100be1)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_try_get
```
```
In net/mptcp/token.c (ffffffff821550a3)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/device.c (ffffffff82164d74)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff821675ac)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In lib/dec_and_lock.c (ffffffff82177b4e)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In lib/klist.c (ffffffff82179ddb)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
```
```
In lib/kobject.c (ffffffff8217a8eb)
Location: arch/x86/include/asm/atomic.h:113
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006d29)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81035633)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8103e074)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064e57)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff81075493)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/cred.c (ffffffff810c7c9f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/ucount.c (ffffffff810ca288)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810ca541)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810cd450)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e5f37)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810fc970)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81a7397f)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810ff4e6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81102a69)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff81108d5f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff81114307)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff8112a7f9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff811446f1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/module.c (ffffffff8114a0f6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81180d22)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff8118f027)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81196cf0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811a4577)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811ac462)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/syscall.c (ffffffff811d8cd2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff811eb511)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff811f732e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff8120bf8f)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff81213507)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff81217365)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In mm/filemap.c (ffffffff8121ae6e)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8123136f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81251a3a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffffffff81264ace)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff8126d862)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812837f8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81287c8c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff8129026b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81297f76)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812a4571)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a908a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b1960)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812b7cbc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c2cc7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812cbb71)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff812cd2fe)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In mm/memfd.c (ffffffff812cf968)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812d07f2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812d8789)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff812dd3c4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812e6c32)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/notify/mark.c (ffffffff81325ffa)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff813320ec)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8133ccd7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/crypto/keyring.c (ffffffff81344ca9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/verity/enable.c (ffffffff81348463)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff8135884d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff8136766e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff8136a0d6)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff81371fae)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff81375f81)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff8137808d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff8137ca69)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff81386d9b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8139b32e)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff8142a6e6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8142f642)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8143e34e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8143fd77)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8148db7c)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81497ef2)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149eb7d)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814a200c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff814a3e14)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff814a8574)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814a9cf5)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In block/bsg-lib.c (ffffffff815005b2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff81524360)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff8154b7eb)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff81557364)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8157bffd)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815974a0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/vt/vt.c (ffffffff81663bca)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81668552)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166c1f5)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff8168abb4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff816b6c57)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff816c150c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff816d3c4b)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8171a24f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8171bb7e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171c88d)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff81721c10)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172ace3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/nvme/host/core.c (ffffffff81746fb8)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff8177c4e9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/cdrom/cdrom.c (ffffffff8179a5e9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817a5093)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817ad128)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817bad6d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff818061c4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8186badc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81883bc8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81884a9f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81a69bec)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8189483b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff818b3dec)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818bb493)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff818d397c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818e5b7c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818f82ac)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff8190bd67)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81919407)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/core/dst_cache.c (ffffffff8191a885)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/core/bpf_sk_storage.c (ffffffff8192994e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff819337f6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff819463f1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff8194bf51)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff8195073e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81951823)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff819557b7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81958831)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a299)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81964839)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a557)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c87c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819802e7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81989e79)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff8198bde2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8198df74)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8199f8d6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819a67a5)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819ab8ac)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b0288)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7c8a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b928a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c336c)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb995)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc9f1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff819dab74)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff819dcaa5)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819f2082)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a037eb)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0cb1f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a1607c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a191e6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a1f1ce)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81a225da)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a286d2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81a4d22b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In lib/klist.c (ffffffff81a4efe9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In lib/kobject.c (ffffffff81a4f856)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81024f86)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8102d884)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055127)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff8106528f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/cred.c (ffffffff810b64bf)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/ucount.c (ffffffff810b8a98)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810b8d51)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810bfa15)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_tick_remote
```
```
In kernel/sched/fair.c (ffffffff810d50d7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810ecb80)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81a2fcdf)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810ef6d6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff810f3cd9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810f9c4f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff81105017)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff8111d069)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/tick-sched.c (ffffffff811347f4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_dep_set_cpu
  - kernel/time/tick-sched.c:tick_nohz_dep_set_all
```
```
In kernel/futex.c (ffffffff81136f21)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/module.c (ffffffff8113d3a6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81173e62)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff81182199)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81189fbe)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff81197547)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff8119f31c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/syscall.c (ffffffff811cba92)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff811de2b4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff811ea07e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff811fed5f)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff81206277)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff8120a0c5)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In mm/filemap.c (ffffffff8120e06e)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8122442f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff812448e2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffffffff81256eee)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff8125f892)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812756b7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81279aec)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff81281efb)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81289b36)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff81296041)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8129aa00)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a2d30)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812a8e8c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b3d17)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812bc9f1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff812be16e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In mm/memfd.c (ffffffff812c05e8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812c1472)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812c9409)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff812ce044)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812d7872)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/notify/mark.c (ffffffff81316b9a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff81322cac)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8132d9a7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/crypto/keyring.c (ffffffff81335989)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/verity/enable.c (ffffffff81339143)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff813494fd)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff8135830e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff8135ab66)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff81362a87)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff81366a51)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff81368b5d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff8136d539)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff8137782b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8138bdbe)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff8141b166)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814200c2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8142edbe)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff814307e7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8147e59c)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81488912)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8148f59d)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81492a2c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff81494834)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81498f94)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8149a715)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In block/bsg-lib.c (ffffffff814f0ac2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff81514640)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff8153bacb)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff81547824)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8156adcd)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81586630)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/vt/vt.c (ffffffff81643f4a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816488d2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164b495)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff81694897)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff8169c7bc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff816aeeeb)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816f36b9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff816f4fde)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f5ced)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff816fb040)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81704103)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/nvme/host/core.c (ffffffff81728c33)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff8175c299)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/net/vxlan.c (ffffffff81770d7b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/net/vxlan.c:__vxlan_sock_add
```
```
In drivers/vfio/vfio.c (ffffffff8177a75b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In drivers/cdrom/cdrom.c (ffffffff8178c2b9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff81796ba3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff8179eb28)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817ac78d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff817b5d2f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817cd944)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8183478c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/firmware/efi/efi.c (ffffffff81a260bc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8184cd15)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff8186dd3c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff818753d3)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff8188d80c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff8189f9bc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818b20dc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff818c5b27)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff818d31b7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/core/dst_cache.c (ffffffff818d4635)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/core/bpf_sk_storage.c (ffffffff818e36fe)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff818ed2f6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff818ffee1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff81905a41)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff8190a22e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff8190b313)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff8190f2a7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff81912321)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913d89)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8191e329)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934017)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8193633c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939da7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81943939)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff819458a2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81947a34)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81959396)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81960265)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff8196536c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196c8b8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974a7a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8197607a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff8198015c)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff81988785)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819897e1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81997934)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81999865)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819aee42)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff819c05ab)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c98df)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d2e3c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff819d5fa6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff819dbf8e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff819df39a)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e5492)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81a0a35b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In lib/klist.c (ffffffff81a0c0e9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In lib/kobject.c (ffffffff81a0c956)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81035493)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8103deb4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065307)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff81075443)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/cred.c (ffffffff810c71ef)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/ucount.c (ffffffff810c97b8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810c9a71)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810cc930)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e2307)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810f9b30)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81adfd8f)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff810fc6a6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff81100cd9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff81106c5f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff811121f7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff81128519)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff811425a1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/module.c (ffffffff81147fa6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117eaf2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff8118cdf7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff81194ac0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811a2347)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811aa232)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/syscall.c (ffffffff811d6aa2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff811e92e1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff811f50fe)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff81209d2f)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff812112a7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff81215105)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In mm/filemap.c (ffffffff81218c0e)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8122f10f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff8124f7da)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffffffff8126286e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff8126b602)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff81281608)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff81285a9c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff8128e07b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff81295d86)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812a2381)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a6e9a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812af770)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812b5acc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c0ad7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812c9981)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff812cb10e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In mm/memfd.c (ffffffff812cd778)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812ce602)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812d6599)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff812db1d4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812e4a42)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/notify/mark.c (ffffffff81323aca)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff8132fbbc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8133a7a7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/crypto/keyring.c (ffffffff81342779)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/verity/enable.c (ffffffff81345f33)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff8135631d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff8136513e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81367ba6)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff8136fa7e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff81373a51)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff81375b5d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff8137a539)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff8138486b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81398b8e)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff81426886)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8142b7e2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8143a4ee)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8143bf17)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff81489c1c)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81493f92)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149ac1d)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8149e0ac)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff8149feb4)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff814a4614)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814a5d95)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In block/bsg-lib.c (ffffffff814fc642)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff815203f0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff8154752b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff815530a4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8157bebd)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815979e0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (ffffffff816380d7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81691faa)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81696932)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169a5d5)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff816b8e24)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff816e5127)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff816ef9dc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817021bb)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8175901f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8175a94e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175b65d)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff817609e0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81769ab3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff817aac04)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff817ac891)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff817c552b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In drivers/cdrom/cdrom.c (ffffffff817d7089)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817e1b33)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817e9bc8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817f780d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81845274)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a860)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186ace9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff818b2342)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818bc86c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff818d5068)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818d5f3f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81ad5ffc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818e833b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81904dec)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8190c493)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff8192497c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81936bac)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff819492dc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff8195cd97)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff8196a597)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/core/dst_cache.c (ffffffff8196ba15)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/core/bpf_sk_storage.c (ffffffff8197aade)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81984986)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81997581)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b377)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:instance_lookup_get
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199e4db)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:gc_worker
  - net/netfilter/nf_conntrack_core.c:early_drop
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a17b9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_show
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a2e33)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_find_expectation
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_find_get
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a3369)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_try_module_get
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b0043)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_ct_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_list
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
```
```
In net/ipv4/route.c (ffffffff819b6721)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff819baf0e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819bbff3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff819bff87)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3001)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4a69)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819cf009)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e4d27)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e704c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819eaab7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff819f4649)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff819f65f2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff819f8814)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0a176)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a11045)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a1614c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1ab28)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2270a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a23d0a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2ddec)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff81a36415)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37471)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a455f4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81a47525)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a5cb02)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a6e26b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7759f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a80afc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a83c66)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a89c4e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81a8d05a)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a94282)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81ab961b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In lib/klist.c (ffffffff81abb3d9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In lib/kobject.c (ffffffff81abbc46)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81036473)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/process.c (ffffffff8103f014)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810668e7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
  - arch/x86/kernel/tsc_sync.c:check_tsc_warp
```
```
In arch/x86/kernel/hpet.c (ffffffff810774a3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a8b4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/cred.c (ffffffff810cf72b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/ucount.c (ffffffff810d1cf8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810d1fc5)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810d52c2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810edea7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff81104ca0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81aec5b2)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/qrwlock.c (ffffffff811078d6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/hibernate.c (ffffffff8110c0a9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff8111201f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff8111d817)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/stacktrace.c (ffffffff81134ba9)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8114e619)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/module.c (ffffffff81154bbf)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118c412)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/trace/trace_clock.c (ffffffff8119a937)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ring_buffer.c (ffffffff811a26d0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
  - kernel/trace/ring_buffer.c:rb_get_reader_page
```
```
In kernel/trace/trace.c (ffffffff811b00d7)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
```
In kernel/trace/trace_stack.c (ffffffff811b8072)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:t_start
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/bpf/syscall.c (ffffffff811e4e12)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/bpf/helpers.c (ffffffff811f7698)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/btf.c (ffffffff81203627)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff81218b00)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff812201f7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In kernel/jump_label.c (ffffffff812240d5)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In mm/filemap.c (ffffffff81227d03)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff8123e51f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff8125f14a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/mmap.c (ffffffff8127222e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
```
```
In mm/rmap.c (ffffffff8127af80)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff81291345)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (ffffffff812957d5)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/hugetlb.c (ffffffff8129de1d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812a5b96)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812b26e1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b71cc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812bfab0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff812c5fec)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812d1597)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff812da681)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/hmm.c (ffffffff812dbe6e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In mm/memfd.c (ffffffff812de588)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812df412)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/super.c (ffffffff812e70d7)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/exec.c (ffffffff812ec154)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/namei.c (ffffffff812f59c2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
```
In fs/notify/mark.c (ffffffff8133580a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/userfaultfd.c (ffffffff8134253c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8134d302)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/crypto/keyring.c (ffffffff81355a79)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/verity/enable.c (ffffffff81359213)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/posix_acl.c (ffffffff81369a29)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/task_mmu.c (ffffffff8137881e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff8137b1f6)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff8138340e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff81386fe3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/proc/proc_net.c (ffffffff8138960d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffff8138e029)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/ext4/balloc.c (ffffffff813983e6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813acfb6)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/debugfs/file.c (ffffffff8143d746)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814427f2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff81451620)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff81453097)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff814a18a8)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff814abfb9)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814b3478)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814b67bb)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff814b857f)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff814bcea6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814be634)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In block/bsg-lib.c (ffffffff815156f2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/refcount.c (ffffffff81539d70)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_if_one
```
```
In lib/syscall.c (ffffffff8156137b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff8156cf34)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8159636d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b1e20)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652410)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff816ac59a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816b0ee2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b51d5)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/char/hw_random/core.c (ffffffff816d33f4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/iommu/intel-svm.c (ffffffff816ff7f5)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff8170a21c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff8171c9db)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817745f0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81775f13)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81776917)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/hosts.c (ffffffff8177c040)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81785203)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/spi/spi.c (ffffffff817c4b7e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff817c6821)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff817df7cb)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In drivers/cdrom/cdrom.c (ffffffff817f1329)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff817fbf23)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818040f8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81811a4d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8185f7f4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818847f0)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884c79)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff818ce5f2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818d8b5c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff818f1b88)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818f2a5f)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81ae24bc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81904fa3)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81925eb6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8192d5c3)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81945e18)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81958362)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff8196abec)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff8197efeb)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff8198c9cb)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/core/dst_cache.c (ffffffff8198de93)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/core/bpf_sk_storage.c (ffffffff8199d00e)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff819a7161)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff819ba261)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff819bff53)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/ip_options.c (ffffffff819c481b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff819c5903)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c9960)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/inet_hashtables.c (ffffffff819ccad1)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce4fa)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819d8b99)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ee087)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0d1a)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f4987)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff819fe809)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/arp.c (ffffffff81a00802)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81a02b82)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a14956)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b9a6)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a20b8c)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a25988)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2dafc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2f129)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a395cc)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41d66)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42e01)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81a512c4)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81a532ef)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a68ee4)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a7a81d)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a83de8)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8d3bc)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a90586)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81a968ae)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/calipso.c (ffffffff81a99d27)
Location: arch/x86/include/asm/atomic.h:198
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
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa03d2)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/dec_and_lock.c (ffffffff81ac5a6b)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In lib/klist.c (ffffffff81ac7849)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
```
```
In lib/kobject.c (ffffffff81ac8084)
Location: arch/x86/include/asm/atomic.h:198
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
```
</details>
</li>
</ul>

## Differences
