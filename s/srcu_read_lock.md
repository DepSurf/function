# Function: <code>srcu_read_lock</code>

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
In kernel/notifier.c (ffffffff810a17aa)
Location: include/linux/srcu.h:216
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff81179724)
Location: include/linux/srcu.h:216
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff811e39ab)
Location: include/linux/srcu.h:216
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
In fs/notify/fsnotify.c (ffffffff8124f336)
Location: include/linux/srcu.h:216
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/quota/dquot.c (ffffffff81272ead)
Location: include/linux/srcu.h:216
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
In security/tomoyo/common.c (ffffffff81f98d99)
Location: include/linux/srcu.h:216
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_check_profile
```
```
In security/tomoyo/file.c (ffffffff8136f380)
Location: include/linux/srcu.h:216
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path_number_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path2_perm
```
```
In security/tomoyo/mount.c (ffffffff8137172d)
Location: include/linux/srcu.h:216
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81371a36)
Location: include/linux/srcu.h:216
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff81372f23)
Location: include/linux/srcu.h:216
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813735d6)
Location: include/linux/srcu.h:216
Inline: True
```
```
In drivers/md/dm.c (ffffffff816a02d0)
Location: include/linux/srcu.h:216
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_live_table_for_ioctl
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_prep_fn
  - drivers/md/dm.c:dm_request_fn
  - drivers/md/dm.c:dm_mq_queue_rq
