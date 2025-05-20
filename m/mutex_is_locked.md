# Function: <code>mutex_is_locked</code>

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
In arch/x86/kernel/kgdb.c (ffffffff81061a48)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
```
```
In kernel/workqueue.c (ffffffff81097425)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_enter_idle
  - kernel/workqueue.c:idle_worker_timeout
```
```
In kernel/params.c (ffffffff8109f444)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/locking/mutex.c (ffffffff810c9b67)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
```
In kernel/rcu/tree.c (ffffffff810e506a)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited
```
```
In kernel/audit_watch.c (ffffffff8112a39a)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff8113ba8c)
Location: include/linux/mutex.h:128
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f4f0)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/hw_breakpoint.c (ffffffff81186c35)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
```
```
In mm/page_alloc.c (ffffffff81192865)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:pm_restore_gfp_mask
  - mm/page_alloc.c:pm_restrict_gfp_mask
```
```
In mm/mmap.c (ffffffff811c8232)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/namei.c (ffffffff8121809e)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
```
```
In fs/dcache.c (ffffffff81222cad)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/dcache.c:dentry_update_name_case
```
```
In fs/attr.c (ffffffff812295e6)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/notify/notification.c (ffffffff8124f9a5)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_peek_first_event
  - fs/notify/notification.c:fsnotify_flush_notify
```
```
In fs/notify/inode_mark.c (ffffffff8124fe99)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
  - fs/notify/inode_mark.c:fsnotify_add_inode_mark
```
```
In fs/notify/mark.c (ffffffff81250444)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/notify/vfsmount_mark.c (ffffffff81250c69)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
  - fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812531ef)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/ext4/inode.c (ffffffff8129cc42)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/namei.c (ffffffff812a7178)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_add
  - fs/ext4/namei.c:ext4_orphan_del
```
```
In fs/ext4/extents.c (ffffffff812c3602)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
```
```
In fs/jbd2/journal.c (ffffffff812f1b2e)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
```
In fs/ecryptfs/crypto.c (ffffffff81306cc5)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In fs/fuse/dir.c (ffffffff813145ca)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In security/apparmor/apparmorfs.c (ffffffff81374a53)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__next_profile
  - security/apparmor/apparmorfs.c:__next_ns
  - security/apparmor/apparmorfs.c:__first_profile
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_migrate_dents
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
```
```
In security/apparmor/policy.c (ffffffff8137f14b)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - security/apparmor/policy.c:__list_remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy.c:__remove_profile
```
```
In security/apparmor/label.c (ffffffff8138dcd3)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
```
In drivers/tty/tty_io.c (ffffffff814e2fd6)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff814e4ae9)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff8151a709)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/base/component.c (ffffffff81545c75)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/base/component.c:component_unbind_all
  - drivers/base/component.c:component_bind_all
```
```
In drivers/nvdimm/core.c (ffffffff81597173)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
```
```
In drivers/nvdimm/claim.c (ffffffff815a0a63)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:__nd_detach_ndns
```
```
In drivers/md/md.c (ffffffff8168f40c)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_array_sectors
```
```
In drivers/md/dm.c (ffffffff816a3795)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_setup_md_queue
```
```
In drivers/devfreq/devfreq.c (ffffffff816ebdad)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
```
In net/core/net_namespace.c (ffffffff8171050e)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
```
```
In net/core/rtnetlink.c (ffffffff81729aa5)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In arch/x86/kernel/kgdb.c (ffffffff81061924)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In kernel/workqueue.c (ffffffff8109cd52)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
```
```
In kernel/params.c (ffffffff810a2b96)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/locking/mutex.c (ffffffff8189bea8)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
```
In kernel/audit_watch.c (ffffffff81132559)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff81144246)
Location: include/linux/mutex.h:128
Inline: True
```
```
In kernel/trace/trace.c (ffffffff811579c0)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117cd21)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/hw_breakpoint.c (ffffffff81199125)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In mm/page_alloc.c (ffffffff811a7065)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In mm/mmap.c (ffffffff811e4372)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/notify/notification.c (ffffffff81278361)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_peek_first_event
```
```
In fs/notify/inode_mark.c (ffffffff81278739)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_add_inode_mark
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
```
```
In fs/notify/mark.c (ffffffff81278eb1)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/vfsmount_mark.c (ffffffff81279549)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8127b7b0)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/jbd2/journal.c (ffffffff8131f3c0)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
```
```
In fs/ecryptfs/crypto.c (ffffffff8133aee5)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In security/apparmor/apparmorfs.c (ffffffff813aae43)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__next_profile
  - security/apparmor/apparmorfs.c:__first_profile
  - security/apparmor/apparmorfs.c:__next_ns
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_migrate_dents
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
```
```
In security/apparmor/policy.c (ffffffff813b908b)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__list_remove_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/label.c (ffffffff813c8ad3)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
```
In security/apparmor/policy_ns.c (ffffffff813d00ed)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In drivers/tty/tty_io.c (ffffffff815322e8)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff81535dae)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff8156d5f3)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/base/component.c (ffffffff81597819)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff815ec0e2)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/claim.c (ffffffff815f6e54)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:__nd_detach_ndns
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81641be5)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/md/md.c (ffffffff816f021c)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_array_sectors
```
```
In drivers/md/dm.c (ffffffff81704075)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/devfreq/devfreq.c (ffffffff81750a43)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
```
In net/core/net_namespace.c (ffffffff81777e4d)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
```
```
In net/core/rtnetlink.c (ffffffff8179796b)
Location: include/linux/mutex.h:128
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In arch/x86/kernel/kgdb.c (ffffffff810649d4)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In kernel/workqueue.c (ffffffff810a1bf2)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
```
```
In kernel/params.c (ffffffff810a7c56)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/audit_watch.c (ffffffff8113c2b9)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff8114e0f1)
Location: include/linux/mutex.h:139
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81162bf0)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81188931)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/hw_breakpoint.c (ffffffff811a8b15)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In mm/page_alloc.c (ffffffff811b7455)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In mm/mmap.c (ffffffff811f43b2)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/notify/inode_mark.c (ffffffff8128c419)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_add_inode_mark
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
```
```
In fs/notify/mark.c (ffffffff8128cae1)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/vfsmount_mark.c (ffffffff8128d109)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
```
```
In fs/jbd2/journal.c (ffffffff81335440)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
```
```
In fs/ecryptfs/crypto.c (ffffffff81350c75)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In security/apparmor/apparmorfs.c (ffffffff813c19c3)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__next_profile
  - security/apparmor/apparmorfs.c:__first_profile
  - security/apparmor/apparmorfs.c:__next_ns
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_migrate_dents
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
```
```
In security/apparmor/policy.c (ffffffff813d044b)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__list_remove_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/label.c (ffffffff813e00e3)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
```
In security/apparmor/policy_ns.c (ffffffff813e77ed)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In drivers/tty/tty_io.c (ffffffff8155ea18)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff815624ce)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff81599d73)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/base/component.c (ffffffff815c5369)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff81618cd2)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81672cc5)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/md/md.c (ffffffff81721abc)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_array_sectors
```
```
In drivers/md/dm.c (ffffffff81735f35)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/devfreq/devfreq.c (ffffffff8177c7c3)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
```
In net/core/net_namespace.c (ffffffff817a4f91)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
```
```
In net/core/rtnetlink.c (ffffffff817c56eb)
Location: include/linux/mutex.h:139
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In arch/x86/kernel/kgdb.c (ffffffff810638ef)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In kernel/workqueue.c (ffffffff8109eed2)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
```
```
In kernel/params.c (ffffffff810a4c1e)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/audit_watch.c (ffffffff8113d94f)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff81150787)
Location: include/linux/mutex.h:142
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81166090)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b574)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/hw_breakpoint.c (ffffffff811b02c5)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In mm/page_alloc.c (ffffffff811bf295)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In mm/mmap.c (ffffffff811ff332)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/notify/mark.c (ffffffff81299b26)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/jbd2/journal.c (ffffffff8134a1c0)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
```
```
In fs/ecryptfs/crypto.c (ffffffff81365795)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In drivers/tty/tty_io.c (ffffffff8157200a)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff81575e42)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff815add4f)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/base/component.c (ffffffff815da196)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff8162ce23)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff816871c5)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/md/md.c (ffffffff81737fcc)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_array_sectors
```
```
In drivers/md/dm.c (ffffffff8174f395)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/devfreq/devfreq.c (ffffffff8179b383)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
```
In net/core/net_namespace.c (ffffffff817c31f0)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
```
```
In net/core/rtnetlink.c (ffffffff817e409b)
Location: include/linux/mutex.h:142
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In arch/x86/kernel/kgdb.c (ffffffff81067a5f)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In kernel/params.c (ffffffff810ab3a1)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/audit_watch.c (ffffffff8114a722)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff8115c9bb)
Location: include/linux/mutex.h:143
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81172f40)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81199036)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/hw_breakpoint.c (ffffffff811c3dc5)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In mm/page_alloc.c (ffffffff811d3da5)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In mm/mmap.c (ffffffff81217932)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/notify/mark.c (ffffffff812bced6)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/jbd2/journal.c (ffffffff8136e810)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
```
In fs/ecryptfs/crypto.c (ffffffff8138a455)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In drivers/tty/tty_io.c (ffffffff815d892a)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff815da778)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff81614733)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/base/component.c (ffffffff81640f16)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff816955b0)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff816f0a55)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/net/phy/phy_device.c (ffffffff816fa3ea)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__phy_resume
```
```
In drivers/md/dm.c (ffffffff817c1605)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/devfreq/devfreq.c (ffffffff81811fa3)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In net/core/net_namespace.c (ffffffff8183cd43)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
```
```
In net/core/rtnetlink.c (ffffffff8185f13a)
Location: include/linux/mutex.h:143
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
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
In arch/x86/kernel/kgdb.c (ffffffff8106a5ff)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81088275)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
```
In kernel/params.c (ffffffff810b22f1)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/audit_watch.c (ffffffff811591b3)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff8116bd37)
Location: include/linux/mutex.h:147
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81181f20)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae6e6)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/hw_breakpoint.c (ffffffff811e4005)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In mm/page_alloc.c (ffffffff811f50e5)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In mm/mmap.c (ffffffff81238c82)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/notify/mark.c (ffffffff812e5b04)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/jbd2/journal.c (ffffffff8139ce5b)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
```
In fs/ecryptfs/crypto.c (ffffffff813b91e5)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In drivers/tty/tty_io.c (ffffffff81610d8a)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff81614730)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff8164eb2b)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/base/component.c (ffffffff8167c215)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff816d1670)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8172d097)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/net/phy/phy_device.c (ffffffff81736f35)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__phy_resume
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81739865)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/md/dm.c (ffffffff81809ca5)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/devfreq/devfreq.c (ffffffff8185bea3)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In net/core/rtnetlink.c (ffffffff818ab293)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
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
In arch/x86/kernel/kgdb.c (ffffffff8107038f)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8108fad5)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
```
In kernel/params.c (ffffffff810baf91)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/audit_watch.c (ffffffff81166153)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff81179776)
Location: include/linux/mutex.h:147
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8118f8e0)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bcd5a)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/hw_breakpoint.c (ffffffff811f44b5)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In mm/page_alloc.c (ffffffff81207455)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In mm/mmap.c (ffffffff8124c642)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/notify/mark.c (ffffffff812fa6fa)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/jbd2/journal.c (ffffffff813b5bcb)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
```
In fs/ecryptfs/crypto.c (ffffffff813d2755)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In drivers/tty/tty_io.c (ffffffff8162de76)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff81631460)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff8166c5fb)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/base/component.c (ffffffff8169bd15)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff816f2d00)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8174f8a7)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/net/phy/phy.c (ffffffff81758105)
Location: include/linux/mutex.h:147
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff8175a0e5)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__phy_resume
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8175d395)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/md/dm.c (ffffffff81835d15)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/devfreq/devfreq.c (ffffffff8187b9cd)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In net/core/rtnetlink.c (ffffffff818ced1d)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
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
In arch/x86/kernel/kgdb.c (ffffffff81074416)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093765)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
```
In kernel/params.c (ffffffff810c0eb1)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/audit_watch.c (ffffffff81172c78)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff81185f14)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/trace/trace.c (ffffffff8119d310)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc461)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/hw_breakpoint.c (ffffffff8120c185)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In mm/mmap.c (ffffffff8125ea72)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/page_alloc.c (ffffffff8126d645)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In fs/notify/mark.c (ffffffff8131b0ea)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/jbd2/journal.c (ffffffff813e0b5d)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
```
In fs/ecryptfs/crypto.c (ffffffff813fd1f5)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In drivers/tty/tty_io.c (ffffffff81661a46)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff8166543e)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff816a2191)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/base/component.c (ffffffff816d4835)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff8172c2cf)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8178b6f9)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/net/phy/phy.c (ffffffff81794ae5)
Location: include/linux/mutex.h:147
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81797dfa)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__phy_resume
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8179a925)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/md/dm.c (ffffffff818788a5)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/soundwire/stream.c (ffffffff818c4ef4)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/soundwire/stream.c:do_bank_switch
```
```
In drivers/devfreq/devfreq.c (ffffffff818c5be5)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In net/core/rtnetlink.c (ffffffff8191bad1)
Location: include/linux/mutex.h:147
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff811034a0)
Location: kernel/locking/mutex.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy_device.c:__phy_resume
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/md/dm.c:dm_set_md_type
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:find_devfreq_governor
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
**Symbols:**

```
ffffffff811034a0-ffffffff811034b7: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110e030)
Location: kernel/locking/mutex.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/params.c:param_array_get
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:__jbd2_update_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_tfm_exists
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:enable_best_rng
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy_device.c:__phy_resume
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/md/dm.c:dm_set_md_type
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
**Symbols:**

