# Function: <code>__mutex_owner</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff810649d4)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In kernel/workqueue.c (ffffffff810a1bf2)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
```
```
In kernel/params.c (ffffffff810a7c56)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/locking/mutex.c (ffffffff810d511f)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/audit_watch.c (ffffffff8113c2b9)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff8114e0f1)
Location: include/linux/mutex.h:66
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81162bf0)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81188931)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/hw_breakpoint.c (ffffffff811a8b15)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In mm/page_alloc.c (ffffffff811b7455)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In mm/mmap.c (ffffffff811f43b2)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/notify/inode_mark.c (ffffffff8128c419)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_add_inode_mark
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
```
```
In fs/notify/mark.c (ffffffff8128cae1)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/notify/vfsmount_mark.c (ffffffff8128d109)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - fs/notify/vfsmount_mark.c:fsnotify_add_vfsmount_mark
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
```
```
In fs/jbd2/journal.c (ffffffff81335440)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
```
```
In fs/ecryptfs/crypto.c (ffffffff81350c75)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In security/apparmor/apparmorfs.c (ffffffff813c19c3)
Location: include/linux/mutex.h:66
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
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__list_remove_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/label.c (ffffffff813e00e3)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
```
In security/apparmor/policy_ns.c (ffffffff813e77ed)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_create_ns
```
```
In drivers/tty/tty_io.c (ffffffff8155ea18)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff815624ce)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff81599d73)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/base/component.c (ffffffff815c5369)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff81618cd2)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81672cc5)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/md/md.c (ffffffff81721abc)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_array_sectors
```
```
In drivers/md/dm.c (ffffffff81735f35)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/devfreq/devfreq.c (ffffffff8177c7c3)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
```
In net/core/net_namespace.c (ffffffff817a4f91)
Location: include/linux/mutex.h:66
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
```
```
In net/core/rtnetlink.c (ffffffff817c56eb)
Location: include/linux/mutex.h:66
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
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In kernel/workqueue.c (ffffffff8109eed2)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:worker_enter_idle
```
```
In kernel/params.c (ffffffff810a4c1e)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/locking/mutex.c (ffffffff810d4195)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/audit.c (ffffffff811348ed)
Location: include/linux/mutex.h:68
Inline: True
```
```
In kernel/audit_watch.c (ffffffff8113d94f)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff81150787)
Location: include/linux/mutex.h:68
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81166090)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b574)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/hw_breakpoint.c (ffffffff811b02c5)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In mm/page_alloc.c (ffffffff811bf295)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In mm/mmap.c (ffffffff811ff332)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/notify/mark.c (ffffffff81299b26)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/jbd2/journal.c (ffffffff8134a1c0)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
```
```
In fs/ecryptfs/crypto.c (ffffffff81365795)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In drivers/tty/tty_io.c (ffffffff8157200a)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff81575e42)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff815add4f)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/base/component.c (ffffffff815da196)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff8162ce23)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff816871c5)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/md/md.c (ffffffff81737fcc)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - drivers/md/md.c:md_set_array_sectors
```
```
In drivers/md/dm.c (ffffffff8174f395)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/devfreq/devfreq.c (ffffffff8179b383)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:update_devfreq
```
```
In net/core/net_namespace.c (ffffffff817c31f0)
Location: include/linux/mutex.h:68
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
```
```
In net/core/rtnetlink.c (ffffffff817e409b)
Location: include/linux/mutex.h:68
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
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In kernel/params.c (ffffffff810ab3a1)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/locking/mutex.c (ffffffff810dc0e5)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/audit.c (ffffffff8114162f)
Location: include/linux/mutex.h:69
Inline: True
```
```
In kernel/audit_watch.c (ffffffff8114a722)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff8115c9bb)
Location: include/linux/mutex.h:69
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81172f40)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81199036)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/hw_breakpoint.c (ffffffff811c3dc5)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In mm/page_alloc.c (ffffffff811d3da5)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In mm/mmap.c (ffffffff81217932)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/notify/mark.c (ffffffff812bced6)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/jbd2/journal.c (ffffffff8136e810)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
```
In fs/ecryptfs/crypto.c (ffffffff8138a455)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In drivers/tty/tty_io.c (ffffffff815d892a)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff815da778)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff81614733)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/base/component.c (ffffffff81640f16)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff816955b0)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff816f0a55)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/net/phy/phy_device.c (ffffffff816fa3ea)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__phy_resume
```
```
In drivers/md/dm.c (ffffffff817c1605)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/devfreq/devfreq.c (ffffffff81811fa3)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In net/core/net_namespace.c (ffffffff8183cd43)
Location: include/linux/mutex.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
```
```
In net/core/rtnetlink.c (ffffffff8185f13a)
Location: include/linux/mutex.h:69
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
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81088275)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
```
In kernel/params.c (ffffffff810b22f1)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/locking/mutex.c (ffffffff810e4725)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/audit_watch.c (ffffffff811591b3)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff8116bd37)
Location: include/linux/mutex.h:73
Inline: True
```
```
In kernel/trace/trace.c (ffffffff81181f20)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae6e6)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/hw_breakpoint.c (ffffffff811e4005)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In mm/page_alloc.c (ffffffff811f50e5)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In mm/mmap.c (ffffffff81238c82)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/notify/mark.c (ffffffff812e5b04)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/jbd2/journal.c (ffffffff8139ce5b)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
```
In fs/ecryptfs/crypto.c (ffffffff813b91e5)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In drivers/tty/tty_io.c (ffffffff81610d8a)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff81614730)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff8164eb2b)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/base/component.c (ffffffff8167c215)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff816d1670)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8172d097)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/net/phy/phy_device.c (ffffffff81736f35)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__phy_resume
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81739865)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/md/dm.c (ffffffff81809ca5)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/devfreq/devfreq.c (ffffffff8185bea3)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:update_devfreq
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In net/core/rtnetlink.c (ffffffff818ab293)
Location: include/linux/mutex.h:73
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
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8108fad5)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
```
In kernel/params.c (ffffffff810baf91)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/locking/mutex.c (ffffffff810efd15)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
```
```
In kernel/audit_watch.c (ffffffff81166153)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff81179776)
Location: include/linux/mutex.h:73
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8118f8e0)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bcd5a)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/hw_breakpoint.c (ffffffff811f44b5)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In mm/page_alloc.c (ffffffff81207455)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In mm/mmap.c (ffffffff8124c642)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In fs/notify/mark.c (ffffffff812fa6fa)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/jbd2/journal.c (ffffffff813b5bcb)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
```
In fs/ecryptfs/crypto.c (ffffffff813d2755)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In drivers/tty/tty_io.c (ffffffff8162de76)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff81631460)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff8166c5fb)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/base/component.c (ffffffff8169bd15)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff816f2d00)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8174f8a7)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/net/phy/phy.c (ffffffff81758105)
Location: include/linux/mutex.h:73
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff8175a0e5)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__phy_resume
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8175d395)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/md/dm.c (ffffffff81835d15)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/devfreq/devfreq.c (ffffffff8187b9cd)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In net/core/rtnetlink.c (ffffffff818ced1d)
Location: include/linux/mutex.h:73
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
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
```
```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093765)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
```
In kernel/params.c (ffffffff810c0eb1)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/params.c:param_array_get
  - kernel/params.c:param_array_set