```
```
In net/core/netpoll.c (ffffffff81737fd4)
Location: include/linux/srcu.h:216
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
In kernel/notifier.c (ffffffff810a4eca)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff81189fc6)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff81202786)
Location: include/linux/srcu.h:231
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
In fs/notify/fsnotify.c (ffffffff81277a99)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/quota/dquot.c (ffffffff812a067b)
Location: include/linux/srcu.h:231
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
In fs/debugfs/file.c (ffffffff81353a4b)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
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
```
```
In security/tomoyo/common.c (ffffffff813a1c2a)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813a5dec)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813a7b3d)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813a7e58)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813a91f3)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813a99f6)
Location: include/linux/srcu.h:231
Inline: True
```
```
In drivers/md/dm.c (ffffffff817034f0)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_blk_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
```
In net/core/netpoll.c (ffffffff817a42b4)
Location: include/linux/srcu.h:231
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
In kernel/notifier.c (ffffffff810aab2a)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff811993b6)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff812145c6)
Location: include/linux/srcu.h:231
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
In fs/notify/fsnotify.c (ffffffff8128b779)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/quota/dquot.c (ffffffff812b602b)
Location: include/linux/srcu.h:231
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
In fs/debugfs/file.c (ffffffff81369cfb)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
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
```
```
In security/tomoyo/common.c (ffffffff813b87aa)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813bc96c)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813be6cd)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813be9e8)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813bfd63)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813c0566)
Location: include/linux/srcu.h:231
Inline: True
```
```
In block/blk-mq.c (ffffffff81425253)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In drivers/base/core.c (ffffffff815c7869)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_read_lock
```
```
In drivers/md/dm.c (ffffffff817353b0)
Location: include/linux/srcu.h:231
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_blk_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
```
In net/core/netpoll.c (ffffffff817d2d24)
Location: include/linux/srcu.h:231
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
In kernel/notifier.c (ffffffff810a761c)
Location: include/linux/srcu.h:154
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff811a6068)
Location: include/linux/srcu.h:154
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8121fa46)
Location: include/linux/srcu.h:154
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
In fs/notify/fsnotify.c (ffffffff812985a2)
Location: include/linux/srcu.h:154
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff8129947f)
Location: include/linux/srcu.h:154
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff812c303a)
Location: include/linux/srcu.h:154
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
In fs/debugfs/file.c (ffffffff8137e367)
Location: include/linux/srcu.h:154
Inline: True
Inline callers:
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
```
```
In security/tomoyo/common.c (ffffffff813cf056)
Location: include/linux/srcu.h:154
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813d32b3)
Location: include/linux/srcu.h:154
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813d4fcd)
Location: include/linux/srcu.h:154
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813d53b5)
Location: include/linux/srcu.h:154
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813d6626)
Location: include/linux/srcu.h:154
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813d6ed9)
Location: include/linux/srcu.h:154
Inline: True
```
```
In block/blk-mq.c (ffffffff814301fc)
Location: include/linux/srcu.h:154
Inline: True
```
```
In drivers/base/core.c (ffffffff815dc556)
Location: include/linux/srcu.h:154
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_read_lock
```
```
In drivers/base/power/wakeup.c (ffffffff815f185d)
Location: include/linux/srcu.h:154
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff8163cdf9)
Location: include/linux/srcu.h:154
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffffffff8174e5ec)
Location: include/linux/srcu.h:154
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
```
In net/core/netpoll.c (ffffffff817f2084)
Location: include/linux/srcu.h:154
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
In kernel/notifier.c (ffffffff810add9c)
Location: include/linux/srcu.h:155
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff811b9c5e)
Location: include/linux/srcu.h:155
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8123ac56)
Location: include/linux/srcu.h:155
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
In fs/notify/fsnotify.c (ffffffff812bb8bc)
Location: include/linux/srcu.h:155
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff812bc7ef)
Location: include/linux/srcu.h:155
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff812e6bf4)
Location: include/linux/srcu.h:155
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
In security/tomoyo/common.c (ffffffff813f5506)
Location: include/linux/srcu.h:155
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff813f97c3)
Location: include/linux/srcu.h:155
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff813fb4dd)
Location: include/linux/srcu.h:155
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff813fb7b5)
Location: include/linux/srcu.h:155
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff813fcb56)
Location: include/linux/srcu.h:155
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff813fd409)
Location: include/linux/srcu.h:155
Inline: True
```
```
In block/blk-mq.c (ffffffff8145b10a)
Location: include/linux/srcu.h:155
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff81643596)
Location: include/linux/srcu.h:155
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_read_lock
```
```
In drivers/base/power/wakeup.c (ffffffff81658e4d)
Location: include/linux/srcu.h:155
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff816a5ac9)
Location: include/linux/srcu.h:155
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffffffff817c0613)
Location: include/linux/srcu.h:155
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
```
In net/core/netpoll.c (ffffffff8186d644)
Location: include/linux/srcu.h:155
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
In kernel/notifier.c (ffffffff810b4c0e)
Location: include/linux/srcu.h:189
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff811d8fcf)
Location: include/linux/srcu.h:189
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff8125e016)
Location: include/linux/srcu.h:189
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
In fs/notify/fsnotify.c (ffffffff812e4412)
Location: include/linux/srcu.h:189
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff812e5745)
Location: include/linux/srcu.h:189
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff81310d4a)
Location: include/linux/srcu.h:189
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
In security/tomoyo/common.c (ffffffff81426445)
Location: include/linux/srcu.h:189
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8142a7c5)
Location: include/linux/srcu.h:189
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8142c44d)
Location: include/linux/srcu.h:189
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8142c73f)
Location: include/linux/srcu.h:189
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8142da81)
Location: include/linux/srcu.h:189
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8142e2de)
Location: include/linux/srcu.h:189
Inline: True
```
```
In block/blk-mq.c (ffffffff81491427)
Location: include/linux/srcu.h:189
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff8167ee95)
Location: include/linux/srcu.h:189
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff816949a8)
Location: include/linux/srcu.h:189
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff816e1ef3)
Location: include/linux/srcu.h:189
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
```
```
In drivers/md/dm.c (ffffffff81808b92)
Location: include/linux/srcu.h:189
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/core/netpoll.c (ffffffff818be874)
Location: include/linux/srcu.h:189
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
In kernel/notifier.c (ffffffff810bdd5e)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8110fa39)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff811e9452)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff81272896)
Location: include/linux/srcu.h:197
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
In fs/notify/fsnotify.c (ffffffff812f90ab)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff812f9ec5)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff81327d7a)
Location: include/linux/srcu.h:197
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
In security/tomoyo/common.c (ffffffff81442b45)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81447095)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81448d9d)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8144908f)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8144a3d1)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8144ac69)
Location: include/linux/srcu.h:197
Inline: True
```
```
In block/blk-mq.c (ffffffff814aa870)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff8169f2d5)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff816b5038)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff81705313)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
```
```
In drivers/md/dm.c (ffffffff81834c62)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff818e76d4)
Location: include/linux/srcu.h:197
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (ffffffff810c3eaf)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff81118909)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff812027e4)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff8128de4a)
Location: include/linux/srcu.h:150
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
In fs/notify/fsnotify.c (ffffffff813196f6)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff8131a6a5)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff8134f8e2)
Location: include/linux/srcu.h:150
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
In security/tomoyo/common.c (ffffffff81470715)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81474ca8)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff814769d0)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81476e9d)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff814781a3)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff814788fe)
Location: include/linux/srcu.h:150
Inline: True
```
```
In block/blk-mq.c (ffffffff814d8f59)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff816d7915)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff816eecb8)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff8173f1a3)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffffffff818774d2)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff81937a24)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (ffffffff810ccfbf)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff81124cd9)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff8120f5e9)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff8129de2a)
Location: include/linux/srcu.h:150
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
In fs/notify/fsnotify.c (ffffffff8132c526)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff8132d4e5)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff81367bf2)
Location: include/linux/srcu.h:150
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
In security/tomoyo/common.c (ffffffff8148a4d5)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8148ea48)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81490770)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81490c3d)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff81491ec3)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8149261e)
Location: include/linux/srcu.h:150
Inline: True
```
```
In block/blk-mq.c (ffffffff814f2319)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff816fba35)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff81712ed8)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff81763383)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffffffff818a9262)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff8196a8e4)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (ffffffff810d689f)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8113292b)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff81234750)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_init_event
```
```
In mm/mmu_notifier.c (ffffffff812d211a)
Location: include/linux/srcu.h:150
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
In fs/notify/fsnotify.c (ffffffff81366488)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff81367295)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff813b04ce)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff814e1665)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff814e5cd8)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff814e7af0)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff814e7fcd)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_inet_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff814e9293)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff814e9a0e)
Location: include/linux/srcu.h:150
Inline: True
```
```
In block/blk-mq.c (ffffffff81552bab)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff817b5255)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff817ce708)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
```
```
In drivers/dax/super.c (ffffffff81823223)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/md/dm.c (ffffffff81979892)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
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
```
```
In net/core/netpoll.c (ffffffff81a3e434)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065f1f)
Location: include/linux/srcu.h:150
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068056)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/notifier.c (ffffffff810d19af)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/notifier.c:srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8112e11b)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff8123f0a0)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_init_event
```
```
In mm/mmu_notifier.c (ffffffff812ddb3a)
Location: include/linux/srcu.h:150
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
In fs/notify/fsnotify.c (ffffffff81373550)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff813745f5)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff813c1ace)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff814fea95)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff815030d8)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81504e70)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8150534d)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_inet_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff815065bf)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81506d2e)
Location: include/linux/srcu.h:150
Inline: True
```
```
In block/blk-mq.c (ffffffff8156ecac)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff817c9945)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff817e2c78)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
```
```
In drivers/dax/super.c (ffffffff81831f63)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/md/dm.c (ffffffff8197e67e)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff81a40d04)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810662a8)
Location: include/linux/srcu.h:153
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810685c6)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/notifier.c (ffffffff810d358f)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - kernel/notifier.c:srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8112e664)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
```
In kernel/events/core.c (ffffffff81243210)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - kernel/events/core.c:perf_init_event
```
```
In mm/mmu_notifier.c (ffffffff812e4f3a)
Location: include/linux/srcu.h:153
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
In fs/notify/fsnotify.c (ffffffff81379e34)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff8137afa5)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff813c84ae)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff81505735)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81509ca8)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8150b9f0)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8150becd)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff8150d0ff)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8150d86e)
Location: include/linux/srcu.h:153
Inline: True
```
```
In block/blk-mq.c (ffffffff81576888)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff817ad135)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff817c7038)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
```
```
In drivers/dax/super.c (ffffffff81815693)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/md/dm.c (ffffffff819624ce)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff81a259c4)
Location: include/linux/srcu.h:153
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810703c8)
Location: include/linux/srcu.h:159
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072d50)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/notifier.c (ffffffff810e671f)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - kernel/notifier.c:srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8114fb44)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
```
In kernel/events/core.c (ffffffff8127da60)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - kernel/events/core.c:perf_init_event
```
```
In mm/mmu_notifier.c (ffffffff8132cd4a)
Location: include/linux/srcu.h:159
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
In fs/notify/fsnotify.c (ffffffff813c6a2f)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff813c7c05)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff81418b5a)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
```
In security/tomoyo/common.c (ffffffff81562555)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81567194)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81569260)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff815699fd)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff8156ac33)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8156b3be)
Location: include/linux/srcu.h:159
Inline: True
```
```
In block/blk-mq.c (ffffffff815db4fa)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff81836425)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff81851418)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
```
```
In drivers/dax/super.c (ffffffff8189f99d)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:dax_get_by_host
```
```
In drivers/md/dm.c (ffffffff81a09685)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/core/netpoll.c (ffffffff81ada704)
Location: include/linux/srcu.h:159
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e7a3)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080f8a)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/notifier.c (ffffffff811007ea)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - kernel/notifier.c:srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff811771df)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
```
In kernel/events/core.c (ffffffff812d6968)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff8139d4aa)
Location: include/linux/srcu.h:160
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
In fs/notify/fsnotify.c (ffffffff8144dada)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff8144f205)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff81492385)
Location: include/linux/srcu.h:160
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
In fs/proc/vmcore.c (ffffffff814b02ab)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In security/tomoyo/common.c (ffffffff815fd635)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81602d45)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81604fdf)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81605843)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff81606c7f)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816075c6)
Location: include/linux/srcu.h:160
Inline: True
```
```
In block/blk-mq.c (ffffffff816880f6)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_run_hw_queue
```
```
In block/blk-mq-sched.c (ffffffff8168fc32)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In drivers/base/core.c (ffffffff81978425)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff81997038)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
```
```
In drivers/dax/super.c (ffffffff819e9427)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/md/dm.c (ffffffff81b71708)
Location: include/linux/srcu.h:160
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/core/netpoll.c (ffffffff81c5b564)
Location: include/linux/srcu.h:160
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090299)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093a32)
Location: include/linux/srcu.h:179
Inline: True
```
```
In kernel/notifier.c (ffffffff8112573a)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - kernel/notifier.c:srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff8133f735)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff8141c95a)
Location: include/linux/srcu.h:179
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
In fs/notify/fsnotify.c (ffffffff814dc19a)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff814dda45)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff81526055)
Location: include/linux/srcu.h:179
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
In fs/proc/vmcore.c (ffffffff81546b55)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In security/tomoyo/common.c (ffffffff816ae425)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff816b3ec5)
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
In security/tomoyo/mount.c (ffffffff816b630f)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff816b6c33)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff816b81bf)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816b8cf6)
Location: include/linux/srcu.h:179
Inline: True
```
```
In block/blk-mq.c (ffffffff817464d1)
Location: include/linux/srcu.h:179
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
In block/blk-mq-sched.c (ffffffff8174e74f)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In drivers/base/core.c (ffffffff81ae4c95)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff81b07ec8)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
```
```
In drivers/dax/super.c (ffffffff81b65ae5)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/md/dm.c (ffffffff81d0e558)
Location: include/linux/srcu.h:179
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/core/netpoll.c (ffffffff81e11854)
Location: include/linux/srcu.h:179
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810931a9)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810969b2)
Location: include/linux/srcu.h:209
Inline: True
```
```
In kernel/notifier.c (ffffffff81132a32)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - kernel/notifier.c:srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff8136be15)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - kernel/events/core.c:perf_init_event
```
```
In mm/mmu_notifier.c (ffffffff8144ff19)
Location: include/linux/srcu.h:209
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
In fs/notify/fsnotify.c (ffffffff8151298a)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff81514225)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff8155e525)
Location: include/linux/srcu.h:209
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
In fs/proc/vmcore.c (ffffffff8157e634)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In security/tomoyo/common.c (ffffffff816e6e55)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff816ec885)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff816eed1f)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff816ef613)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff816f0b8f)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff816f16c9)
Location: include/linux/srcu.h:209
Inline: True
```
```
In block/blk-mq.c (ffffffff81783841)
Location: include/linux/srcu.h:209
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
In drivers/base/core.c (ffffffff81b33025)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff81b56088)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
```
```
In drivers/dax/super.c (ffffffff81bb9105)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/md/dm.c (ffffffff81d77b58)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/core/netpoll.c (ffffffff81e85164)
Location: include/linux/srcu.h:209
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a619)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109df22)
Location: include/linux/srcu.h:209
Inline: True
```
```
In kernel/notifier.c (ffffffff8113d942)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - kernel/notifier.c:srcu_notifier_call_chain
```
```
In kernel/events/core.c (ffffffff81394fd5)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - kernel/events/core.c:perf_init_event
```
```
In mm/mmu_notifier.c (ffffffff81489c49)
Location: include/linux/srcu.h:209
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
In fs/notify/fsnotify.c (ffffffff81546e3a)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff815486f5)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff81594bf5)
Location: include/linux/srcu.h:209
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
In fs/proc/vmcore.c (ffffffff815b7074)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/tracefs/event_inode.c (ffffffff816ab350)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_iterate
```
```
In security/tomoyo/common.c (ffffffff81723b65)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81729655)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8172baef)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8172c3e3)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
  - security/tomoyo/network.c:tomoyo_check_inet_address