```
ffffffff8110e030-ffffffff8110e047: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110b2f0)
Location: kernel/locking/mutex.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/params.c:param_array_get
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:__jbd2_update_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_tfm_exists
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:enable_best_rng
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/iommu/intel/svm.c:pasid_to_svm_sdev
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy_device.c:__phy_resume
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/md/dm.c:dm_set_md_type
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
**Symbols:**

```
ffffffff8110b2f0-ffffffff8110b307: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110d180)
Location: kernel/locking/mutex.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:__jbd2_update_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_tfm_exists
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - security/selinux/ima.c:selinux_ima_measure_state
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:enable_best_rng
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/iommu/intel/svm.c:pasid_to_svm_sdev
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
  - drivers/md/dm.c:dm_set_md_type
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
  - net/core/rtnetlink.c:rtnl_af_lookup
```
**Symbols:**

```
ffffffff8110d180-ffffffff8110d197: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8112c8f0)
Location: kernel/locking/mutex.c:86
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_tfm_exists
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:enable_best_rng
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:drop_current_rng
  - drivers/char/hw_random/core.c:set_current_rng
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/iommu/intel/svm.c:pasid_to_svm_sdev
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/md/dm.c:dm_set_md_type
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
  - net/core/rtnetlink.c:rtnl_af_lookup
