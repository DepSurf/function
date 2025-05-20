# Function: <code>rb_insert_color</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff813ef6d0)
Location: lib/rbtree.c:418
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_init
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - block/cfq-iosched.c:cfq_group_service_tree_add
  - block/cfq-iosched.c:cfq_prio_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - lib/timerqueue.c:timerqueue_add
  - drivers/iommu/iova.c:alloc_iova
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - net/core/gen_estimator.c:gen_new_estimator
```
**Symbols:**

```
ffffffff813ef6d0-ffffffff813ef854: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81435fa0)
Location: lib/rbtree.c:418
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - block/cfq-iosched.c:cfq_prio_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_add
  - lib/timerqueue.c:timerqueue_add
  - drivers/iommu/iova.c:alloc_iova
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - net/core/gen_estimator.c:gen_new_estimator
```
**Symbols:**

```
ffffffff81435fa0-ffffffff81436129: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81452f90)
Location: lib/rbtree.c:433
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - block/cfq-iosched.c:cfq_prio_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_add
  - lib/timerqueue.c:timerqueue_add
  - drivers/iommu/iova.c:alloc_iova
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81452f90-ffffffff81453119: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff818f31b0)
Location: lib/rbtree.c:435
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_add
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffffffff818f31b0-ffffffff818f333a: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81979b50)
Location: lib/rbtree.c:450
Inline: False
Direct callers:
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffffffff81979b50-ffffffff81979cdd: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819d5a80)
Location: lib/rbtree.c:450
Inline: False
Direct callers:
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/events/core.c:perf_event_groups_insert
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_insert
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - block/cfq-iosched.c:cfq_prio_tree_add
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffffffff819d5a80-ffffffff819d5bcc: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a0dcb0)
Location: lib/rbtree.c:450
Inline: False
Direct callers:
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_insert
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffffffff81a0dcb0-ffffffff81a0ddfc: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a7da20)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_insert
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffffffff81a7da20-ffffffff81a7db58: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81ab4d50)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - lib/timerqueue.c:timerqueue_add
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffffffff81ab4d50-ffffffff81ab4e88: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815ef9b0)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/power/swap.c:swsusp_extents_insert
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/backing-dev.c:wb_congested_get_create
  - mm/swapfile.c:add_swap_extent
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:pde_subdir_insert
  - fs/proc/proc_sysctl.c:insert_entry
  - fs/kernfs/dir.c:kernfs_link_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - block/blk-throttle.c:__throtl_enqueue_tg
  - lib/timerqueue.c:timerqueue_add
  - drivers/iommu/iova.c:init_iova_domain
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:nexthop_add
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
```
**Symbols:**

```
ffffffff815ef9b0-ffffffff815efacd: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81614110)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/power/swap.c:swsusp_extents_insert
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/swapfile.c:add_swap_extent
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:pde_subdir_insert
  - fs/proc/proc_sysctl.c:insert_entry
  - fs/kernfs/dir.c:kernfs_link_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - lib/timerqueue.c:timerqueue_add
  - drivers/iommu/iova.c:init_iova_domain
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:insert_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81614110-ffffffff8161422d: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815f7770)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/swapfile.c:add_swap_extent
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_entry
  - fs/kernfs/dir.c:kernfs_link_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/landlock/ruleset.c:insert_rule
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - lib/timerqueue.c:timerqueue_add
  - lib/timerqueue.c:timerqueue_add
  - drivers/iommu/iova.c:init_iova_domain
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:insert_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff815f7770-ffffffff815f7890: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81664f00)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/swapfile.c:add_swap_extent
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_insert
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_entry
  - fs/kernfs/dir.c:kernfs_link_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/landlock/ruleset.c:insert_rule
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - lib/timerqueue.c:timerqueue_add
  - lib/timerqueue.c:timerqueue_add
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/iommu/iova.c:init_iova_domain
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:insert_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff81664f00-ffffffff81665020: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8177f410)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/backing-dev.c:bdi_register_va
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/swapfile.c:add_swap_extent
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_entry
  - fs/kernfs/dir.c:kernfs_link_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/landlock/ruleset.c:insert_rule
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - lib/timerqueue.c:timerqueue_add
  - lib/timerqueue.c:timerqueue_add
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/iommu/iova.c:init_iova_domain
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
  - net/core/dev_addr_lists.c:dev_addr_mod
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:insert_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
**Symbols:**

