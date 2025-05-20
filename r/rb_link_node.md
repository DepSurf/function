# Function: <code>rb_link_node</code>

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
In arch/x86/mm/pat_rbtree.c (ffffffff81071f50)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
```
In kernel/sched/fair.c (ffffffff810b23cd)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810c1915)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/locking/rtmutex.c (ffffffff810cad45)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
```
```
In kernel/power/swap.c (ffffffff810d409e)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff810d6153)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff81155cf3)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/events/uprobes.c (ffffffff8118819e)
Location: include/linux/rbtree.h:80
Inline: True
```
```
In mm/backing-dev.c (ffffffff811aeb66)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffff811b8764)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:anon_vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff811c4b1d)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff811ccbf5)
Location: include/linux/rbtree.h:80
Inline: True
```
```
In mm/zswap.c (ffffffff811d8f63)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff811e037e)
Location: include/linux/rbtree.h:80
Inline: True
```
```
In mm/ksm.c (ffffffff811e5f2c)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memcontrol.c (ffffffff811fa02c)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff812563f0)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/proc/generic.c (ffffffff8127f2a2)
Location: include/linux/rbtree.h:80
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff812857cd)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffffffff8128a30c)
Location: include/linux/rbtree.h:80
Inline: True
```
```
In fs/ext4/dir.c (ffffffff812917e0)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/mballoc.c (ffffffff812cdeb9)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/block_validity.c (ffffffff812d61c8)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/extents_status.c (ffffffff812daf8d)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/fuse/file.c (ffffffff8131544a)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff8132be54)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff8132fdde)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - security/keys/key.c:key_user_lookup
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_init
```
```
In security/apparmor/label.c (ffffffff81389dbd)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff81396351)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff813b3346)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff813d9ad5)
Location: include/linux/rbtree.h:80
Inline: True
```
```
In block/cfq-iosched.c (ffffffff813dd842)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_group_service_tree_add
  - block/cfq-iosched.c:cfq_prio_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
```
```
In lib/timerqueue.c (ffffffff813f2228)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
```
```
In lib/interval_tree.c (ffffffff81404b99)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff8152cfa8)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/base/regmap/regmap.c (ffffffff815648fc)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81568d5f)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In net/core/gen_estimator.c (ffffffff8170f90e)
Location: include/linux/rbtree.h:80
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
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
In arch/x86/mm/pat_rbtree.c (ffffffff81072bd5)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810b4eed)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810c57ef)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/locking/rtmutex.c (ffffffff810cf8b3)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (ffffffff810d8e9d)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff810dafd5)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff8115f023)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/events/uprobes.c (ffffffff8119a841)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In mm/backing-dev.c (ffffffff811c7fa5)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffff811d2e01)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff811e093d)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff811e9cb5)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In mm/zswap.c (ffffffff811f6db3)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff811fe65e)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In mm/ksm.c (ffffffff81204dbb)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memcontrol.c (ffffffff8121dacc)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff8127ed14)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/proc/generic.c (ffffffff812ac2f4)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff812b290e)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffffffff812b7736)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In fs/ext4/dir.c (ffffffff812bed41)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/mballoc.c (ffffffff812fdb5e)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/block_validity.c (ffffffff81305e7c)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/extents_status.c (ffffffff8130a919)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/fuse/file.c (ffffffff81349c9d)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff81360af2)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff81fc2b92)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff813c4a1f)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff813d20b9)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff813f7049)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff8141f915)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In block/cfq-iosched.c (ffffffff81423ab2)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_prio_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_add
```
```
In lib/timerqueue.c (ffffffff81438bc8)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
```
```
In lib/interval_tree.c (ffffffff8144c74c)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff81580358)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/base/regmap/regmap.c (ffffffff815b9289)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff815bd91c)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In net/core/gen_estimator.c (ffffffff81777204)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
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
In arch/x86/mm/pat_rbtree.c (ffffffff81076785)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810bb3ad)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810cb7db)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/locking/rtmutex.c (ffffffff810d6293)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (ffffffff810df98d)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff810e1aa5)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff81169a43)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/events/uprobes.c (ffffffff811a9fb1)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In mm/backing-dev.c (ffffffff811d80c5)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffff811e2cc1)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff811f086d)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff811fb065)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In mm/zswap.c (ffffffff81207764)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff8120f39e)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In mm/ksm.c (ffffffff81216e91)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memcontrol.c (ffffffff812300ac)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff812928a4)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/proc/generic.c (ffffffff812c1be4)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff812c815e)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffffffff812ccf36)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In fs/ext4/dir.c (ffffffff812d4361)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/mballoc.c (ffffffff81313bde)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/ext4/block_validity.c (ffffffff8131be3c)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/extents_status.c (ffffffff81320919)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/fuse/file.c (ffffffff8135f5ad)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff81377472)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff81fff5ac)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff813dc06f)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff813e97d9)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff81410a59)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff8143ba35)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In block/cfq-iosched.c (ffffffff8143f1c2)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_prio_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_add
```
```
In lib/timerqueue.c (ffffffff81455bb8)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
```
```
In lib/interval_tree.c (ffffffff8146b10c)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff815acee1)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/base/regmap/regmap.c (ffffffff815e8548)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff815ecd2c)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In net/ipv4/tcp_input.c (ffffffff8180910a)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In arch/x86/mm/pat_rbtree.c (ffffffff81074e83)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810b5cdd)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810c779a)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/locking/rtmutex.c (ffffffff810d51b5)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (ffffffff810deafa)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff810e0bbf)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff8116c9c3)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/events/uprobes.c (ffffffff811b15b8)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In mm/backing-dev.c (ffffffff811e0fa1)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffff811ed12f)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff811fb6ec)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff81205d85)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In mm/zswap.c (ffffffff81212eae)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff8121acde)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In mm/ksm.c (ffffffff81222a0a)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memcontrol.c (ffffffff8123b9ba)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff8129fa37)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/proc/generic.c (ffffffff812cec15)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff812d52ea)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffffffff812da556)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In fs/ext4/block_validity.c (ffffffff812e4930)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff812e5d57)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff812ef877)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff8130a7c2)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/fuse/file.c (ffffffff81374156)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff8138afd2)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff820e2870)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff813ed037)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff813f5bd7)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff8141e4a7)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff81449d75)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In block/cfq-iosched.c (ffffffff8144e983)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_add
```
```
In lib/interval_tree.c (ffffffff814707fb)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff815c2a55)
Location: include/linux/rbtree.h:82
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff815fcec7)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81601552)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In net/ipv4/tcp_input.c (ffffffff818293b9)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In lib/timerqueue.c (ffffffff818f7496)
Location: include/linux/rbtree.h:82
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107b0b3)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810bcfc0)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810ced83)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/locking/rtmutex.c (ffffffff810dd058)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (ffffffff810e6d7a)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff810e8e8f)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff81179a65)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/events/uprobes.c (ffffffff811c5198)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In mm/backing-dev.c (ffffffff811f6fb1)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffff81203519)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff81213c1c)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff8121eaa5)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In mm/zswap.c (ffffffff8122d955)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff81235efe)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In mm/ksm.c (ffffffff8123ddc3)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memcontrol.c (ffffffff8125b250)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff812c2e73)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/proc/generic.c (ffffffff812f340c)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff812f9b2a)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffffffff812fedb6)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In fs/ext4/block_validity.c (ffffffff81309360)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff8130a767)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff81314377)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff8132f2a2)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/fuse/file.c (ffffffff81398ec9)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff813b0352)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff826eb529)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff81414687)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff8141dcc7)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff81448c47)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff814759d5)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In block/cfq-iosched.c (ffffffff8147a95a)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_add
```
```
In lib/interval_tree.c (ffffffff8149cf12)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff816295b5)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff81664ff9)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816698d2)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816aadc7)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In net/ipv4/inetpeer.c (ffffffff818937b4)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff818ae083)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In lib/timerqueue.c (ffffffff8197de96)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107de83)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810c4bb0)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810d667b)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/locking/rtmutex.c (ffffffff810e56e8)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (ffffffff810ee76d)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff810f11b9)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff81188c45)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/events/core.c (ffffffff811d3568)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff811e56f5)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In mm/backing-dev.c (ffffffff81218275)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffff812241d9)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff81234b59)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff8124077c)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In mm/zswap.c (ffffffff81250aee)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff81258d9e)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/mempolicy.c:sp_insert
```
```
In mm/ksm.c (ffffffff812610c3)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memcontrol.c (ffffffff8127efa7)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff812ebbba)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff813206ba)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffff813268d6)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffffffff8132c20c)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In fs/ext4/block_validity.c (ffffffff813372fa)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff81338717)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff81342253)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff8135dc74)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/fuse/file.c (ffffffff813c8f72)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff813e0386)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff82715ab4)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff81446a23)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff8144ff88)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff8147bd34)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff814a9e95)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In block/cfq-iosched.c (ffffffff814af704)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_prio_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_add
```
```
In lib/interval_tree.c (ffffffff814d2102)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff816642d5)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff816a0a17)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816a5253)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e7302)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In net/ipv4/inetpeer.c (ffffffff818e7b62)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81903733)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In lib/timerqueue.c (ffffffff819da376)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In arch/x86/mm/pat_rbtree.c (ffffffff81084a03)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810cdf80)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810e0bbb)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/locking/rtmutex.c (ffffffff810f0c78)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (ffffffff810f9dee)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff810fc709)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff811964f5)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffffffff811d8837)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff811e3908)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff811f610a)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In mm/backing-dev.c (ffffffff8122b1a5)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffff81237219)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff812482d9)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff8125506c)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In mm/zswap.c (ffffffff81264fca)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff8126d18e)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/mempolicy.c:sp_insert
```
```
In mm/ksm.c (ffffffff8127589f)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/memcontrol.c (ffffffff812937d7)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff812ffe04)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff813377b0)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffff8133d726)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffffffff813432dc)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In fs/ext4/block_validity.c (ffffffff8134e57a)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff8134f9c7)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff813598b7)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff81376214)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/fuse/file.c (ffffffff813e2f3b)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff813fab96)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff828cceff)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff81463ad3)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff8146cf66)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff8149a044)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff814c434b)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In lib/interval_tree.c (ffffffff814e6a32)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff816825a5)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff816c1420)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816c5d98)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8170a692)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In net/ipv4/inetpeer.c (ffffffff81914a12)
Location: include/linux/rbtree.h:105
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff8191641e)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
```
```
In net/ipv4/tcp_input.c (ffffffff819318d3)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In lib/timerqueue.c (ffffffff81a12596)
Location: include/linux/rbtree.h:105
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In arch/x86/mm/pat_rbtree.c (ffffffff81088697)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810d6342)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810e7638)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffffffff810f9396)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (ffffffff811024ad)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff81104dd8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff811a43a4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffffffff811ed327)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff811faad2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff8120de83)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/backing-dev.c (ffffffff8123ade4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffff812487b2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff8125a52d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff81268108)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/swapfile.c (ffffffff81278648)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/zswap.c (ffffffff8127fbe1)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff81288605)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mempolicy.c:sp_insert
```
```
In mm/ksm.c (ffffffff81291aa2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffffffff812ae9da)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff81320db3)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff8135f918)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffff81366281)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffffffff8136b546)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/ext4/block_validity.c (ffffffff81376ec5)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff8137865d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff81382911)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff8139f6fe)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/fuse/file.c (ffffffff8140ea4c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff81426f9a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff828e68c1)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff81490d8b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff8149a656)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff814c810a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff814f2af0)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In lib/interval_tree.c (ffffffff815133e6)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff816b9dce)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff816fc014)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81700f23)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81745edc)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In net/ipv4/inetpeer.c (ffffffff81976e3b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff81994fd9)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffff819cf61d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In lib/timerqueue.c (ffffffff81a81a7e)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In arch/x86/mm/pat_rbtree.c (ffffffff81089307)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e09c2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810f2c58)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffffffff81105186)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (ffffffff8110e8cd)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff81111193)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff811afb94)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffffffff811f9a6b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff81207ba2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff8121b4b3)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/backing-dev.c (ffffffff81249254)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffff81256c02)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff81268ac1)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff81277848)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/swapfile.c (ffffffff81288138)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/zswap.c (ffffffff8128f9d9)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff81298225)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/ksm.c (ffffffff812a1822)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffffffff812c03ea)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff81333b53)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff81377b78)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffff8137e511)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffffffff81383716)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/ext4/block_validity.c (ffffffff8138f12d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff81390a1d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff8139ae11)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff813b856e)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/fuse/file.c (ffffffff8142799c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff81440cda)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff828ef37a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff814aac3b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff814b4856)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff814e11fa)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff8150c070)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In lib/interval_tree.c (ffffffff81533e26)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff816dcbc0)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff817203c4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81725273)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8176a051)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d56c5)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In net/ipv4/inetpeer.c (ffffffff819ad7cb)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff819cbb29)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffff81a061ad)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In lib/timerqueue.c (ffffffff81ab8c85)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090d36)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810f1032)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810fa09c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff8110ff79)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (ffffffff81119924)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_extents_insert
```
```
In kernel/power/wakelock.c (ffffffff8111c397)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff811c7d54)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffffffff8121d8e9)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff81230b0a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff812465c5)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In mm/backing-dev.c (ffffffff8127754d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffff8128558e)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff81299af8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
```
```
In mm/vmalloc.c (ffffffff812ab1ab)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In mm/swapfile.c (ffffffff812ba2c8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_extent
```
```
In mm/zswap.c (ffffffff812c25ab)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff812cba95)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mempolicy.c:sp_insert
```
```
In mm/ksm.c (ffffffff812d5e14)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffffffff812f5602)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff8136e05b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff813c0392)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/generic.c:pde_subdir_insert
```
```
In fs/proc/proc_sysctl.c (ffffffff813c70c6)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
```
In fs/kernfs/dir.c (ffffffff813ce2b6)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_link_sibling
```
```
In fs/ext4/block_validity.c (ffffffff813da6c7)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff813dc00f)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff813e6593)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff814041b1)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/fuse/file.c (ffffffff814778bc)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
```
```
In ipc/mqueue.c (ffffffff81491a9a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff82d0462a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff815094d6)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff81513de6)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff8153fded)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff8156d43e)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - block/blk-throttle.c:__throtl_enqueue_tg
```
```
In lib/interval_tree.c (ffffffff81598249)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In lib/timerqueue.c (ffffffff815f3935)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
```
```
In drivers/iommu/iova.c (ffffffff81793ecf)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/regmap/regmap.c (ffffffff817dc4d4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817e16dc)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182beaf)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a06b4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In net/ipv4/inetpeer.c (ffffffff81a9776c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff81ab21a5)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5902)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810906f6)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810efcb2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810f8490)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff8110d129)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (ffffffff81115174)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_extents_insert
```
```
In kernel/power/wakelock.c (ffffffff81116cf7)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff811c5454)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffffffff812206ec)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff8123a71a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff81250c35)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In mm/backing-dev.c (ffffffff81281365)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/interval_tree.c (ffffffff8128f86e)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff812a4c8c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
```
```
In mm/vmalloc.c (ffffffff812b6654)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In mm/swapfile.c (ffffffff812c5d38)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_extent
```
```
In mm/zswap.c (ffffffff812ce3c4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff812d7435)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mempolicy.c:sp_insert
```
```
In mm/ksm.c (ffffffff812e191d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffffffff81300c82)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff8137b2c4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff813d21e2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/generic.c:pde_subdir_insert
```
```
In fs/proc/proc_sysctl.c (ffffffff813d9096)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
```
In fs/kernfs/dir.c (ffffffff813dfee6)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_link_sibling
```
```
In fs/ext4/block_validity.c (ffffffff813ec397)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff813eda9f)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff813f88c3)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff814173f1)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/fuse/file.c (ffffffff81492d43)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
```
```
In ipc/mqueue.c (ffffffff814af2aa)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff82ff19f7)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff815263a1)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff81530f44)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff8155c58d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff81587cee)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In lib/interval_tree.c (ffffffff815b3c69)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In lib/timerqueue.c (ffffffff81617fb5)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
```
```
In drivers/iommu/iova.c (ffffffff817c0c1f)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/regmap/regmap.c (ffffffff817f1770)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817f642c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183cf0f)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818af654)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In net/ipv4/inetpeer.c (ffffffff81aa1710)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff81abd16b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02762)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In net/mptcp/protocol.c (ffffffff81bbce9f)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff81021e83)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In arch/x86/mm/pat/memtype_interval.c (ffffffff81091196)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810f16e4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810fa610)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff81c36f4f)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/power/swap.c (ffffffff81115afd)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff81117427)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff811c6644)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffffffff8122417c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff8123ef78)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff812550e0)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In mm/backing-dev.c (ffffffff81286ad5)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/interval_tree.c (ffffffff81294ece)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff812aa3ec)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
```
```
In mm/vmalloc.c (ffffffff812bbd42)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In mm/swapfile.c (ffffffff812cc7b8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_extent
```
```
In mm/zswap.c (ffffffff812d4a64)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff812debe5)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mempolicy.c:sp_insert
```
```
In mm/ksm.c (ffffffff812e90ba)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffffffff81307448)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff81383081)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff813d9678)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffff813dff45)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
```
In fs/kernfs/dir.c (ffffffff813e6a96)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_link_sibling
```
```
In fs/ext4/block_validity.c (ffffffff813f28d7)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff813f414f)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff813ff933)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff8141c480)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/fuse/file.c (ffffffff81497cb3)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
```
```
In ipc/mqueue.c (ffffffff814b50ea)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff831fc2a7)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff8152bd2d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/landlock/ruleset.c (ffffffff81537d2c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/landlock/ruleset.c:insert_rule
```
```
In security/integrity/iint.c (ffffffff81539374)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff81564e2a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff8158eb3e)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In lib/interval_tree.c (ffffffff815bead6)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In lib/timerqueue.c (ffffffff815fb5d5)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
```
```
In drivers/iommu/iova.c (ffffffff817a3b3f)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/regmap/regmap.c (ffffffff817d609a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817dab7c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8181feeb)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81893e5d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/md/dm-ioctl.c (ffffffff819695ee)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c679)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff81aa7fb8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee070)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In net/mptcp/protocol.c (ffffffff81bac6ff)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff810259e0)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810a0d16)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In kernel/sched/core.c (ffffffff810f1f03)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In kernel/sched/fair.c (ffffffff8110b222)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff8111533f)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d554bf)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/power/swap.c (ffffffff81135d3d)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff811377b7)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff811f1c34)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffffffff8125c0bc)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff812799a8)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff81290b20)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In mm/backing-dev.c (ffffffff812c5e65)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In mm/interval_tree.c (ffffffff812d552e)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff812eba0a)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
```
```
In mm/vmalloc.c (ffffffff812fe17e)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In mm/swapfile.c (ffffffff81311b28)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_extent
```
```
In mm/zswap.c (ffffffff8131ad68)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff81326125)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/mempolicy.c:sp_insert
```
```
In mm/ksm.c (ffffffff81330fda)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffffffff813511d3)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff813d0305)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff8142ada8)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffff814318d5)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
```
In fs/kernfs/dir.c (ffffffff814385e5)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_link_sibling
```
```
In fs/ext4/block_validity.c (ffffffff814448b7)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff8144628f)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff81451f43)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff8146f880)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In fs/fuse/file.c (ffffffff814ef8c4)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
```
```
In ipc/mqueue.c (ffffffff8150d7aa)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff832e32f9)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff8158a10d)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/landlock/ruleset.c (ffffffff8159652c)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/landlock/ruleset.c:insert_rule
```
```
In security/integrity/iint.c (ffffffff81597bb4)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff815c91aa)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff815f4b9e)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In lib/interval_tree.c (ffffffff81625e06)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In lib/timerqueue.c (ffffffff81668ea5)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
```
```
In drivers/iommu/iova.c (ffffffff8182cc97)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/regmap/regmap.c (ffffffff81861654)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff8186639c)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/block/loop.c (ffffffff8186fdd5)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa5ab)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81927a21)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/md/dm-ioctl.c (ffffffff81a11a2a)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
```
```
In net/core/dev_addr_lists.c (ffffffff81aa81fe)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/ipv4/inetpeer.c (ffffffff81b477b9)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff81b643bf)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae420)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In net/mptcp/protocol.c (ffffffff81c7907f)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff810299cd)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810b4d76)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In kernel/sched/core.c (ffffffff8110dc73)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81126bac)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff811350ee)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f27134)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/power/swap.c (ffffffff8115817a)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff81159de4)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff8122a637)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffffffff812a5cbf)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff812ccb8d)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff812e5955)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In mm/backing-dev.c (ffffffff81324573)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/interval_tree.c (ffffffff81334732)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff8134e83c)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
```
```
In mm/vmalloc.c (ffffffff813653df)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In mm/swapfile.c (ffffffff8137ccca)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_extent
```
```
In mm/zswap.c (ffffffff81386665)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff813951f2)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/mempolicy.c:sp_insert
```
```
In mm/ksm.c (ffffffff8139ff83)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffffffff813c9a13)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff81458a50)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff814a43f4)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffff814abcb7)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
```
In fs/kernfs/dir.c (ffffffff814b37b6)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_link_sibling
```
```
In fs/ext4/block_validity.c (ffffffff814c0837)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff814c23ab)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff814ce5ac)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff814f0880)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In fs/fuse/file.c (ffffffff8157cd24)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
```
```
In ipc/mqueue.c (ffffffff8159fde9)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff83499636)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff8162b327)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/landlock/ruleset.c (ffffffff816388a2)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/landlock/ruleset.c:insert_rule
```
```
In security/integrity/iint.c (ffffffff8163c361)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff816743bd)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff816a65ce)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In lib/interval_tree.c (ffffffff816f6906)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In lib/timerqueue.c (ffffffff817828e3)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
```
```
In drivers/iommu/iova.c (ffffffff8196df5c)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/regmap/regmap.c (ffffffff819a91e1)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff819ae91a)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/block/loop.c (ffffffff819b678e)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4d9e)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7cd73)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/md/dm-ioctl.c (ffffffff81b7a1ba)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
```
```
In net/core/dev_addr_lists.c (ffffffff81c200c8)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/ipv4/inetpeer.c (ffffffff81cd49cf)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff81cf31e0)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffff81d415f4)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In net/mptcp/protocol.c (ffffffff81e1e039)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff8103043d)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810cfba6)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In kernel/sched/core.c (ffffffff811349a3)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In kernel/sched/fair.c (ffffffff8115014f)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8115f63e)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d2bf4)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/power/swap.c (ffffffff81189d0a)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff8118c094)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff81275eb7)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffffffff81303d3f)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff81334ba3)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff8134f500)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In mm/backing-dev.c (ffffffff81398ea3)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/interval_tree.c (ffffffff813ab3fc)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/vmalloc.c (ffffffff813e0cea)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In mm/swapfile.c (ffffffff813fa85a)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_extent
```
```
In mm/zswap.c (ffffffff81404483)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff81414da2)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/mempolicy.c:sp_insert
```
```
In mm/ksm.c (ffffffff8141ee03)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffffffff8144f093)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/xattr.c (ffffffff814b764b)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_add
  - fs/xattr.c:simple_xattr_set