```
**Symbols:**

```
ffffffff8112c8f0-ffffffff8112c907: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8114d4d0)
Location: kernel/locking/mutex.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_tfm_exists
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_manage_rngd
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:enable_best_rng
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:drop_current_rng
  - drivers/char/hw_random/core.c:set_current_rng
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/iommu/intel/svm.c:pasid_to_svm_sdev
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/md/dm.c:dm_set_md_type
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
  - net/core/rtnetlink.c:rtnl_af_lookup
```
**Symbols:**

```
ffffffff8114d4d0-ffffffff8114d4eb: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8117c5c0)
Location: kernel/locking/mutex.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_tfm_exists
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:enable_best_rng
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:drop_current_rng
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/md/dm.c:dm_set_md_type
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
  - net/core/rtnetlink.c:rtnl_af_lookup
```
**Symbols:**

```
ffffffff8117c5c0-ffffffff8117c5db: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8118d2a0)
Location: kernel/locking/mutex.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/power/main.c:pm_restrict_gfp_mask
  - kernel/power/main.c:pm_restore_gfp_mask
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_tfm_exists
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:enable_best_rng
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:drop_current_rng
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_error
  - drivers/md/dm.c:dm_set_md_type
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
  - net/core/rtnetlink.c:rtnl_af_lookup