```
```
In kernel/locking/mutex.c (ffffffff810f7775)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
```
```
In kernel/audit_watch.c (ffffffff81172c78)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/seccomp.c (ffffffff81185f14)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/trace/trace.c (ffffffff8119d310)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc461)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/hw_breakpoint.c (ffffffff8120c185)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
```
In mm/mmap.c (ffffffff8125ea72)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/page_alloc.c (ffffffff8126d645)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - mm/page_alloc.c:pm_restrict_gfp_mask
  - mm/page_alloc.c:pm_restore_gfp_mask
```
```
In fs/notify/mark.c (ffffffff8131b0ea)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_detach_mark
```
```
In fs/jbd2/journal.c (ffffffff813e0b5d)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
```
```
In fs/ecryptfs/crypto.c (ffffffff813fd1f5)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
```
In drivers/tty/tty_io.c (ffffffff81661a46)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_tty
```
```
In drivers/tty/n_tty.c (ffffffff8166543e)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/char/hw_random/core.c (ffffffff816a2191)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:add_early_randomness
```
```
In drivers/base/component.c (ffffffff816d4835)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
```
In drivers/nvdimm/core.c (ffffffff8172c2cf)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff8178b6f9)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_unlock_ddc
```
```
In drivers/net/phy/phy.c (ffffffff81794ae5)
Location: include/linux/mutex.h:73
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81797dfa)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__phy_resume
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8179a925)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/md/dm.c (ffffffff818788a5)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_set_md_type
```
```
In drivers/soundwire/stream.c (ffffffff818c4ef4)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/soundwire/stream.c:do_bank_switch
```
```
In drivers/devfreq/devfreq.c (ffffffff818c5be5)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:find_devfreq_governor
```
```
In net/core/rtnetlink.c (ffffffff8191bad1)
Location: include/linux/mutex.h:73
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_prog_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81103535)
Location: kernel/locking/mutex.c:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110e058)
Location: kernel/locking/mutex.c:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110b31e)
Location: kernel/locking/mutex.c:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110d1ae)
Location: kernel/locking/mutex.c:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_is_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8112c9ee)
Location: kernel/locking/mutex.c:76
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_is_locked
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
In kernel/locking/mutex.c (ffffffff8114d985)
Location: kernel/locking/mutex.c:79
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_is_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8117cc55)
Location: kernel/locking/mutex.c:79
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_is_locked
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
In kernel/locking/mutex.c (ffffffff8118d7f5)
Location: kernel/locking/mutex.c:79
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_is_locked
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
In kernel/locking/mutex.c (ffffffff8119c1a5)
Location: kernel/locking/mutex.c:79
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_check_waiters
  - kernel/locking/mutex.c:mutex_is_locked
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff800010168650)
Location: kernel/locking/mutex.c:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c03b4d2c)
Location: kernel/locking/mutex.c:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0000000001c0470)
Location: kernel/locking/mutex.c:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe00010a468)
Location: kernel/locking/mutex.c:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810fc845)
Location: kernel/locking/mutex.c:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810eca55)
Location: kernel/locking/mutex.c:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810f9a05)
Location: kernel/locking/mutex.c:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81104b81)
Location: kernel/locking/mutex.c:73
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_trylock_recursive
  - kernel/locking/mutex.c:mutex_is_locked
```
</details>
</li>
</ul>

## Differences
