# Function: <code>srcu_read_unlock</code>

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
In kernel/notifier.c (ffffffff810a17ce)
Location: include/linux/srcu.h:234
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff8117978c)
Location: include/linux/srcu.h:234
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff811e39ed)
Location: include/linux/srcu.h:234
Inline: True
Inline callers:
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
```
```
In fs/notify/fsnotify.c (ffffffff8124f585)
Location: include/linux/srcu.h:234
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/quota/dquot.c (ffffffff81272f4c)
Location: include/linux/srcu.h:234
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff81f98e9b)
Location: include/linux/srcu.h:234
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_check_profile
```
```
In security/tomoyo/file.c (ffffffff8136f460)
Location: include/linux/srcu.h:234
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/tomoyo/mount.c (ffffffff81371751)
Location: include/linux/srcu.h:234
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81371a5c)
Location: include/linux/srcu.h:234
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff81372f7a)
Location: include/linux/srcu.h:234
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813735ed)
Location: include/linux/srcu.h:234
Inline: True
```
```
In drivers/md/dm.c (ffffffff816a02ff)
Location: include/linux/srcu.h:234
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_live_table_for_ioctl
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_pr_register
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_prep_fn
  - drivers/md/dm.c:dm_prep_fn
  - drivers/md/dm.c:dm_request_fn
  - drivers/md/dm.c:dm_mq_queue_rq
  - drivers/md/dm.c:dm_mq_queue_rq
