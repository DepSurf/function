# Function: <code>rb_prev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff813eff20)
Location: lib/rbtree.c:508
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pvm_determine_end
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:pvm_find_next_prev
  - mm/vmalloc.c:pcpu_get_vm_areas
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - block/elevator.c:elv_rb_former_request
  - block/cfq-iosched.c:cfq_close_cooperator
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff813eff20-ffffffff813eff5e: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81436880)
Location: lib/rbtree.c:508
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pvm_determine_end
  - mm/vmalloc.c:pvm_find_next_prev
  - mm/vmalloc.c:__free_vmap_area
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - block/elevator.c:elv_rb_former_request
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_find_next_rq
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff81436880-ffffffff814368c6: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81453870)
Location: lib/rbtree.c:523
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pvm_determine_end
  - mm/vmalloc.c:pvm_find_next_prev
  - mm/vmalloc.c:__free_vmap_area
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - block/elevator.c:elv_rb_former_request
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_find_next_rq
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
```
**Symbols:**

```
ffffffff81453870-ffffffff814538b6: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff818f3ad0)
Location: lib/rbtree.c:525
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pvm_determine_end
  - mm/vmalloc.c:pvm_find_next_prev
  - mm/vmalloc.c:__free_vmap_area
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - block/elevator.c:elv_rb_former_request
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_find_next_rq
  - drivers/iommu/iova.c:alloc_iova
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff818f3ad0-ffffffff818f3b16: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8197a4d0)
Location: lib/rbtree.c:560
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pvm_determine_end
  - mm/vmalloc.c:pvm_find_next_prev
  - mm/vmalloc.c:__free_vmap_area
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - block/elevator.c:elv_rb_former_request
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_find_next_rq
  - block/cfq-iosched.c:cfq_rb_erase
  - drivers/iommu/iova.c:alloc_iova
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff8197a4d0-ffffffff8197a516: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819d6a70)
Location: lib/rbtree.c:560
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pvm_determine_end
  - mm/vmalloc.c:pvm_find_next_prev
  - mm/vmalloc.c:__free_vmap_area
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - block/elevator.c:elv_rb_former_request
  - block/cfq-iosched.c:cfq_close_cooperator
  - block/cfq-iosched.c:cfq_find_next_rq
  - block/cfq-iosched.c:cfq_rb_erase
  - drivers/iommu/iova.c:alloc_iova
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff819d6a70-ffffffff819d6ab3: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a0eca0)
Location: lib/rbtree.c:560
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pvm_determine_end
  - mm/vmalloc.c:pvm_find_next_prev
  - mm/vmalloc.c:__free_vmap_area
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:alloc_iova
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81a0eca0-ffffffff81a0ece4: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a7dd50)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:alloc_iova
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81a7dd50-ffffffff81a7dd92: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81ab5080)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:alloc_iova
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81ab5080-ffffffff81ab50c2: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815efcc0)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:build_probe_list
  - kernel/events/uprobes.c:build_probe_list
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:mem_cgroup_update_tree
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff815efcc0-ffffffff815efd02: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81614420)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:build_probe_list
  - kernel/events/uprobes.c:build_probe_list
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:mem_cgroup_update_tree
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff81614420-ffffffff81614462: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815f7ab0)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff815f7ab0-ffffffff815f7af2: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81665240)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff81665240-ffffffff81665282: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8177f7d0)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff8177f7d0-ffffffff8177f829: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8203c510)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff8203c510-ffffffff8203c569: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff820baa40)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap
  - fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff820baa40-ffffffff820baa8e: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff82195350)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap
  - fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:__alloc_and_insert_iova_range
  - drivers/gpu/drm/drm_mm.c:drm_mm_insert_node_in_range
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
**Symbols:**

```
ffffffff82195350-ffffffff8219539e: rb_prev (STB_GLOBAL)
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
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffff800010d8f9e8)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:alloc_iova
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffff800010d8f9e8-ffff800010d8fa38: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c0e8a22c)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
c0e8a22c-c0e8a298: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c000000000ed2820)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/mempolicy.c:sp_lookup
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
c000000000ed2820-c000000000ed28a8: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffe0008b7f7a)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffe0008b7f7a-ffffffe0008b7fb2: rb_prev (STB_GLOBAL)
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
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a53ed0)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:alloc_iova
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81a53ed0-ffffffff81a53f12: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a10fb0)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:alloc_iova
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81a10fb0-ffffffff81a10ff2: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81ac02c0)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:alloc_iova
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81ac02c0-ffffffff81ac0302: rb_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct rb_node *rb_prev(const struct rb_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81acc790)
Location: lib/rbtree.c:524
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - mm/vmalloc.c:pcpu_get_vm_areas
  - fs/ext4/block_validity.c:add_system_zone
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_evict_inode
  - block/elevator.c:elv_rb_former_request
  - drivers/iommu/iova.c:alloc_iova
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
**Symbols:**

```
ffffffff81acc790-ffffffff81acc7d2: rb_prev (STB_GLOBAL)
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
