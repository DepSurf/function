# Function: <code>__srcu_read_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __srcu_read_lock(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810e3970)
Location: kernel/rcu/srcu.c:296
Inline: False
Direct callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_page
  - fs/notify/fsnotify.c:fsnotify
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - drivers/md/dm.c:dm_get_live_table_for_ioctl
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_prep_fn
  - drivers/md/dm.c:dm_request_fn
  - drivers/md/dm.c:dm_mq_queue_rq
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff810e3970-ffffffff810e399d: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __srcu_read_lock(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810e9c80)
Location: kernel/rcu/srcu.c:296
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_page
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_blk_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff810e9c80-ffffffff810e9cb0: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __srcu_read_lock(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810f0b50)
Location: kernel/rcu/srcu.c:296
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_page
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_make_request
  - drivers/base/core.c:device_links_read_lock
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_blk_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff810f0b50-ffffffff810f0b80: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __srcu_read_lock(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f0b10)
Location: kernel/rcu/srcutree.c:374
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/notifier.c:__srcu_notifier_call_chain
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - drivers/base/core.c:device_links_read_lock
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff810f0b10-ffffffff810f0b36: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __srcu_read_lock(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fa7d0)
Location: kernel/rcu/srcutree.c:375
Inline: False
Direct callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/base/core.c:device_links_read_lock
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff810fa7d0-ffffffff810fa7f9: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __srcu_read_lock(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81102d50)
Location: kernel/rcu/srcutree.c:406
Inline: False
Direct callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:mm_has_blockable_invalidate_notifiers
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/dax/super.c:dax_get_by_host
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff81102d50-ffffffff81102d79: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110fa39)
Location: kernel/rcu/srcutree.c:412
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:pm_runtime_work
  - drivers/base/power/runtime.c:pm_runtime_work
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/dax/super.c:dax_get_by_host
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff8110e720-ffffffff8110e749: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81118909)
Location: kernel/rcu/srcutree.c:403
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff81117dc0-ffffffff81117df0: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81124cd9)
Location: kernel/rcu/srcutree.c:403
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff81124180-ffffffff811241b0: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8113292b)
Location: kernel/rcu/srcutree.c:416
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/events/core.c:perf_init_event
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:mn_hlist_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:mn_hlist_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_inet_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff81131970-ffffffff811319a0: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e11b)
Location: kernel/rcu/srcutree.c:405
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
  - kernel/notifier.c:srcu_notifier_call_chain
  - kernel/events/core.c:perf_init_event
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:mn_hlist_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:mn_hlist_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_inet_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff8112d150-ffffffff8112d180: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e664)
Location: kernel/rcu/srcutree.c:408
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
  - kernel/notifier.c:srcu_notifier_call_chain
  - kernel/events/core.c:perf_init_event
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:mn_hlist_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff8112d6f0-ffffffff8112d720: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114fb44)
Location: kernel/rcu/srcutree.c:400
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
  - kernel/notifier.c:srcu_notifier_call_chain
  - kernel/events/core.c:perf_init_event
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:dax_get_by_host
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff8114e8c0-ffffffff8114e8f0: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811771df)
Location: kernel/rcu/srcutree.c:634
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
  - kernel/notifier.c:srcu_notifier_call_chain
  - kernel/printk/printk.c:printk_sprint
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/proc/vmcore.c:mmap_vmcore
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff81175610-ffffffff81175641: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ae8cf)
Location: kernel/rcu/srcutree.c:662
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
  - kernel/notifier.c:srcu_notifier_call_chain
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_flush_all
  - kernel/printk/printk.c:printk_sprint
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/proc/vmcore.c:mmap_vmcore
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff811ac740-ffffffff811ac771: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811c08b8)
Location: kernel/rcu/srcutree.c:710
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
  - kernel/notifier.c:srcu_notifier_call_chain
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_flush_all
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/events/core.c:perf_init_event
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/proc/vmcore.c:mmap_vmcore
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queue
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff811be5b0-ffffffff811be5dd: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811d0d98)
Location: kernel/rcu/srcutree.c:712
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
  - kernel/notifier.c:srcu_notifier_call_chain
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_unblank
  - kernel/printk/printk.c:console_flush_all
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/events/core.c:perf_init_event
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_arch_invalidate_secondary_tlbs
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/proc/vmcore.c:mmap_vmcore
  - fs/tracefs/event_inode.c:eventfs_iterate
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queue
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
  - drivers/gpu/drm/drm_drv.c:drm_minor_acquire
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff811cead0-ffffffff811ceafd: __srcu_read_lock (STB_GLOBAL)
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
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff80001018a150)
Location: kernel/rcu/srcutree.c:403
Inline: False
Direct callers:
  - arch/arm64/kernel/process.c:arch_cpu_idle
  - arch/arm64/kernel/process.c:arch_cpu_idle
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/smp.c:handle_IPI
  - virt/kvm/kvm_main.c:kvm_io_bus_get_dev
  - virt/kvm/kvm_main.c:kvm_vcpu_check_block
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_release
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_test_young
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_clear_young
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_clear_flush_young
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_invalidate_range_start
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_change_pte
  - virt/kvm/eventfd.c:kvm_notify_acked_irq
  - virt/kvm/eventfd.c:kvm_irq_has_notifier
  - virt/kvm/eventfd.c:kvm_irqfd_assign
  - virt/kvm/eventfd.c:irqfd_wakeup
  - virt/kvm/eventfd.c:irqfd_resampler_ack
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
  - virt/kvm/arm/mmu.c:stage2_unmap_vm
  - virt/kvm/arm/mmu.c:stage2_flush_vm
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_save_pending_tables
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_save_pending_tables
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_restore_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:scan_its_table
  - virt/kvm/arm/vgic/vgic-its.c:vgic_enable_lpis
  - virt/kvm/arm/vgic/vgic-its.c:update_lpi_config
  - virt/kvm/irqchip.c:kvm_set_irq
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffff80001018a150-ffff80001018a1a8: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d9050)
Location: kernel/rcu/srcutree.c:403
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - arch/arm/kernel/smp.c:smp_send_stop
  - arch/arm/kernel/smp.c:smp_send_reschedule
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:tick_broadcast
  - arch/arm/kernel/smp.c:arch_irq_work_raise
  - arch/arm/kernel/smp.c:arch_send_call_function_single_ipi
  - arch/arm/kernel/smp.c:arch_send_wakeup_ipi_mask
  - arch/arm/kernel/smp.c:arch_send_call_function_ipi_mask
  - arch/arm/mach-omap2/powerdomain.c:pwrdm_set_next_pwrst
  - arch/arm/mach-omap2/powerdomain.c:_pwrdm_state_switch
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
c03d7eec-c03d7f38: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e3b00)
Location: kernel/rcu/srcutree.c:403
Inline: False
Direct callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/rcu/srcutree.c:__call_srcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
c0000000001e3b00-c0000000001e3b78: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011f61e)
Location: kernel/rcu/srcutree.c:403
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffe00011e83a-ffffffe00011e894: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111d2b9)
Location: kernel/rcu/srcutree.c:403
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_ioctl
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff8111c760-ffffffff8111c790: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e379)
Location: kernel/rcu/srcutree.c:403
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_ioctl
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff8110d820-ffffffff8110d850: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111b1a9)
Location: kernel/rcu/srcutree.c:403
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff8111a650-ffffffff8111a680: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __srcu_read_lock(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81127179)
Location: kernel/rcu/srcutree.c:403
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/notifier.c:__srcu_notifier_call_chain
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/events/core.c:perf_event_alloc
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/mount.c:tomoyo_mount_permission
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
  - block/blk-mq.c:hctx_lock
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff81125de0-ffffffff81125e10: __srcu_read_lock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_struct *ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct *sp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