```
```
In net/core/netpoll.c (ffffffff81737ff8)
Location: include/linux/srcu.h:234
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (ffffffff810a4eee)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff8118a031)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff812027aa)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
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
```
```
In fs/notify/fsnotify.c (ffffffff81277d1e)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/quota/dquot.c (ffffffff812a0704)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In fs/debugfs/file.c (ffffffff81353a7a)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
```
In security/tomoyo/common.c (ffffffff813a1caa)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813a5f05)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813a7b61)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813a7e7c)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813a924a)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813a9a0d)
Location: include/linux/srcu.h:249
Inline: True
```
```
In drivers/md/dm.c (ffffffff8170356a)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_blk_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
```
In net/core/netpoll.c (ffffffff817a42d8)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (ffffffff810aab4e)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff81199421)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff812145ea)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
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
```
```
In fs/notify/fsnotify.c (ffffffff8128b9fe)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/quota/dquot.c (ffffffff812b60b4)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In fs/debugfs/file.c (ffffffff81369d2a)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
```
In security/tomoyo/common.c (ffffffff813b882a)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813bca85)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813be6f1)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813bea0c)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813bfdba)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813c057d)
Location: include/linux/srcu.h:249
Inline: True
```
```
In block/blk-mq.c (ffffffff81425272)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In drivers/base/core.c (ffffffff815c7888)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_read_unlock
```
```
In drivers/md/dm.c (ffffffff8173542a)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_blk_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
```
In net/core/netpoll.c (ffffffff817d2d48)
Location: include/linux/srcu.h:249
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (ffffffff810a764e)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff811a60a7)
Location: include/linux/srcu.h:170
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8121fa6a)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff812987a6)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff812994a4)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff812c30d1)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In fs/debugfs/file.c (ffffffff8137e39a)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
```
In security/tomoyo/common.c (ffffffff813cf0de)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813d33e7)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813d4ff1)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813d54ca)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813d666f)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813d6ef0)
Location: include/linux/srcu.h:170
Inline: True
```
```
In block/blk-mq.c (ffffffff8143020f)
Location: include/linux/srcu.h:170
Inline: True
```
```
In drivers/base/core.c (ffffffff815dc578)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_read_unlock
```
```
In drivers/base/power/wakeup.c (ffffffff815f189a)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff8163ce64)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffffffff8174e66a)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_flush
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
```
In net/core/netpoll.c (ffffffff817f20a8)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (ffffffff810addce)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff811b9c9d)
Location: include/linux/srcu.h:171
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8123ac7d)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff812bbcc3)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff812bc814)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff812e6cb2)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff813f558e)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813f98f7)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813fb501)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813fb8ca)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813fcb9f)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813fd420)
Location: include/linux/srcu.h:171
Inline: True
```
```
In block/blk-mq.c (ffffffff8145b11d)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff816435b8)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_read_unlock
```
```
In drivers/base/power/wakeup.c (ffffffff81658e8a)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff816a5b34)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffffffff817c0695)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
```
In net/core/netpoll.c (ffffffff8186d668)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (ffffffff810b4c46)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff811d9060)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff8125e03e)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
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
```
```
In fs/notify/fsnotify.c (ffffffff812e4490)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff812e5774)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff81310dfc)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff814264d6)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8142a7f8)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8142c481)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8142c77b)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8142dad1)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8142e302)
Location: include/linux/srcu.h:205
Inline: True
```
```
In block/blk-mq.c (ffffffff81491445)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff8167eec1)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff816946e5)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff816e1f54)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
```
```
In drivers/md/dm.c (ffffffff81806f9c)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/core/netpoll.c (ffffffff818be898)
Location: include/linux/srcu.h:205
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (ffffffff810bdd96)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8110faef)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff811e94ba)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff812728bd)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff812f92da)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff812f9ef4)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff81327e2c)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff81442bd6)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff814470c8)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81448dd1)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff814490cb)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8144a421)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8144ac8d)
Location: include/linux/srcu.h:223
Inline: True
```
```
In block/blk-mq.c (ffffffff814aa851)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff8169f301)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff816b4d75)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff81705374)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
```
```
In drivers/md/dm.c (ffffffff81832fcc)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff818e76f8)
Location: include/linux/srcu.h:223
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/notifier.c (ffffffff810c3ef1)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff811189c5)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff81202878)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff8128de70)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff81319921)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff8131a6de)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff8134f994)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff814707ae)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81474cdb)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81476a01)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81476ece)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff81478200)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81478915)
Location: include/linux/srcu.h:176
Inline: True
```
```
In block/blk-mq.c (ffffffff814d8f37)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff816d7943)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff816ef67c)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff8173f208)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffffffff81876fb6)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff81937a48)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff8146ecf0-ffffffff8146ed19: srcu_read_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/notifier.c (ffffffff810cd001)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff81124d95)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff8120f67e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff8129de50)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff8132c751)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff8132d51e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff81367ca4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff8148a56e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8148ea7b)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff814907a1)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81490c6e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff81491f20)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81492635)
Location: include/linux/srcu.h:176
Inline: True
```
```
In block/blk-mq.c (ffffffff814f22f7)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff816fba63)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff817136ac)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff817633e8)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffffffff818a8d46)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff8196a908)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff81488af0-ffffffff81488b19: srcu_read_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/notifier.c (ffffffff810d68e1)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff811329e2)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff8123481a)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/events/core.c:perf_init_event
```
```
In mm/mmu_notifier.c (ffffffff812d2140)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:mn_hlist_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:mn_hlist_release
```
```
In fs/notify/fsnotify.c (ffffffff8136657e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff813672ff)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff813b0633)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff814e16fe)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff814e5d0b)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff814e7b21)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff814e7ffe)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_inet_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff814e92f0)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff814e9a25)
Location: include/linux/srcu.h:176
Inline: True
```
```
In block/blk-mq.c (ffffffff81552b79)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff817b5283)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff817ceefc)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_unlock
```
```
In drivers/dax/super.c (ffffffff81823288)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/md/dm.c (ffffffff81978766)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff81a3e458)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff814dd0b0-ffffffff814dd0d9: srcu_read_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065f53)
Location: include/linux/srcu.h:176
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810680b4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/notifier.c (ffffffff810d1a0a)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/notifier.c:srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8112e1c4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff8123f16f)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/events/core.c:perf_init_event
```
```
In mm/mmu_notifier.c (ffffffff812ddb60)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:mn_hlist_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:mn_hlist_release
```
```
In fs/notify/fsnotify.c (ffffffff81373681)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff81374628)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff813c1c33)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff814feb2e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8150310b)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81504ea1)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8150537e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_inet_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff81506615)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81506d45)
Location: include/linux/srcu.h:176
Inline: True
```
```
In block/blk-mq.c (ffffffff8156abe0)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:hctx_unlock
```
```
In drivers/base/core.c (ffffffff817c9973)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff817e34fc)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_unlock
```
```
In drivers/dax/super.c (ffffffff81831fc8)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
Direct callers:
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/md/dm.c (ffffffff8197d5c0)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff81a40d28)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff814fa4d0-ffffffff814fa4f9: srcu_read_unlock.constprop.0 (STB_LOCAL)
ffffffff81831b60-ffffffff81831b89: srcu_read_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810662d5)
Location: include/linux/srcu.h:179
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068624)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/notifier.c (ffffffff810d35ea)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - kernel/notifier.c:srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8112e70e)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
```
In kernel/events/core.c (ffffffff812432ea)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - kernel/events/core.c:perf_init_event
```
```
In mm/mmu_notifier.c (ffffffff812e4f60)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:mn_hlist_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff81379fe2)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff8137afd8)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff813c8613)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff815057ce)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81509cdb)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8150ba21)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8150befe)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff8150d155)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8150d885)
Location: include/linux/srcu.h:179
Inline: True
```
```
In block/blk-mq.c (ffffffff81572b40)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - block/blk-mq.c:hctx_unlock
```
```
In drivers/base/core.c (ffffffff817ad163)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff817c78bc)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_unlock
```
```
In drivers/dax/super.c (ffffffff818156f8)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
Direct callers:
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/md/dm.c (ffffffff819615c0)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff81a259e8)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff815011f0-ffffffff81501219: srcu_read_unlock.constprop.0 (STB_LOCAL)
ffffffff81814d90-ffffffff81814db9: srcu_read_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810703f5)
Location: include/linux/srcu.h:185
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072dc1)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/notifier.c (ffffffff810e677a)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - kernel/notifier.c:srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8114fbec)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
```
In kernel/events/core.c (ffffffff8127db3a)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - kernel/events/core.c:perf_init_event
```
```
In mm/mmu_notifier.c (ffffffff8132cd70)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff813c6c0f)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff813c7c38)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff81418cdb)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff815625ff)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff815671c7)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81569291)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81569a41)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff8156ac9e)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8156b3d5)
Location: include/linux/srcu.h:185
Inline: True
```
```
In block/blk-mq.c (ffffffff815db46b)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff81836453)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff81851a2c)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_unlock
```
```
In drivers/dax/super.c (ffffffff8189fa62)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:dax_get_by_host
Direct callers:
  - drivers/dax/super.c:generic_fsdax_supported
```
```
In drivers/md/dm.c (ffffffff81a08520)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/core/netpoll.c (ffffffff81ada728)
Location: include/linux/srcu.h:185
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff8155c6a0-ffffffff8155c6c9: srcu_read_unlock.constprop.0 (STB_LOCAL)
ffffffff81d0b894-ffffffff81d0b8af: srcu_read_unlock.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e803)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080fe8)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/notifier.c (ffffffff8110082e)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - kernel/notifier.c:srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8117721f)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
```
In kernel/events/core.c (ffffffff812d6a87)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff8139d4d1)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff8144dce8)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff8144f237)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff81492447)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In fs/proc/vmcore.c (ffffffff814b03dc)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In security/tomoyo/common.c (ffffffff815fd6df)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
```
```
In security/tomoyo/file.c (ffffffff81602d78)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81605005)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81605884)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff81606cf8)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816075dd)
Location: include/linux/srcu.h:186
Inline: True
```
```
In block/blk-mq.c (ffffffff8168811a)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_run_hw_queue
```
```
In block/blk-mq-sched.c (ffffffff8168fc61)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In drivers/base/core.c (ffffffff81978451)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff81996f8c)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_unlock
```
```
In drivers/dax/super.c (ffffffff819e945e)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/md/dm.c (ffffffff81b70819)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/core/netpoll.c (ffffffff81c5b588)
Location: include/linux/srcu.h:186
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109032f)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093ab1)
Location: include/linux/srcu.h:224
Inline: True
```
```
In kernel/notifier.c (ffffffff8112577e)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - kernel/notifier.c:srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff8133f854)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff8141c981)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff814dc3a8)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff814dda77)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff81526117)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In fs/proc/vmcore.c (ffffffff81546c86)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In security/tomoyo/common.c (ffffffff816ae4cb)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff816b3ef8)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff816b6335)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff816b6c74)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff816b8238)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816b8d0d)
Location: include/linux/srcu.h:224
Inline: True
```
```
In block/blk-mq.c (ffffffff8174650e)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In block/blk-mq-sched.c (ffffffff8174e78f)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In drivers/base/core.c (ffffffff81ae4cc1)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff81b07dec)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_unlock
```
```
In drivers/dax/super.c (ffffffff81b65b3a)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/md/dm.c (ffffffff81d0d859)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/core/netpoll.c (ffffffff81e11878)
Location: include/linux/srcu.h:224
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093257)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096a3d)
Location: include/linux/srcu.h:282
Inline: True
```
```
In kernel/notifier.c (ffffffff81132a69)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - kernel/notifier.c:srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff8136bf29)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - kernel/events/core.c:perf_init_event
```
```
In mm/mmu_notifier.c (ffffffff8144ff40)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff81512b93)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff81514257)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff8155e5e7)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In fs/proc/vmcore.c (ffffffff8157e765)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In security/tomoyo/common.c (ffffffff816e6efb)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff816ec8b8)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff816eed45)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff816ef654)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff816f0c08)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816f16e0)
Location: include/linux/srcu.h:282
Inline: True
```
```
In block/blk-mq.c (ffffffff81783867)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff81b33051)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff81b55e4c)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_unlock
```
```
In drivers/dax/super.c (ffffffff81bb915a)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/md/dm.c (ffffffff81d767b3)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/core/netpoll.c (ffffffff81e85188)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a6c7)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109dfad)
Location: include/linux/srcu.h:282
Inline: True
```
```
In kernel/notifier.c (ffffffff8113d979)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - kernel/notifier.c:srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff813950e9)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - kernel/events/core.c:perf_init_event
```
```
In mm/mmu_notifier.c (ffffffff81489c70)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_arch_invalidate_secondary_tlbs
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff81547043)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff81548727)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff81594cb7)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In fs/proc/vmcore.c (ffffffff815b71a5)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/tracefs/event_inode.c (ffffffff816ab478)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_iterate
```
```
In security/tomoyo/common.c (ffffffff81723c0b)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81729688)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8172bb15)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8172c424)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff8172d9d8)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8172e4b0)
Location: include/linux/srcu.h:282
Inline: True
```
```
In block/blk-mq.c (ffffffff817c5bd7)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_run_work_fn
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff81b8a961)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff81bae40c)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_unlock
```
```
In drivers/dax/super.c (ffffffff81c0d7ba)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8c5f7)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_minor_acquire
  - drivers/gpu/drm/drm_drv.c:drm_minor_acquire