```
```
In fs/eventpoll.c (ffffffff814e7580)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff81539854)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffff8154295d)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
```
In fs/kernfs/dir.c (ffffffff8154a626)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_link_sibling
```
```
In fs/ext4/block_validity.c (ffffffff815588e7)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff8155a61b)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff81566ddc)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff8158bec9)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In fs/fuse/file.c (ffffffff81622874)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
```
```
In ipc/mqueue.c (ffffffff816496a9)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff83ecf665)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff816dfc0a)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/landlock/ruleset.c (ffffffff816efd52)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/landlock/ruleset.c:insert_rule
```
```
In security/integrity/iint.c (ffffffff816f3b71)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff817300ad)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff81764b6c)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_service_queue_add
```
```
In lib/interval_tree.c (ffffffff817e8eb6)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff81ad889c)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/regmap/regmap.c (ffffffff81b1c2c5)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81b22413)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/block/loop.c (ffffffff81b2b99e)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b7224e)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/md/dm-ioctl.c (ffffffff81d1856a)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
```
```
In net/core/dev_addr_lists.c (ffffffff81dd202c)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/ipv4/inetpeer.c (ffffffff81e94caf)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff81eb7810)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a3e4)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In net/mptcp/protocol.c (ffffffff81ff69d0)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In lib/timerqueue.c (ffffffff8203f813)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030533)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d31e6)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In kernel/sched/core.c (ffffffff81143bcd)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In kernel/sched/fair.c (ffffffff8115efc0)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8116fdb7)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff82156f59)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/power/swap.c (ffffffff8119b1fa)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff8119d7b4)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff8128d877)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/helpers.c (ffffffff81321289)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_rbtree_add_impl
```
```
In kernel/bpf/local_storage.c (ffffffff813326e1)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff813658e3)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff813806d0)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In mm/backing-dev.c (ffffffff813cbe03)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/interval_tree.c (ffffffff813df7a2)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/vmalloc.c (ffffffff81415a6f)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In mm/swapfile.c (ffffffff8142d8ab)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_extent
```
```
In mm/zswap.c (ffffffff8143722d)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff81448336)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/mempolicy.c:sp_insert
```
```
In mm/ksm.c (ffffffff81453a16)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffffffff81484ac3)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/xattr.c (ffffffff814ec49b)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_add
  - fs/xattr.c:simple_xattr_set
```
```
In fs/eventpoll.c (ffffffff8151f3a7)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff81571ab5)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffff8157aa2d)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
```
In fs/kernfs/dir.c (ffffffff81582256)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_link_sibling
```
```
In fs/ext4/block_validity.c (ffffffff81590737)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff815923f4)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff8159ea88)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff815c2009)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/fuse/file.c (ffffffff8165acb4)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
```
```
In ipc/mqueue.c (ffffffff81681c09)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff836f46d5)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff8171922f)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/landlock/ruleset.c (ffffffff8172a272)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/landlock/ruleset.c:insert_rule
```
```
In security/integrity/iint.c (ffffffff8172dc90)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff8176c2dd)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff817a3c4c)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_service_queue_add
```
```
In lib/interval_tree.c (ffffffff81828e96)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff81b26994)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/regmap/regmap.c (ffffffff81b6b586)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81b717cd)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/block/loop.c (ffffffff81b7bc92)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5c5e)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/md/dm-ioctl.c (ffffffff81d8183a)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
```
```
In net/core/dev_addr_lists.c (ffffffff81e42bfc)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/ipv4/inetpeer.c (ffffffff81ef347f)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff81f15f40)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69f14)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In net/mptcp/protocol.c (ffffffff820730b0)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In lib/timerqueue.c (ffffffff820bdd33)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In arch/x86/events/intel/uncore_discovery.c (ffffffff81036803)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810db976)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In kernel/sched/core.c (ffffffff8114f0ed)
Location: include/linux/rbtree.h:59
Inline: True
```
```
In kernel/sched/fair.c (ffffffff811602ba)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8117d3a5)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff82239d99)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/power/swap.c (ffffffff811aa289)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff811ac933)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff812a8c96)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/helpers.c (ffffffff8134390c)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_rbtree_add_impl
```
```
In kernel/bpf/local_storage.c (ffffffff81356cb1)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff8138ea03)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff813a9a7f)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In mm/backing-dev.c (ffffffff813f6773)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/shmem_quota.c (ffffffff81409137)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/shmem_quota.c:shmem_acquire_dquot
```
```
In mm/interval_tree.c (ffffffff81409eb2)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/vmalloc.c (ffffffff8144254a)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In mm/swapfile.c (ffffffff8146736e)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_extent
```
```
In mm/zswap.c (ffffffff81470db2)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
```
```
In mm/mempolicy.c (ffffffff8148797b)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:shared_policy_replace
  - mm/mempolicy.c:shared_policy_replace
