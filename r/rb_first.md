# Function: <code>rb_first</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff813efdc0)
Location: lib/rbtree.c:450
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - mm/backing-dev.c:bdi_unregister
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - block/blk-throttle.c:throtl_rb_first
  - block/cfq-iosched.c:cfq_rb_first
  - block/cfq-iosched.c:cfq_get_next_cfqg
  - block/cfq-iosched.c:cfq_put_queue
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
```
**Symbols:**

```
ffffffff813efdc0-ffffffff813efde0: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81436690)
Location: lib/rbtree.c:450
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - mm/backing-dev.c:bdi_unregister
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - block/blk-throttle.c:throtl_rb_first
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_get_next_cfqg
  - block/cfq-iosched.c:cfq_find_next_rq
  - block/cfq-iosched.c:cfq_rb_first
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
```
**Symbols:**

```
ffffffff81436690-ffffffff814366ac: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81453680)
Location: lib/rbtree.c:465
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - mm/backing-dev.c:bdi_unregister
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - block/blk-throttle.c:throtl_rb_first
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_get_next_cfqg
  - block/cfq-iosched.c:cfq_find_next_rq
  - block/cfq-iosched.c:cfq_rb_first
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81453680-ffffffff8145369c: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff818f38f0)
Location: lib/rbtree.c:467
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - mm/backing-dev.c:bdi_put
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_free
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - block/blk-throttle.c:throtl_rb_first
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_get_next_cfqg
  - block/cfq-iosched.c:cfq_find_next_rq
  - block/cfq-iosched.c:cfq_rb_first
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
**Symbols:**

```
ffffffff818f38f0-ffffffff818f390c: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819799a0)
Location: lib/rbtree.c:502
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - mm/backing-dev.c:release_bdi
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - block/blk-throttle.c:throtl_rb_first
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_find_next_rq
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
**Symbols:**

```
ffffffff819799a0-ffffffff819799bc: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819d6260)
Location: lib/rbtree.c:502
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - mm/backing-dev.c:release_bdi
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - block/blk-throttle.c:throtl_rb_first
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_find_next_rq
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
**Symbols:**

```
ffffffff819d6260-ffffffff819d6278: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a0e490)
Location: lib/rbtree.c:502
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - mm/backing-dev.c:release_bdi
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
```
**Symbols:**

```
ffffffff81a0e490-ffffffff81a0e4a8: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a7d8b0)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - mm/backing-dev.c:release_bdi
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
```
**Symbols:**

```
ffffffff81a7d8b0-ffffffff81a7d8cd: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81ab4be0)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - mm/backing-dev.c:release_bdi
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
```
**Symbols:**

```
ffffffff81ab4be0-ffffffff81ab4bfd: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815ef820)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - mm/backing-dev.c:release_bdi
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:discard_swap
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_activate
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:labelset_next_stale
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_sanity_check_pfn_list
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_reaccount
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_reaccount
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_collapse_ofo_queue
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_tso_should_defer
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
```
**Symbols:**

```
ffffffff815ef820-ffffffff815ef83d: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81613f80)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:discard_swap
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_activate
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:labelset_next_stale
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_reaccount
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_reaccount
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_populate_bitmap_full
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_collapse_ofo_queue
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_tso_should_defer
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/mptcp/protocol.c:__mptcp_ofo_queue
```
**Symbols:**

```
ffffffff81613f80-ffffffff81613f9d: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815f75e0)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_activate
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_tso_should_defer
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:__mptcp_ofo_queue
```
**Symbols:**

```
ffffffff815f75e0-ffffffff815f75fd: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81664d70)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_activate
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_populate_bitmap
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:__mptcp_ofo_queue
```
**Symbols:**

```
ffffffff81664d70-ffffffff81664d8d: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8177f1f0)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_activate
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_populate_bitmap
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:__mptcp_ofo_queue
```
**Symbols:**

```
ffffffff8177f1f0-ffffffff8177f214: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8203bea0)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - fs/xattr.c:simple_xattrs_free
  - fs/xattr.c:simple_xattr_list
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_activate
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:__mptcp_ofo_queue
```
**Symbols:**

```
ffffffff8203bea0-ffffffff8203bec4: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff820ba410)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - fs/xattr.c:simple_xattrs_free
  - fs/xattr.c:simple_xattr_list
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_activate
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:__mptcp_ofo_queue
```
**Symbols:**

```
ffffffff820ba410-ffffffff820ba434: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff82194d20)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - mm/shmem_quota.c:shmem_free_file_info
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:ksm_check_stable_tree
  - fs/namespace.c:__ia32_sys_listmount
  - fs/namespace.c:__x64_sys_listmount
  - fs/xattr.c:simple_xattrs_free
  - fs/xattr.c:simple_xattr_list
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_activate
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_try_undo_recovery
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:__mptcp_ofo_queue
```
**Symbols:**

```
ffffffff82194d20-ffffffff82194d44: rb_first (STB_GLOBAL)
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
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffff800010d8f500)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - mm/backing-dev.c:bdi_put
  - mm/swapfile.c:__do_sys_swapon
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
```
**Symbols:**

```
ffff800010d8f500-ffff800010d8f520: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c0e89c90)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - mm/backing-dev.c:bdi_put
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
```
**Symbols:**

```
c0e89c90-c0e89cc4: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c000000000ed20f0)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_show
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_rmv_dev
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_rmv_dev
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - mm/backing-dev.c:bdi_put
  - mm/swapfile.c:__do_sys_swapon
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
```
**Symbols:**

```
c000000000ed20f0-c000000000ed212c: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffe0008b7c10)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - mm/backing-dev.c:release_bdi
  - mm/swapfile.c:__do_sys_swapon
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
```
**Symbols:**

```
ffffffe0008b7c10-ffffffe0008b7c2a: rb_first (STB_GLOBAL)
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
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a53a30)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - mm/backing-dev.c:release_bdi
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
```
**Symbols:**

```
ffffffff81a53a30-ffffffff81a53a4d: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a10b10)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - mm/backing-dev.c:release_bdi
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
```
**Symbols:**

```
ffffffff81a10b10-ffffffff81a10b2d: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81abfe20)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - mm/backing-dev.c:release_bdi
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
```
**Symbols:**

```
ffffffff81abfe20-ffffffff81abfe3d: rb_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rb_node *rb_first(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81acc2f0)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - mm/backing-dev.c:release_bdi
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_labelset_destroy
  - security/apparmor/label.c:aa_labelset_destroy
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_prepare
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
```
**Symbols:**

```
ffffffff81acc2f0-ffffffff81acc30d: rb_first (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
