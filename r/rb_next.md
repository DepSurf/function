# Function: <code>rb_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff813efee0)
Location: lib/rbtree.c:476
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/locking/rtmutex.c:rt_mutex_dequeue
  - kernel/locking/rtmutex.c:rt_mutex_dequeue_pi
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pvm_find_next_prev
  - mm/mempolicy.c:mpol_set_shared_policy
  - mm/mempolicy.c:mpol_free_shared_policy
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_tree_search
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/proc.c:proc_key_users_start
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - block/elevator.c:elv_rb_latter_request
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
  - block/cfq-iosched.c:cfq_close_cooperator
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:split_and_remove_iova
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
ffffffff813efee0-ffffffff813eff1e: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81436830)
Location: lib/rbtree.c:476
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:rt_mutex_dequeue_pi
  - kernel/locking/rtmutex.c:rt_mutex_dequeue
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pvm_find_next_prev
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:__es_tree_search
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - block/elevator.c:elv_rb_latter_request
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_find_next_rq
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
```
**Symbols:**

```
ffffffff81436830-ffffffff81436876: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81453820)
Location: lib/rbtree.c:491
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:rt_mutex_dequeue_pi
  - kernel/locking/rtmutex.c:rt_mutex_dequeue
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pvm_find_next_prev
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:__es_tree_search
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - block/elevator.c:elv_rb_latter_request
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_find_next_rq
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81453820-ffffffff81453866: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff818f3a80)
Location: lib/rbtree.c:493
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:rt_mutex_dequeue_pi
  - kernel/locking/rtmutex.c:rt_mutex_dequeue
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pvm_find_next_prev
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:__es_tree_search
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - block/elevator.c:elv_rb_latter_request
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_find_next_rq
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff818f3a80-ffffffff818f3ac6: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8197a0d0)
Location: lib/rbtree.c:528
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/vmalloc.c:pvm_find_next_prev
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:__es_tree_search
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - block/elevator.c:elv_rb_latter_request
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_find_next_rq
  - lib/interval_tree.c:interval_tree_remove
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - lib/rbtree.c:rb_erase_cached
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff8197a0d0-ffffffff8197a116: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819d6680)
Location: lib/rbtree.c:528
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/vmalloc.c:pvm_find_next_prev
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - block/elevator.c:elv_rb_latter_request
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_next_request
  - block/deadline-iosched.c:deadline_merged_requests
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_find_next_rq
  - lib/interval_tree.c:interval_tree_remove
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - lib/rbtree.c:rb_erase_cached
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff819d6680-ffffffff819d66c3: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a0e8b0)
Location: lib/rbtree.c:528
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/vmalloc.c:pvm_find_next_prev
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - block/elevator.c:elv_rb_latter_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/rbtree.c:rb_erase_cached
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81a0e8b0-ffffffff81a0e8f4: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a7dd00)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81a7dd00-ffffffff81a7dd42: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81ab5030)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81ab5030-ffffffff81ab5072: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815efc70)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/uprobes.c:build_probe_list
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:discard_swap
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/ksm.c:ksm_check_stable_tree
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/apparmor/label.c:labelset_next_stale
  - block/elevator.c:elv_rb_latter_request
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/dma-buf/sw_sync.c:sync_pt_create
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
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
```
**Symbols:**

```
ffffffff815efc70-ffffffff815efcb2: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff816143d0)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/uprobes.c:build_probe_list
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/swapfile.c:discard_swap
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/ksm.c:ksm_check_stable_tree
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/apparmor/label.c:labelset_next_stale
  - block/elevator.c:elv_rb_latter_request
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
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
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff816143d0-ffffffff81614412: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815f7a60)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/ksm.c:ksm_check_stable_tree
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:register_nexthop_notifier
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff815f7a60-ffffffff815f7aa2: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff816651f0)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/ksm.c:ksm_check_stable_tree
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:remove_iova
  - drivers/iommu/iova.c:remove_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_populate_bitmap
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff816651f0-ffffffff81665232: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8177f770)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/ksm.c:ksm_check_stable_tree
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_show
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:remove_iova
  - drivers/iommu/iova.c:remove_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_populate_bitmap
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff8177f770-ffffffff8177f7c9: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8203c4a0)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_groups_next
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/ksm.c:ksm_check_stable_tree
  - fs/xattr.c:simple_xattrs_free
  - fs/xattr.c:simple_xattr_list
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:remove_iova
  - drivers/iommu/iova.c:remove_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff8203c4a0-ffffffff8203c4f9: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff820ba9e0)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - kernel/sched/core.c:sched_core_next
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/bpf/helpers.c:bpf_rbtree_remove
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_groups_next
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/ksm.c:ksm_check_stable_tree
  - fs/xattr.c:simple_xattrs_free
  - fs/xattr.c:simple_xattr_list
  - fs/xattr.c:simple_xattr_list
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_clear_and_put
  - fs/eventpoll.c:ep_clear_and_put
  - fs/eventpoll.c:__ep_remove
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap
  - fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_next_request
  - lib/interval_tree.c:interval_tree_remove
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:remove_iova
  - drivers/iommu/iova.c:remove_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff820ba9e0-ffffffff820baa2e: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff821952f0)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - kernel/sched/core.c:sched_core_next
  - kernel/sched/fair.c:__dequeue_entity
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/bpf/helpers.c:bpf_rbtree_remove
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_groups_next
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/shmem_quota.c:shmem_get_next_id
  - mm/shmem_quota.c:shmem_free_file_info
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/ksm.c:ksm_check_stable_tree
  - fs/namespace.c:__ia32_sys_listmount
  - fs/namespace.c:__x64_sys_listmount
  - fs/namespace.c:m_next
  - fs/xattr.c:simple_xattrs_free
  - fs/xattr.c:simple_xattr_list
  - fs/xattr.c:simple_xattr_list
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_clear_and_put
  - fs/eventpoll.c:ep_clear_and_put
  - fs/eventpoll.c:__ep_remove
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_activate
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap
  - fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_next_request
  - lib/interval_tree.c:interval_tree_remove
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:remove_iova
  - drivers/iommu/iova.c:remove_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/gpu/drm/drm_mm.c:rm_hole
  - drivers/gpu/drm/drm_mm.c:drm_mm_interval_tree_remove
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:list_devices
  - drivers/md/dm-ioctl.c:dm_hash_remove_all
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthops_dump
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff821952f0-ffffffff8219533e: rb_next (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffff800010d8f998)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffff800010d8f998-ffff800010d8f9e8: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c0e8a1c0)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/extents_status.c:__es_tree_search
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
c0e8a1c0-c0e8a22c: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c000000000ed2790)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_show
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_rmv_dev
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
c000000000ed2790-c000000000ed2818: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffe0008b7f42)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffe0008b7f42-ffffffe0008b7f7a: rb_next (STB_GLOBAL)
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
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a53e80)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81a53e80-ffffffff81a53ec2: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a10f60)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81a10f60-ffffffff81a10fa2: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81ac0270)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81ac0270-ffffffff81ac02b2: rb_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_next(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81acc740)
Location: lib/rbtree.c:492
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_copy_nth_element
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:pick_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/power/wakelock.c:pm_show_wakelocks
  - kernel/trace/trace_stat.c:stat_seq_next
  - kernel/trace/trace_stat.c:stat_seq_start
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:visit_groups_merge
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_do_scheduled_discard
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:mpol_set_shared_policy
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:get_epoll_tfile_raw_ptr
  - fs/eventpoll.c:ep_show_fdinfo
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:first_usable_entry
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/fuse/dev.c:fuse_abort_conn
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/apparmor/label.c:__labelset_update
  - block/elevator.c:elv_rb_latter_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_remove_request
  - lib/interval_tree.c:interval_tree_remove
  - drivers/iommu/iova.c:copy_reserved_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/iommu/iova.c:__cached_rbnode_delete_update
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_drop
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - drivers/base/regmap/regcache-rbtree.c:rbtree_show
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_undo_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_iterate_next
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81acc740-ffffffff81acc782: rb_next (STB_GLOBAL)
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