```
```
In mm/ksm.c (ffffffff8148e253)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffffffff814b3fc3)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/namespace.c (ffffffff81510ed7)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/namespace.c:mnt_add_to_ns
```
```
In fs/xattr.c (ffffffff8152037b)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/xattr.c:simple_xattr_add
  - fs/xattr.c:simple_xattr_set
```
```
In fs/eventpoll.c (ffffffff815539b7)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff815aa465)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffff815b330d)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_entry
```
```
In fs/kernfs/dir.c (ffffffff815bae86)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_link_sibling
```
```
In fs/ext4/block_validity.c (ffffffff815c9477)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff815cb14d)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff815d8327)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff815fab39)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
```
```
In fs/fuse/file.c (ffffffff81694984)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
  - fs/fuse/file.c:fuse_insert_writeback
```
```
In ipc/mqueue.c (ffffffff816bdfe9)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff839278e5)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff81757cbf)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/landlock/ruleset.c (ffffffff8176b73d)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/landlock/ruleset.c:insert_rule
```
```
In security/integrity/iint.c (ffffffff8176e624)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff817ae4cd)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff817e77bc)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_service_queue_add
```
```
In lib/interval_tree.c (ffffffff8187a8a6)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194f190)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:line_set_debounce_period
```
```
In drivers/iommu/iova.c (ffffffff81b7d5d4)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/iommu/iova.c:reserve_iova
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbf286)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81bc54e9)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/block/loop.c (ffffffff81bcfcc1)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a66d)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca1070)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:add_hole
  - drivers/gpu/drm/drm_mm.c:add_hole
  - drivers/gpu/drm/drm_mm.c:drm_mm_interval_tree_add_node
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81cabdca)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_prime.c:drm_prime_add_buf_handle
  - drivers/gpu/drm/drm_prime.c:drm_prime_add_buf_handle