```
```
In drivers/md/dm.c (ffffffff81e2d9e3)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/core/netpoll.c (ffffffff81f47178)
Location: include/linux/srcu.h:282
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In virt/kvm/kvm_main.c (ffff8000100b6df4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_io_bus_get_dev
  - virt/kvm/kvm_main.c:kvm_vcpu_check_block
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_release
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_test_young
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_clear_young
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_clear_flush_young
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_invalidate_range_start
  - virt/kvm/kvm_main.c:kvm_mmu_notifier_change_pte
```
```
In virt/kvm/eventfd.c (ffff8000100c0e48)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_notify_acked_irq
  - virt/kvm/eventfd.c:kvm_irq_has_notifier
  - virt/kvm/eventfd.c:kvm_irq_has_notifier
  - virt/kvm/eventfd.c:kvm_irqfd_assign
  - virt/kvm/eventfd.c:irqfd_wakeup
  - virt/kvm/eventfd.c:irqfd_resampler_ack
```
```
In virt/kvm/arm/mmu.c (ffff8000100cc330)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
  - virt/kvm/arm/mmu.c:stage2_unmap_vm
  - virt/kvm/arm/mmu.c:stage2_flush_vm
```
```
In virt/kvm/arm/vgic/vgic-v3.c (ffff8000100dfcd0)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_save_pending_tables
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_save_pending_tables
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100e7e10)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_restore_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0
  - virt/kvm/arm/vgic/vgic-its.c:scan_its_table
  - virt/kvm/arm/vgic/vgic-its.c:vgic_enable_lpis
  - virt/kvm/arm/vgic/vgic-its.c:update_lpi_config