```
**Symbols:**

```
ffffffff8118d2a0-ffffffff8118d2bb: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8119bc50)
Location: kernel/locking/mutex.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/power/main.c:pm_restrict_gfp_mask
  - kernel/power/main.c:pm_restore_gfp_mask
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/bpf/arraymap.c:prog_array_map_poke_run
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_tfm_exists
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:enable_best_rng
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:drop_current_rng
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:alloc_nvdimm_map
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_get_property
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_get_property
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_get_property
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_info
  - drivers/gpu/drm/drm_gem.c:drm_gem_handle_create_tail
  - drivers/gpu/drm/drm_modes.c:drm_connector_list_update
  - drivers/gpu/drm/drm_modes.c:drm_mode_probed_add
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_planes
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_modeset
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_check_modeset
  - drivers/gpu/drm/drm_crtc_helper.c:drm_helper_crtc_in_use
  - drivers/gpu/drm/drm_crtc_helper.c:drm_helper_encoder_in_use
  - drivers/gpu/drm/drm_crtc_helper.c:drm_helper_encoder_in_use
  - drivers/gpu/drm/drm_plane_helper.c:get_connectors_for_crtc
  - drivers/gpu/drm/drm_probe_helper.c:check_connector_changed
  - drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:phy_error
  - drivers/md/dm.c:dm_set_md_type
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
  - net/core/rtnetlink.c:rtnl_af_lookup