```
```
In drivers/gpu/drm/drm_vma_manager.c (ffffffff81cb81db)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vma_manager.c:vma_node_allow
```
```
In drivers/md/dm-ioctl.c (ffffffff81e38eaa)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:__link_uuid
  - drivers/md/dm-ioctl.c:__link_name
```
```
In net/core/dev_addr_lists.c (ffffffff81f0184c)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_add_ex
```
```
In net/ipv4/inetpeer.c (ffffffff81fb740f)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff81fda34f)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffff820305c4)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In net/mptcp/protocol.c (ffffffff82147300)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In lib/timerqueue.c (ffffffff821985b3)
Location: include/linux/rbtree.h:59
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In arch/arm/xen/p2m.c (ffff8000100f05dc)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - arch/arm/xen/p2m.c:__set_phys_to_machine_multi
```
```
In kernel/sched/fair.c (ffff800010140824)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffff800010154ed4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffff80001016ae20)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/wakelock.c (ffff8000101715b4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffff80001022d134)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffff80001027f4b4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffff8000102913a8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffff8000102a6bd0)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/backing-dev.c (ffff8000102de19c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffff8000102ee4d0)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffff800010300048)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffff80001030dd60)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/swapfile.c (ffff800010323008)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/zswap.c (ffff80001032c33c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffff800010336fd4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mempolicy.c:sp_insert
```
```
In mm/ksm.c (ffff8000103410c0)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffff800010361d68)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffff8000103f18f8)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/proc/generic.c (ffff8000104439c0)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffff80001044af58)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffff800010451cb4)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/ext4/block_validity.c (ffff800010461928)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffff800010463364)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffff80001046d8bc)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffff80001048f788)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/fuse/file.c (ffff80001050c720)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffff800010529308)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffff800011469000)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffff8000105a1ea4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffff8000105ac82c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffff8000105de124)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffff80001060fc4c)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In lib/interval_tree.c (ffff800010640754)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffff8000108ccb6c)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffff8000109146d0)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffff800010919f18)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096bb0c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In net/ipv4/inetpeer.c (ffff800010c5dc08)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffff800010c7e778)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffff800010cbe874)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In lib/timerqueue.c (ffff800010d93278)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (c0390e50)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (c03a2334)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (c03b6978)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (c03c1f70)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (c03c3f68)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (c046a894)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (c04b084c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (c04c2114)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (c04d5d20)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/backing-dev.c (c0502cf8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (c0512318)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (c051eaf0)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (c052978c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/swapfile.c (c053b360)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_extent
```
```
In mm/zswap.c (c0542668)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (c05474bc)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
```
```
In mm/memcontrol.c (c0554784)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (c05c72c8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (c0608ba8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (c06102fc)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (c0615464)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/ext4/block_validity.c (c0621f08)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (c0623a98)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (c062f038)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (c064ffec)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/fuse/file.c (c06c6020)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (c06e2e9c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (c1541b14)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (c0752554)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (c075c210)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (c078b250)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (c07ba348)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In lib/interval_tree.c (c07e60f8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/base/regmap/regmap.c (c09fab3c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (c09ffb94)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (c0a4159c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In net/ipv4/inetpeer.c (c0d6cff0)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (c0d8d778)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (c0dca820)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In lib/timerqueue.c (c0e8f9f8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In arch/powerpc/kernel/eeh_cache.c (c0000000000484a8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_insert_dev
```
```
In arch/powerpc/perf/hv-24x7.c (c00000000012f7f0)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In kernel/sched/fair.c (c0000000001906c4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (c0000000001a8d84)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (c0000000001c2708)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/wakelock.c (c0000000001c9df8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (c0000000002b5c7c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (c0000000003296a8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (c00000000033f294)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (c000000000359e20)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/backing-dev.c (c00000000039e0d0)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (c0000000003b25a0)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (c0000000003cbe5c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (c0000000003de9b0)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/swapfile.c (c0000000003f8ea0)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_extent
```
```
In mm/zswap.c (c000000000403014)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (c0000000004115c4)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/ksm.c (c00000000041ea6c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (c00000000044e140)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (c0000000004f916c)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/proc/generic.c (c000000000559004)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (c000000000562eac)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (c00000000056b548)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/ext4/block_validity.c (c00000000057e0cc)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (c000000000580334)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (c00000000058d7c8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (c0000000005b53ac)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/fuse/file.c (c000000000650154)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (c000000000675230)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (c000000001397040)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (c00000000071cc8c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (c00000000072ad30)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (c00000000076f98c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (c0000000007ad184)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In lib/interval_tree.c (c0000000007eab9c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/base/regmap/regmap.c (c0000000009b6bd0)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (c0000000009bdf08)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (c000000000a2416c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In net/ipv4/inetpeer.c (c000000000d6016c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (c000000000d88a78)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (c000000000dd9a68)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In lib/timerqueue.c (c000000000ed74c4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (ffffffe0000eed6e)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffe0000fc980)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffffffe00010b476)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/trace/trace_stat.c (ffffffe000186d20)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffffffe0001b6106)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffe0001c3e00)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In mm/backing-dev.c (ffffffe0001f67ca)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffe00020264e)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffe00020da4c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffe000215ee2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/swapfile.c (ffffffe000223b12)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/zswap.c (ffffffe00022af48)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffe000235146)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
```
```
In mm/memcontrol.c (ffffffe00024169a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffe0002a4206)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffe0002da49a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffe0002e0130)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffffffe0002e4922)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/ext4/block_validity.c (ffffffe0002f0962)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffe0002f1de6)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffe0002fab2c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffe000313dfa)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/fuse/file.c (ffffffe000376e48)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffe00038c71c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffe000024236)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffe0003ec712)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffe0003f5026)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffe000420da8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffe000447b0a)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In lib/interval_tree.c (ffffffe00046d074)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/base/regmap/regmap.c (ffffffe000595dfc)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffe00059a07e)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d6a72)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In net/ipv4/inetpeer.c (ffffffe0007c6408)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0ad6)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffe000814e6a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In lib/timerqueue.c (ffffffe0008bd43e)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In arch/x86/mm/pat_rbtree.c (ffffffff810882c7)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810dab72)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810ec058)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffffffff810fe496)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (ffffffff81106e9d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff81109773)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff811a81b4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffffffff811f208b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff812001c2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff81213b03)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/backing-dev.c (ffffffff812418a4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffff8124f252)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff81261111)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff8126fe98)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/swapfile.c (ffffffff81280718)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/zswap.c (ffffffff81287fb9)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff81290805)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/ksm.c (ffffffff81299e02)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffffffff812b89ca)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff8132c133)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff81370158)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffff81376af1)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffffffff8137bcf6)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/ext4/block_validity.c (ffffffff8138770d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff81388ffd)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff813933f1)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff813b0b4e)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/fuse/file.c (ffffffff8141ff7c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff814392ba)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff828d822e)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff814a321b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff814ace36)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff814d97da)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff81504650)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In lib/interval_tree.c (ffffffff8152c406)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff816a2610)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff816e66f4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816eb5a3)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8171e741)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In net/ipv4/inetpeer.c (ffffffff8194d63b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff8196b999)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5f4d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In lib/timerqueue.c (ffffffff81a57ad5)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In arch/x86/mm/pat_rbtree.c (ffffffff81076f27)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810c9b82)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810dc078)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffffffff810ee696)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (ffffffff810f7d8d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff810fa653)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff8119b134)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffffffff811e4ddb)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff811f2fc2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff81206873)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/backing-dev.c (ffffffff81234894)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffff812421f2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff81253531)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff81261e08)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/swapfile.c (ffffffff81272588)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/zswap.c (ffffffff81279e19)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff81282485)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/ksm.c (ffffffff8128b9c2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffffffff812a9b9a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff8131d4a3)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff81360be8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffff813675c1)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffffffff8136c7c6)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/ext4/block_validity.c (ffffffff8137819d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff81379a8d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff81383e81)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff813a15de)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/fuse/file.c (ffffffff814109fc)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff81429d2a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff828d094a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff81493c3b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff8149d856)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff814ca18a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff814f4b10)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In lib/interval_tree.c (ffffffff8151c6e6)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff81680000)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff816c0d34)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816c5be3)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816f7b8b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177f775)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In net/ipv4/inetpeer.c (ffffffff8190712b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff81925489)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fa0d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In lib/timerqueue.c (ffffffff81a14bb5)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In arch/x86/mm/pat_rbtree.c (ffffffff81088277)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810d6ef2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810e9188)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffffffff810fb656)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (ffffffff81104d9d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff81107663)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff811a5f84)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffffffff811efe5b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff811fdf92)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff812118a3)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/backing-dev.c (ffffffff8123f644)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffff8124cff2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff8125eeb1)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff8126dc38)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/swapfile.c (ffffffff8127e528)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/zswap.c (ffffffff81285dc9)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff8128e615)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/ksm.c (ffffffff81297c12)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffffffff812b67da)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff81329c03)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/generic.c (ffffffff8136dc28)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffff813745c1)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffffffff813797c6)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/ext4/block_validity.c (ffffffff813851dd)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff8138695d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff81390d51)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff813ae3ae)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/fuse/file.c (ffffffff8141c11c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff8143545a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff828eafae)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff8149f2bb)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff814a8ed6)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff814d586a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff815006e0)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In lib/interval_tree.c (ffffffff81528496)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff816d0880)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff81713884)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81718733)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8175d511)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817ca545)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In net/ipv4/inetpeer.c (ffffffff819b7e0b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff819d6169)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffff81a107ed)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In lib/timerqueue.c (ffffffff81ac3ec5)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In arch/x86/mm/pat_rbtree.c (ffffffff8108a517)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e28a2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810f4138)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffffffff81106826)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/power/swap.c (ffffffff8111017d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff81112a23)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/trace/trace_stat.c (ffffffff811b3d24)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/bpf/local_storage.c (ffffffff811fe36b)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/events/core.c (ffffffff8120d0a2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_insert
```
```
In kernel/events/uprobes.c (ffffffff812207ec)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/backing-dev.c (ffffffff8124edc4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/interval_tree.c (ffffffff8125c9b2)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff8126e881)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff8127d5f8)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In mm/swapfile.c (ffffffff8128e8b8)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/zswap.c (ffffffff81295b68)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/mempolicy.c (ffffffff8129e515)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In mm/ksm.c (ffffffff812a7a04)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
```
In mm/memcontrol.c (ffffffff812c709a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_insert_exceeded
```
```
In fs/eventpoll.c (ffffffff8133c5ae)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/proc/generic.c (ffffffff81381558)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_register
```
```
In fs/proc/proc_sysctl.c (ffffffff81387fd1)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:insert_header
```
```
In fs/kernfs/dir.c (ffffffff8138d916)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In fs/ext4/block_validity.c (ffffffff81398d5d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:add_system_zone
```
```
In fs/ext4/dir.c (ffffffff8139a63d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_htree_store_dirent
```
```
In fs/ext4/extents_status.c (ffffffff813a4be1)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__insert_pending
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/mballoc.c (ffffffff813c29be)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
```
```
In fs/fuse/file.c (ffffffff81431c5c)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff8144cafa)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:msg_insert
```
```
In security/keys/key.c (ffffffff828f03c4)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/keys/key.c:key_init
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/label.c (ffffffff814b78eb)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
```
```
In security/integrity/iint.c (ffffffff814c18c6)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_inode_get
```
```
In block/elevator.c (ffffffff814ee48a)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - block/elevator.c:elv_rb_add
```
```
In block/blk-throttle.c (ffffffff815196f0)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In lib/interval_tree.c (ffffffff81541e76)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/iommu/iova.c (ffffffff816eae10)
Location: include/linux/rbtree.h:69
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff8172ea74)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81733a93)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81778bb1)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e47e5)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In net/ipv4/inetpeer.c (ffffffff819c1688)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/tcp_input.c (ffffffff819dfd89)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rbtree_insert
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b03d)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
  - net/ipv4/inet_fragment.c:inet_frag_queue_insert
```
```
In lib/timerqueue.c (ffffffff81ad0395)
Location: include/linux/rbtree.h:69
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
```
</details>
</li>
</ul>

## Differences
