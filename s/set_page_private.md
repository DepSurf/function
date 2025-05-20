# Function: <code>set_page_private</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81169fc9)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff811a8097)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/events/ring_buffer.c (ffffffff81243bbb)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/shmem.c (ffffffff8126d3b5)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
```
```
In mm/compaction.c (ffffffff8128219c)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/memory.c (ffffffff81291ade)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/page_alloc.c (ffffffff812b45e6)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/swap_state.c (ffffffff812b908b)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812bfd09)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/hugetlb.c (ffffffff812c7092)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812e1638)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/migrate.c (ffffffff812e2d88)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/zsmalloc.c (ffffffff81305712)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
  - mm/zsmalloc.c:reset_page
```
```
In mm/balloon_compaction.c (ffffffff81307b06)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In fs/buffer.c (ffffffff8135bac9)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/crypto/crypto.c (ffffffff81390243)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff813abf5c)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/hugetlbfs/inode.c (ffffffff8145077e)
Location: include/linux/mm_types.h:244
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8171065a)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/md/md-bitmap.c (ffffffff819723e1)
Location: include/linux/mm_types.h:244
Inline: True
```
```
In net/core/skbuff.c (ffffffff819ee5be)
Location: include/linux/mm_types.h:244
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
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
In kernel/kexec_core.c (ffffffff81166709)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff811a5617)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/events/ring_buffer.c (ffffffff8124e24b)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/shmem.c (ffffffff81277ba5)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
```
```
In mm/compaction.c (ffffffff8128c317)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/memory.c (ffffffff8129c3df)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/page_alloc.c (ffffffff812c030c)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/swap_state.c (ffffffff812c483d)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812cb8b9)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/hugetlb.c (ffffffff812d2c01)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812ec588)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/migrate.c (ffffffff812ee1b8)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/zsmalloc.c (ffffffff81311472)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
  - mm/zsmalloc.c:reset_page
```
```
In mm/balloon_compaction.c (ffffffff81313836)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In fs/buffer.c (ffffffff8136a079)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/crypto/crypto.c (ffffffff813a1883)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff813bddb6)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/hugetlbfs/inode.c (ffffffff8146cc8e)
Location: include/linux/mm_types.h:247
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d23a)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/md/md-bitmap.c (ffffffff819772f1)
Location: include/linux/mm_types.h:247
Inline: True
```
```
In net/core/skbuff.c (ffffffff819ee260)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
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
In kernel/kexec_core.c (ffffffff811674a9)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff811a6be0)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - kernel/relay.c:relay_create_buf
```
```
In kernel/events/ring_buffer.c (ffffffff81252b82)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/shmem.c (ffffffff8127c905)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
```
```
In mm/compaction.c (ffffffff81290904)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/memory.c (ffffffff812a16ef)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/page_alloc.c (ffffffff812c5a80)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/memory_hotplug.c (ffffffff812c6e28)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/memory_hotplug.c:get_page_bootmem
```
```
In mm/swap_state.c (ffffffff812cb4db)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff812d250b)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/hugetlb.c (ffffffff812d96fd)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/migrate.c (ffffffff812f3ca8)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/zsmalloc.c (ffffffff8131753c)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
  - mm/zsmalloc.c:reset_page
```
```
In mm/balloon_compaction.c (ffffffff813199c6)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
```
```
In fs/buffer.c (ffffffff8136ff3d)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/crypto/crypto.c (ffffffff813a8a23)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff813c4f76)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/hugetlbfs/inode.c (ffffffff8147205e)
Location: include/linux/mm_types.h:247
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710faa)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/md/md-bitmap.c (ffffffff8195b80e)
Location: include/linux/mm_types.h:247
Inline: True
```
```
In net/core/skbuff.c (ffffffff819d3c8a)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
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
In kernel/kexec_core.c (ffffffff8118d018)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff811d0400)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - kernel/relay.c:relay_create_buf
```
```
In kernel/events/ring_buffer.c (ffffffff8128e454)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/shmem.c (ffffffff812baa65)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
```
```
In mm/compaction.c (ffffffff812d0af1)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/memory.c (ffffffff812e2615)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/page_alloc.c (ffffffff8130a187)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/swap_state.c (ffffffff8131056c)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81317dea)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/hugetlb.c (ffffffff813202f1)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__prep_new_huge_page
  - mm/hugetlb.c:__prep_new_huge_page
  - mm/hugetlb.c:__prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_hugetlb_page
```
```
In mm/migrate.c (ffffffff8133e654)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/hugetlb_cgroup.c (ffffffff8135e1c2)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/zsmalloc.c (ffffffff81363a9c)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - mm/zsmalloc.c:create_page_chain
  - mm/zsmalloc.c:reset_page
```
```
In mm/balloon_compaction.c (ffffffff813661b6)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/bootmem_info.c (ffffffff8136cb58)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
  - mm/bootmem_info.c:get_page_bootmem
```
```
In fs/buffer.c (ffffffff813beaa0)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/crypto/crypto.c (ffffffff813f817d)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff814149aa)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/hugetlbfs/inode.c (ffffffff814c89ee)
Location: include/linux/mm_types.h:262
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178dac4)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/md/md-bitmap.c (ffffffff81a01007)
Location: include/linux/mm_types.h:262
Inline: True
```
```
In net/core/skbuff.c (ffffffff81a8398a)
Location: include/linux/mm_types.h:262
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
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
In kernel/kexec_core.c (ffffffff811bc26b)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff81203c98)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/events/ring_buffer.c (ffffffff812e345b)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/shmem.c (ffffffff81318116)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
```
```
In mm/compaction.c (ffffffff8132f1b7)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/memory.c (ffffffff813443f2)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/page_alloc.c (ffffffff81372a32)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
```
```
In mm/swap_state.c (ffffffff8137b296)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff813834b8)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/hugetlb.c (ffffffff81389ad3)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:add_hugetlb_page
```
```
In mm/hugetlb_cgroup.c (ffffffff813d8605)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge_rsvd
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_commit_charge
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff813dd013)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - mm/memory-failure.c:ClearPageHWPoisonTakenOff
  - mm/memory-failure.c:SetPageHWPoisonTakenOff