```
**Symbols:**

```
ffffffff8119bc50-ffffffff8119bc6b: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff8000101685f8)
Location: kernel/locking/mutex.c:83
Inline: False
Direct callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy_device.c:__phy_resume
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/md/dm.c:dm_set_md_type
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:find_devfreq_governor
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
**Symbols:**

```
ffff8000101685f8-ffff800010168628: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c03b4cf0)
Location: kernel/locking/mutex.c:83
Inline: False
Direct callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy_device.c:__phy_resume
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/md/dm.c:dm_set_md_type
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:find_devfreq_governor
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
**Symbols:**

```
c03b4cf0-c03b4d18: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0000000001c0380)
Location: kernel/locking/mutex.c:83
Inline: False
Direct callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_tfm_exists
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:enable_best_rng
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:drop_current_rng
  - drivers/char/hw_random/core.c:set_current_rng
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy_device.c:__phy_resume
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/md/dm.c:dm_set_md_type
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:find_devfreq_governor
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
**Symbols:**

```
c0000000001c0380-c0000000001c039c: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe00010a422)
Location: kernel/locking/mutex.c:83
Inline: False
Direct callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - mm/mmap.c:mm_drop_all_locks
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy_device.c:__phy_resume
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/md/dm.c:dm_set_md_type
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:find_devfreq_governor
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
**Symbols:**

```
ffffffe00010a422-ffffffe00010a44a: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810fc7b0)
Location: kernel/locking/mutex.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy_device.c:__phy_resume
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/md/dm.c:dm_set_md_type
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:find_devfreq_governor
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
**Symbols:**

```
ffffffff810fc7b0-ffffffff810fc7c7: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810ec9c0)
Location: kernel/locking/mutex.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/nvdimm/btt.c:btt_write_pg
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy_device.c:__phy_resume
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/md/dm.c:dm_set_md_type
  - drivers/hv/connection.c:relid2channel
  - drivers/hv/channel_mgmt.c:hv_process_channel_removal
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:find_devfreq_governor
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
**Symbols:**

```
ffffffff810ec9c0-ffffffff810ec9d7: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810f9970)
Location: kernel/locking/mutex.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy_device.c:__phy_resume
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/md/dm.c:dm_set_md_type
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:find_devfreq_governor
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
**Symbols:**

```
ffffffff810f9970-ffffffff810f9987: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool mutex_is_locked(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81104ad0)
Location: kernel/locking/mutex.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
  - kernel/audit_watch.c:audit_add_watch
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - mm/mmap.c:mm_drop_all_locks
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
  - drivers/nvdimm/core.c:is_nvdimm_bus_locked
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy_device.c:__phy_resume
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/md/dm.c:dm_set_md_type
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:find_devfreq_governor
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
**Symbols:**

```
ffffffff81104ad0-ffffffff81104ae7: mutex_is_locked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