```
```
In security/tomoyo/securityfs_if.c (ffffffff8172d95f)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8172e499)
Location: include/linux/srcu.h:209
Inline: True
```
```
In block/blk-mq.c (ffffffff817c5bb1)
Location: include/linux/srcu.h:209
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
In drivers/base/core.c (ffffffff81b8a935)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff81bae648)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
  - drivers/base/power/wakeup.c:wakeup_sources_read_lock
```
```
In drivers/dax/super.c (ffffffff81c0d765)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8c5a8)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_minor_acquire
```
```
In drivers/md/dm.c (ffffffff81e2ed88)
Location: include/linux/srcu.h:209
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In net/core/netpoll.c (ffffffff81f47154)
Location: include/linux/srcu.h:209
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/kvm_main.c (ffff8000100b6dcc)
Location: include/linux/srcu.h:150
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
In virt/kvm/eventfd.c (ffff8000100c0df4)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_notify_acked_irq
  - virt/kvm/eventfd.c:kvm_irq_has_notifier
  - virt/kvm/eventfd.c:kvm_irqfd_assign
  - virt/kvm/eventfd.c:irqfd_wakeup
  - virt/kvm/eventfd.c:irqfd_resampler_ack
```
```
In virt/kvm/arm/mmu.c (ffff8000100cc278)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
  - virt/kvm/arm/mmu.c:stage2_unmap_vm
  - virt/kvm/arm/mmu.c:stage2_flush_vm