```
ffffffff8177f410-ffffffff8177f57c: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8203c120)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/backing-dev.c:bdi_register_va
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/swapfile.c:add_swap_extent
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/xattr.c:simple_xattr_add
  - fs/xattr.c:simple_xattr_set
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_entry
  - fs/kernfs/dir.c:kernfs_link_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/landlock/ruleset.c:insert_rule
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - block/blk-throttle.c:tg_service_queue_add
  - block/blk-throttle.c:tg_service_queue_add
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/iommu/iova.c:init_iova_domain
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
  - net/core/dev_addr_lists.c:dev_addr_mod
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:insert_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - lib/timerqueue.c:timerqueue_add
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffffffff8203c120-ffffffff8203c28c: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff820ba690)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/helpers.c:bpf_rbtree_add_impl
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/backing-dev.c:bdi_register_va
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/swapfile.c:add_swap_extent
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/xattr.c:simple_xattr_add
  - fs/xattr.c:simple_xattr_set
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_entry
  - fs/kernfs/dir.c:kernfs_link_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/landlock/ruleset.c:insert_rule
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - block/blk-throttle.c:tg_service_queue_add
  - block/blk-throttle.c:tg_service_queue_add
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/iommu/iova.c:init_iova_domain
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
  - net/core/dev_addr_lists.c:dev_addr_mod
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:insert_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - lib/timerqueue.c:timerqueue_add
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffffffff820ba690-ffffffff820ba812: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff82194fa0)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/core.c:bpf_ksym_add
  - kernel/bpf/helpers.c:bpf_rbtree_add_impl
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/uprobes.c:alloc_uprobe
  - mm/backing-dev.c:bdi_register_va
  - mm/shmem_quota.c:shmem_acquire_dquot
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/swapfile.c:add_swap_extent
  - mm/zswap.c:zswap_store
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/namespace.c:mnt_add_to_ns
  - fs/xattr.c:simple_xattr_add
  - fs/xattr.c:simple_xattr_set
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_entry
  - fs/kernfs/dir.c:kernfs_link_sibling
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/landlock/ruleset.c:insert_rule
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - block/blk-throttle.c:tg_service_queue_add
  - block/blk-throttle.c:tg_service_queue_add
  - drivers/gpio/gpiolib-cdev.c:line_set_debounce_period
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/iommu/iova.c:init_iova_domain
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/block/loop.c:loop_queue_work
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/gpu/drm/drm_mm.c:add_hole
  - drivers/gpu/drm/drm_prime.c:drm_prime_add_buf_handle
  - drivers/gpu/drm/drm_prime.c:drm_prime_add_buf_handle
  - drivers/gpu/drm/drm_vma_manager.c:vma_node_allow
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
  - net/core/dev_addr_lists.c:dev_addr_mod
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:insert_nexthop
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - lib/timerqueue.c:timerqueue_add
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffffffff82194fa0-ffffffff82195122: rb_insert_color (STB_GLOBAL)
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
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffff800010d8f6a0)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/core.c:perf_event_groups_insert
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/mempolicy.c:sp_insert
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - lib/timerqueue.c:timerqueue_add
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffff800010d8f6a0-ffff800010d8f7ec: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c0e89e84)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:wb_congested_get_create
  - mm/swapfile.c:add_swap_extent
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
c0e89e84-c0e89ff8: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c000000000ed2350)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_insert_dev
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/core.c:perf_event_groups_insert
  - mm/backing-dev.c:wb_congested_get_create
  - mm/swapfile.c:add_swap_extent
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_header
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - lib/timerqueue.c:timerqueue_add
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
c000000000ed2350-c000000000ed250c: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffe0008b7d36)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffffffe0008b7d36-ffffffe0008b7e34: rb_insert_color (STB_GLOBAL)
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
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a53ba0)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - lib/timerqueue.c:timerqueue_add
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffffffff81a53ba0-ffffffff81a53cd8: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a10c80)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - lib/timerqueue.c:timerqueue_add
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffffffff81a10c80-ffffffff81a10db8: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81abff90)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:ep_insert
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - lib/timerqueue.c:timerqueue_add
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffffffff81abff90-ffffffff81ac00c8: rb_insert_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rb_insert_color(struct rb_node *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81acc460)
Location: lib/rbtree.c:434
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/module.c:__mod_tree_insert
  - kernel/module.c:__mod_tree_insert
  - kernel/trace/trace_stat.c:insert_stat
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/events/core.c:perf_event_groups_insert
  - mm/backing-dev.c:wb_congested_get_create
  - mm/zswap.c:zswap_frontswap_store
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/proc/generic.c:proc_register
  - fs/proc/proc_sysctl.c:insert_header
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/dir.c:ext4_htree_store_dirent
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/fuse/file.c:fuse_file_poll
  - ipc/mqueue.c:msg_insert
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/apparmor/label.c:__label_insert
  - security/integrity/iint.c:integrity_inode_get
  - block/elevator.c:elv_rb_add
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - lib/timerqueue.c:timerqueue_add
  - lib/timerqueue.c:timerqueue_add
```
**Symbols:**

```
ffffffff81acc460-ffffffff81acc598: rb_insert_color (STB_GLOBAL)
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