```
```
In mm/zsmalloc.c (ffffffff813e1e3c)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:create_page_chain
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/balloon_compaction.c (ffffffff813e3197)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/bootmem_info.c (ffffffff813eaef2)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
  - mm/bootmem_info.c:get_page_bootmem
```
```
In fs/crypto/crypto.c (ffffffff81e78607)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/hugetlbfs/inode.c (ffffffff8155413e)
Location: include/linux/mm_types.h:330
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c627f)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In net/core/skbuff.c (ffffffff81bf9197)
Location: include/linux/mm_types.h:330
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
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
In kernel/kexec_core.c (ffffffff811fe49b)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff8124b8ae)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/events/ring_buffer.c (ffffffff8134bacb)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/compaction.c (ffffffff813a6029)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff813f01a2)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swap_state.c (ffffffff813f8b70)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81400eb8)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/hugetlb.c (ffffffff8140a7b3)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_huge_page
```
```
In mm/memory-failure.c (ffffffff81462f33)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - mm/memory-failure.c:ClearPageHWPoisonTakenOff
  - mm/memory-failure.c:SetPageHWPoisonTakenOff
```
```
In mm/zsmalloc.c (ffffffff8146941f)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:create_page_chain
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/balloon_compaction.c (ffffffff8146ab16)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/bootmem_info.c (ffffffff814730f2)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/crypto/crypto.c (ffffffff8206a3c5)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16bae)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In net/core/skbuff.c (ffffffff81da7fe0)
Location: include/linux/mm_types.h:467
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
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
In kernel/kexec_core.c (ffffffff81213766)
Location: include/linux/mm_types.h:412
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff81262b2e)
Location: include/linux/mm_types.h:412
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/events/ring_buffer.c (ffffffff8137cb1b)
Location: include/linux/mm_types.h:412
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mm_init.c (ffffffff82145ef9)
Location: include/linux/mm_types.h:412
Inline: True
```
```
In mm/compaction.c (ffffffff813d9d15)
Location: include/linux/mm_types.h:412
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff81423d22)
Location: include/linux/mm_types.h:412
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swap_state.c (ffffffff8142b959)
Location: include/linux/mm_types.h:412
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81433d97)
Location: include/linux/mm_types.h:412
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/memory-failure.c (ffffffff81498c23)
Location: include/linux/mm_types.h:412
Inline: True
Inline callers:
  - mm/memory-failure.c:ClearPageHWPoisonTakenOff
  - mm/memory-failure.c:SetPageHWPoisonTakenOff
```
```
In mm/zsmalloc.c (ffffffff8149e3ae)
Location: include/linux/mm_types.h:412
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:create_page_chain
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/balloon_compaction.c (ffffffff8149f9a6)
Location: include/linux/mm_types.h:412
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/bootmem_info.c (ffffffff814a7862)
Location: include/linux/mm_types.h:412
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/crypto/crypto.c (ffffffff81533406)
Location: include/linux/mm_types.h:412
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fc3e)
Location: include/linux/mm_types.h:412
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In net/core/skbuff.c (ffffffff81e16b43)
Location: include/linux/mm_types.h:412
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
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
In kernel/kexec_core.c (ffffffff8122b696)
Location: include/linux/mm_types.h:490
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (ffffffff8127cd4e)
Location: include/linux/mm_types.h:490
Inline: True
Inline callers:
  - kernel/relay.c:relay_alloc_buf
```
```
In kernel/events/ring_buffer.c (ffffffff813a5d78)
Location: include/linux/mm_types.h:490
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/mm_init.c (ffffffff82228619)
Location: include/linux/mm_types.h:490
Inline: True
```
```
In mm/compaction.c (ffffffff81403a62)
Location: include/linux/mm_types.h:490
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/page_alloc.c (ffffffff81450c0a)
Location: include/linux/mm_types.h:490
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swapfile.c (ffffffff8146d19c)
Location: include/linux/mm_types.h:490
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/hugetlb.c (ffffffff8391aa33)
Location: include/linux/mm_types.h:490
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_folio_init_tail_vmemmap
```
```
In mm/memory-failure.c (ffffffff814c81d3)
Location: include/linux/mm_types.h:490
Inline: True
Inline callers:
  - mm/memory-failure.c:ClearPageHWPoisonTakenOff
  - mm/memory-failure.c:SetPageHWPoisonTakenOff
```
```
In mm/zsmalloc.c (ffffffff814cd4df)
Location: include/linux/mm_types.h:490
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:create_page_chain
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/balloon_compaction.c (ffffffff814cf0f6)
Location: include/linux/mm_types.h:490
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_list_dequeue
  - mm/balloon_compaction.c:balloon_page_enqueue_one
```
```
In mm/bootmem_info.c (ffffffff814d8892)
Location: include/linux/mm_types.h:490
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/crypto/crypto.c (ffffffff8156832e)
Location: include/linux/mm_types.h:490
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab244e)
Location: include/linux/mm_types.h:490
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In net/core/skbuff.c (ffffffff81ed3f53)
Location: include/linux/mm_types.h:490
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_ubufs
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