```
```
In virt/kvm/arm/vgic/vgic-v3.c (ffff8000100dfca8)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_save_pending_tables
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_save_pending_tables
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_lpi_sync_pending_status
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100e7de8)
Location: include/linux/srcu.h:150
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
In virt/kvm/irqchip.c (ffff8000100ebcd8)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - virt/kvm/irqchip.c:kvm_set_irq
```
```
In kernel/notifier.c (ffff80001012be28)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffff80001018b234)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffff800010297570)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffff80001033cdac)
Location: include/linux/srcu.h:150
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
In fs/notify/fsnotify.c (ffff8000103e7e08)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffff8000103e96e4)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffff800010430bcc)
Location: include/linux/srcu.h:150
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
In security/tomoyo/common.c (ffff80001057d938)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffff8000105823c0)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffff8000105849c8)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffff800010585058)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffff800010586664)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffff80001058720c)
Location: include/linux/srcu.h:150
Inline: True
```
```
In block/blk-mq.c (ffff8000105f1b5c)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffff8000108e6364)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffff8000109037ec)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffff800010963070)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffff800010aff680)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffff800010c1091c)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (c037c308)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (c03d9050)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (c04c77c8)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (c0543744)
Location: include/linux/srcu.h:150
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
In fs/notify/fsnotify.c (c05bf964)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (c05c0e70)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (c05fb558)
Location: include/linux/srcu.h:150
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
In security/tomoyo/common.c (c072fe98)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (c07342ec)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (c0736440)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (c0736a18)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (c0738038)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (c07389f4)
Location: include/linux/srcu.h:150
Inline: True
```
```
In block/blk-mq.c (c079dc38)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (c09d4990)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (c09edf20)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (c0a3a398)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (c0bdf638)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (c0d28d84)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (c000000000174b9c)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (c0000000001e4c8c)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (c000000000346e40)
Location: include/linux/srcu.h:150
Inline: True
```
```
In mm/mmu_notifier.c (c0000000004184e8)
Location: include/linux/srcu.h:150
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
In fs/notify/fsnotify.c (c0000000004ee834)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (c0000000004f0708)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (c000000000544f20)
Location: include/linux/srcu.h:150
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
In security/tomoyo/common.c (c0000000006e96cc)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (c0000000006f0c90)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (c0000000006f3d98)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (c0000000006f45bc)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (c0000000006f6700)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (c0000000006f740c)
Location: include/linux/srcu.h:150
Inline: True
```
```
In block/blk-mq.c (c000000000788a48)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (c00000000097bff8)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (c0000000009a23fc)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (c000000000a19530)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (c000000000bee498)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (c000000000cfdcc4)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (ffffffe0000e0b06)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffe00011f61e)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffe0001ca03e)
Location: include/linux/srcu.h:150
Inline: True
```
```
In mm/mmu_notifier.c (ffffffe0002329a8)
Location: include/linux/srcu.h:150
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
In fs/notify/fsnotify.c (ffffffe00029cbf2)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffe00029de7a)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffe0002cc2d8)
Location: include/linux/srcu.h:150
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
In security/tomoyo/common.c (ffffffe0003cec94)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffe0003d28e2)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffe0003d48d8)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffe0003d4de2)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffe0003d600c)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffe0003d696a)
Location: include/linux/srcu.h:150
Inline: True
```
```
In block/blk-mq.c (ffffffe000430586)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffe00057adfa)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/dax/super.c (ffffffe0005d074e)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffffffe0006ef616)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffe00078d3b0)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (ffffffff810c733f)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8111d2b9)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff81207c09)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff8129640a)
Location: include/linux/srcu.h:150
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
In fs/notify/fsnotify.c (ffffffff81324b06)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff81325ac5)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff813601d2)
Location: include/linux/srcu.h:150
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
In security/tomoyo/common.c (ffffffff81482ab5)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81487028)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81488d50)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8148921d)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8148a4a3)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8148abfe)
Location: include/linux/srcu.h:150
Inline: True
```
```
In block/blk-mq.c (ffffffff814ea8f9)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff816c1225)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff816d9258)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff81717a73)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/nvme/host/core.c (ffffffff817454b0)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_ioctl
```
```
In drivers/nvme/host/multipath.c (ffffffff8174989b)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
```
```
In drivers/md/dm.c (ffffffff8184f0e2)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff8190a8b4)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (ffffffff810b5b5f)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8110e379)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff811fad39)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff8128801a)
Location: include/linux/srcu.h:150
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
In fs/notify/fsnotify.c (ffffffff813156a6)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff81316665)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff81350e72)
Location: include/linux/srcu.h:150
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
In security/tomoyo/common.c (ffffffff814734d5)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff81477a48)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81479770)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff81479c3d)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8147aec3)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8147b61e)
Location: include/linux/srcu.h:150
Inline: True
```
```
In block/blk-mq.c (ffffffff814dae49)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff8169c4d5)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff816b3898)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff816effa3)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/nvme/host/core.c (ffffffff81727140)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_ioctl
```
```
In drivers/nvme/host/multipath.c (ffffffff8172b48b)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
```
```
In drivers/md/dm.c (ffffffff81816702)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff818c4f04)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (ffffffff810c688f)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff8111b1a9)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff812059d9)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff8129421a)
Location: include/linux/srcu.h:150
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
In fs/notify/fsnotify.c (ffffffff813225d6)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff81323595)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff8135dca2)
Location: include/linux/srcu.h:150
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
In security/tomoyo/common.c (ffffffff8147eb55)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff814830c8)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff81484df0)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff814852bd)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff81486543)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff81486c9e)
Location: include/linux/srcu.h:150
Inline: True
```
```
In block/blk-mq.c (ffffffff814e6989)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/core.c (ffffffff816ef6f5)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff81706b98)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff81756843)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffffffff8189e712)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff8195b8e4)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
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
In kernel/notifier.c (ffffffff810ced4f)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/notifier.c:__srcu_notifier_call_chain
```
```
In kernel/rcu/srcutree.c (ffffffff81127179)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/events/core.c (ffffffff81214846)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmu_notifier.c (ffffffff812a404a)
Location: include/linux/srcu.h:150
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
In fs/notify/fsnotify.c (ffffffff81334436)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/mark.c (ffffffff81335605)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_grab_connector
  - fs/notify/mark.c:fsnotify_finish_user_wait