```
```
In virt/kvm/irqchip.c (ffff8000100ebcf8)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - virt/kvm/irqchip.c:kvm_set_irq
```
```
In kernel/notifier.c (ffff80001012be50)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffff80001018b2fc)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffff8000102975f4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffff80001033cdd0)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffff8000103e7ed4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffff8000103e972c)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffff800010430cb4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffff80001057d9d4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffff8000105823e8)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffff8000105849f8)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffff8000105850a0)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffff8000105866c4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffff800010587234)
Location: include/linux/srcu.h:176
Inline: True
```
```
In block/blk-mq.c (ffff8000105f1b3c)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffff8000108e6384)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffff800010903bb8)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffff8000109630e8)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffff800010afd138)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffff800010c10938)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffff800010579250-ffff800010579290: srcu_read_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/notifier.c (c037c348)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (c03d9110)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (c04c7858)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (c0543770)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (c05bfbd0)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (c05c0ea4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (c05fb618)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (c072ff50)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (c0734318)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (c0736470)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (c0736a5c)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (c0738098)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (c0738a14)
Location: include/linux/srcu.h:176
Inline: True
```
```
In block/blk-mq.c (c079dc24)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (c09d49b8)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (c09eebdc)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (c0a3a410)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (c0bdecfc)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (c0d28da4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
c072ca5c-c072cabc: srcu_read_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/notifier.c (c000000000174be4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (c0000000001e4d2c)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (c000000000346eec)
Location: include/linux/srcu.h:176
Inline: True
```
```
In mm/mmu_notifier.c (c000000000418520)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (c0000000004eeaf8)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (c0000000004f0748)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (c000000000545010)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (c0000000006e97f4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (c0000000006f0ccc)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (c0000000006f3dd4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (c0000000006f4608)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (c0000000006f6784)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (c0000000006f7438)
Location: include/linux/srcu.h:176
Inline: True
```
```
In block/blk-mq.c (c000000000788a1c)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (c00000000097c030)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (c0000000009a3394)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (c000000000a19700)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (c000000000bedcf4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (c000000000cfdcf0)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
c0000000006e6580-c0000000006e65f4: srcu_read_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/notifier.c (ffffffe0000e0b26)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffe00011f6d2)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffe0001ca0b8)
Location: include/linux/srcu.h:176
Inline: True
```
```
In mm/mmu_notifier.c (ffffffe0002329c8)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffe00029cc98)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffe00029dea8)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffe0002cc3ec)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffe0003ced2c)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffe0003d2922)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffe0003d48fe)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffe0003d4e12)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffe0003d606c)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffe0003d6986)
Location: include/linux/srcu.h:176
Inline: True
```
```
In block/blk-mq.c (ffffffe000430572)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffe00057ae18)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/dax/super.c (ffffffe0005d07e4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffffffe0006ef068)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffe00078d3d4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffe0003cd40a-ffffffe0003cd44c: srcu_read_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/notifier.c (ffffffff810c7381)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8111d375)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff81207c9e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff81296430)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff81324d31)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff81325afe)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff81360284)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff81482b4e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8148705b)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81488d81)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8148924e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8148a500)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8148ac15)
Location: include/linux/srcu.h:176
Inline: True
```
```
In block/blk-mq.c (ffffffff814ea8d7)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff816c1253)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff816d9a1c)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff81717ad8)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/nvme/host/core.c (ffffffff8174555f)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_ioctl
  - drivers/nvme/host/core.c:nvme_ioctl
  - drivers/nvme/host/core.c:nvme_ioctl
