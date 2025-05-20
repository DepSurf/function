# Function: <code>rb_erase</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff813ef860)
Location: lib/rbtree.c:424
Inline: False
Direct callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/locking/rtmutex.c:rt_mutex_dequeue
  - kernel/locking/rtmutex.c:rt_mutex_dequeue_pi
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:wb_congested_put
  - mm/backing-dev.c:bdi_unregister
  - mm/vmalloc.c:__free_vmap_area
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedreceive
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/blk-throttle.c:__throtl_dequeue_tg
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - block/cfq-iosched.c:cfq_prio_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - lib/timerqueue.c:timerqueue_del
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/iommu/iova.c:__free_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - net/core/gen_estimator.c:gen_kill_estimator
```
**Symbols:**

```
ffffffff813ef860-ffffffff813efbae: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81436130)
Location: lib/rbtree.c:424
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:rt_mutex_dequeue_pi
  - kernel/locking/rtmutex.c:rt_mutex_dequeue
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:__free_vmap_area
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedreceive
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/blk-throttle.c:__throtl_dequeue_tg
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_prio_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - lib/timerqueue.c:timerqueue_del
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - net/core/gen_estimator.c:gen_kill_estimator
```
**Symbols:**

```
ffffffff81436130-ffffffff8143647e: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81453120)
Location: lib/rbtree.c:439
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:rt_mutex_dequeue_pi
  - kernel/locking/rtmutex.c:rt_mutex_dequeue
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:__free_vmap_area
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedreceive
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/blk-throttle.c:__throtl_dequeue_tg
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_prio_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - lib/timerqueue.c:timerqueue_del
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81453120-ffffffff8145346e: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff818f3340)
Location: lib/rbtree.c:441
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:rt_mutex_dequeue_pi
  - kernel/locking/rtmutex.c:rt_mutex_dequeue
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:bdi_put
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:__free_vmap_area
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/blk-throttle.c:__throtl_dequeue_tg
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:put_iova_domain
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff818f3340-ffffffff818f36c0: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81979620)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:__free_vmap_area
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/blk-throttle.c:__throtl_dequeue_tg
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81979620-ffffffff819799a0: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819d5bd0)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/events/core.c:perf_event_groups_delete
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:__free_vmap_area
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/blk-throttle.c:__throtl_dequeue_tg
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_prio_tree_add
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff819d5bd0-ffffffff819d5f3d: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a0de00)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/events/core.c:perf_event_groups_delete
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:__free_vmap_area
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:ext4_es_remove_blks
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81a0de00-ffffffff81a0e16d: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a7dda0)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/events/core.c:perf_event_groups_delete
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:__free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:ext4_es_remove_blks
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:remove_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81a7dda0-ffffffff81a7e10d: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81ab50d0)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/events/core.c:perf_event_groups_delete
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:remove_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81ab50d0-ffffffff81ab543d: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815ef500)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:list_del_event
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:mem_cgroup_update_tree
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - lib/timerqueue.c:timerqueue_del
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_peer_gc
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
```
**Symbols:**

```
ffffffff815ef500-ffffffff815ef812: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81613c30)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:list_del_event
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:mem_cgroup_update_tree
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - lib/timerqueue.c:timerqueue_del
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_peer_gc
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:insert_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81613c30-ffffffff81613f76: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815f7290)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/events/core.c:list_del_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - lib/timerqueue.c:timerqueue_del
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:insert_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff815f7290-ffffffff815f75d6: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81664a20)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/module.c:free_module
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/events/core.c:list_del_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/elevator.c:elv_rb_del
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - lib/timerqueue.c:timerqueue_del
  - drivers/iommu/iova.c:remove_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/block/loop.c:loop_free_idle_workers
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
  - net/core/skbuff.c:skb_rbtree_purge
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:insert_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81664a20-ffffffff81664d66: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8177ed90)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_prepare_release
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/elevator.c:elv_rb_del
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - lib/timerqueue.c:timerqueue_del
  - drivers/iommu/iova.c:remove_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/block/loop.c:loop_free_idle_workers
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
  - net/core/skbuff.c:skb_rbtree_purge
  - net/core/dev_addr_lists.c:dev_addr_mod
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:insert_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff8177ed90-ffffffff8177f1e1: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8203ba30)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/xattr.c:simple_xattrs_free
  - fs/xattr.c:simple_xattr_set
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_prepare_release
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/elevator.c:elv_rb_del
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - drivers/iommu/iova.c:remove_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/block/loop.c:loop_free_idle_workers
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
  - net/core/skbuff.c:skb_rbtree_purge
  - net/core/dev_addr_lists.c:dev_addr_mod
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:insert_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff8203ba30-ffffffff8203be81: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff820b9f10)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/helpers.c:bpf_rbtree_remove
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/vmalloc.c:free_vmap_block
  - mm/vmalloc.c:find_unlink_vmap_area
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:shrink_worker
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/xattr.c:simple_xattrs_free
  - fs/xattr.c:simple_xattr_set
  - fs/eventpoll.c:__ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/elevator.c:elv_rb_del
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - drivers/iommu/iova.c:remove_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/block/loop.c:loop_free_idle_workers
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
  - net/core/skbuff.c:skb_rbtree_purge
  - net/core/dev_addr_lists.c:dev_addr_mod
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:insert_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff820b9f10-ffffffff820ba3f1: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff82194820)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/helpers.c:bpf_rbtree_remove
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/shmem_quota.c:shmem_release_dquot
  - mm/shmem_quota.c:shmem_free_file_info
  - mm/vmalloc.c:free_vmap_block
  - mm/vmalloc.c:find_unlink_vmap_area
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_invalidate_entry
  - mm/mempolicy.c:mpol_free_shared_policy
  - mm/mempolicy.c:shared_policy_replace
  - mm/ksm.c:ksm_check_stable_tree
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:umount_tree
  - fs/xattr.c:simple_xattrs_free
  - fs/xattr.c:simple_xattr_set
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/eventpoll.c:__ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_writepage
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_alloc
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/elevator.c:elv_rb_del
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:line_set_debounce_period
  - drivers/iommu/iova.c:remove_iova
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_exit
  - drivers/block/loop.c:loop_free_idle_workers
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/gpu/drm/drm_mm.c:rm_hole
  - drivers/gpu/drm/drm_prime.c:drm_prime_remove_buf_handle
  - drivers/gpu/drm/drm_prime.c:drm_prime_remove_buf_handle
  - drivers/gpu/drm/drm_vma_manager.c:drm_vma_node_revoke
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_hash_insert
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
  - net/core/skbuff.c:skb_rbtree_purge
  - net/core/dev_addr_lists.c:dev_addr_mod
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:insert_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff82194820-ffffffff82194d01: rb_erase (STB_GLOBAL)
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
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffff800010d8f148)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/events/core.c:perf_event_groups_delete
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:bdi_put
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:remove_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffff800010d8f148-ffff800010d8f4fc: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c0e898c8)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/events/core.c:perf_event_groups_delete
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:bdi_put
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:remove_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
c0e898c8-c0e89c90: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c000000000ed28b0)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_rmv_dev
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/events/core.c:perf_event_groups_delete
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:bdi_put
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - block/elevator.c:elv_rb_del
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:remove_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_del
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
c000000000ed28b0-c000000000ed2cec: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffe0008b79c0)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/events/core.c:perf_event_groups_delete
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:remove_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffe0008b79c0-ffffffe0008b7c10: rb_erase (STB_GLOBAL)
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
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a53f20)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/events/core.c:perf_event_groups_delete
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:remove_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81a53f20-ffffffff81a5428d: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a11000)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/events/core.c:perf_event_groups_delete
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:remove_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81a11000-ffffffff81a1136d: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81ac0310)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/events/core.c:perf_event_groups_delete
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:remove_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81ac0310-ffffffff81ac067d: rb_erase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rb_erase(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81acc7e0)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/module.c:__mod_tree_remove
  - kernel/module.c:__mod_tree_remove
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/events/core.c:perf_event_groups_delete
  - kernel/events/uprobes.c:__uprobe_unregister
  - mm/backing-dev.c:release_bdi
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_congested_put
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__free_vmap_area
  - mm/swapfile.c:destroy_swap_extents
  - mm/zswap.c:zswap_frontswap_invalidate_page
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_delete
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:remove_all_stable_nodes
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - fs/proc/proc_sysctl.c:erase_header
  - fs/kernfs/dir.c:kernfs_unlink_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__remove_pending
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/fuse/file.c:fuse_prepare_release
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - security/keys/gc.c:key_garbage_collector
  - security/apparmor/label.c:__label_remove
  - security/integrity/iint.c:integrity_inode_free
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/iommu/iova.c:split_and_remove_iova
  - drivers/base/regmap/regmap.c:regmap_range_exit
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_page_external
  - net/core/skbuff.c:skb_rbtree_purge
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/inet_fragment.c:inet_frag_pull_head
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_reasm_finish
  - net/ipv4/inet_fragment.c:inet_frag_rbtree_purge
  - net/ipv4/nexthop.c:remove_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - lib/timerqueue.c:timerqueue_del
```
**Symbols:**

```
ffffffff81acc7e0-ffffffff81accb4d: rb_erase (STB_GLOBAL)
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