```
```
In fs/quota/dquot.c (ffffffff81373b25)
Location: include/linux/srcu.h:150
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
In security/tomoyo/common.c (ffffffff81496685)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_check_profile
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_read_control
  - security/tomoyo/common.c:tomoyo_load_builtin_policy
```
```
In security/tomoyo/file.c (ffffffff8149ac58)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/file.c:tomoyo_path2_perm
  - security/tomoyo/file.c:tomoyo_mkdev_perm
  - security/tomoyo/file.c:tomoyo_path_perm
  - security/tomoyo/file.c:tomoyo_check_open_permission
  - security/tomoyo/file.c:tomoyo_path_number_perm
```
```
In security/tomoyo/mount.c (ffffffff8149c930)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/mount.c:tomoyo_mount_permission
```
```
In security/tomoyo/network.c (ffffffff8149cdfd)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_unix_entry
```
```
In security/tomoyo/securityfs_if.c (ffffffff8149e083)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (ffffffff8149e7de)
Location: include/linux/srcu.h:150
Inline: True
```
```
In block/blk-mq.c (ffffffff814fc194)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - block/blk-mq.c:hctx_lock
```
```
In drivers/base/core.c (ffffffff81709f35)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
```
```
In drivers/base/power/wakeup.c (ffffffff817215a8)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_start
  - drivers/base/power/wakeup.c:pm_print_active_wakeup_sources
  - drivers/base/power/wakeup.c:device_wakeup_disarm_wake_irqs
  - drivers/base/power/wakeup.c:device_wakeup_arm_wake_irqs
```
```
In drivers/dax/super.c (ffffffff81771ca3)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
```
In drivers/md/dm.c (ffffffff818bb03e)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
```
```
In net/core/netpoll.c (ffffffff8197daf5)
Location: include/linux/srcu.h:150
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_disable
```
</details>
</li>
</ul>

## Differences