```
```
In drivers/nvme/host/multipath.c (ffffffff81749904)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
```
```
In drivers/md/dm.c (ffffffff8184ebc6)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff8190a8d8)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff814810d0-ffffffff814810f9: srcu_read_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/notifier.c (ffffffff810b5ba1)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8110e42b)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff811fadce)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff81288040)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff813158d1)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff8131669e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff81350f24)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff8147356e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81477a7b)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff814797a1)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81479c6e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8147af20)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8147b635)
Location: include/linux/srcu.h:176
Inline: True
```
```
In block/blk-mq.c (ffffffff814dae27)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff8169c503)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff816b406c)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff816f0008)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/nvme/host/core.c (ffffffff817271ef)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_ioctl
  - drivers/nvme/host/core.c:nvme_ioctl
  - drivers/nvme/host/core.c:nvme_ioctl
```
```
In drivers/nvme/host/multipath.c (ffffffff8172b4f4)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
```
```
In drivers/md/dm.c (ffffffff818161e6)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff818c4f28)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff81471af0-ffffffff81471b19: srcu_read_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/notifier.c (ffffffff810c68d1)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8111b265)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff81205a6e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff81294240)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff81322801)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff813235ce)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff8135dd54)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff8147ebee)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff814830fb)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81484e21)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff814852ee)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff814865a0)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81486cb5)
Location: include/linux/srcu.h:176
Inline: True
```
```
In block/blk-mq.c (ffffffff814e6967)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff816ef723)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff8170736c)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff817568a8)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffffffff8189e1f6)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff8195b908)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff8147d170-ffffffff8147d199: srcu_read_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/notifier.c (ffffffff810ced91)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff81127235)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff812148e5)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff812a4070)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_end
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
  - mm/mmu_notifier.c:__mmu_notifier_change_pte
  - mm/mmu_notifier.c:__mmu_notifier_test_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_young
  - mm/mmu_notifier.c:__mmu_notifier_clear_flush_young
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In fs/notify/fsnotify.c (ffffffff81334661)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff8133563f)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/quota/dquot.c (ffffffff81373bc1)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff8149671e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
Direct callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8149ac8b)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8149c961)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8149ce2e)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8149e0e0)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8149e7f5)
Location: include/linux/srcu.h:176
Inline: True
```
```
In block/blk-mq.c (ffffffff814fc1d0)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:hctx_unlock
```
```
In drivers/base/core.c (ffffffff81709f63)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff81721f9c)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_stop
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff81771d06)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffffffff818ba8b6)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff8197db23)
Location: include/linux/srcu.h:176
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
**Symbols:**

```
ffffffff81495280-ffffffff814952a9: srcu_read_unlock.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
