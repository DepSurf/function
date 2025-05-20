# Function: <code>page_size</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81258bb4)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff81271820)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81273f79)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/page_alloc.c (ffffffff81281c17)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff81297e15)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff8129b721)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff812a3b29)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/slub.c:__ksize
  - mm/slub.c:allocate_slab
```
```
In mm/memory_hotplug.c (ffffffff812ac1da)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812b0d21)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9ff5)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812ca7d6)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812cddb7)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/io_uring.c (ffffffff81341251)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In lib/iov_iter.c (ffffffff81524f77)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (ffffffff81aab8c7)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/page_vma_mapped.c (ffffffff812a1ee6)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812a51f9)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/page_alloc.c (ffffffff812b400b)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff812b5d12)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/hugetlb.c (ffffffff812cb4e5)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff812cf2a1)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff812d8409)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - mm/slub.c:__ksize
  - mm/slub.c:allocate_slab
```
```
In mm/memory_hotplug.c (ffffffff812e10ba)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812e26c8)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:copy_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812ffd35)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff81300416)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/page_isolation.c (ffffffff813040c7)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/io_uring.c (ffffffff8137c35a)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In lib/iov_iter.c (ffffffff815897bb)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In net/xdp/xsk.c (ffffffff81ba71d7)
Location: include/linux/mm.h:923
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/truncate.c (ffffffff8126ad98)
Location: include/linux/mm.h:964
Inline: True
```
```
In mm/shmem.c (ffffffff81276e70)
Location: include/linux/mm.h:964
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812ad7ce)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812b06ba)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/page_alloc.c (ffffffff812bfa9f)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff812c178b)
Location: include/linux/mm.h:964
Inline: True
```
```
In mm/hugetlb.c (ffffffff812d7105)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff812dad21)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff812e3e69)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - mm/slub.c:__ksize
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812ed3b0)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:copy_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8130c0d5)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff8130d4d1)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In fs/libfs.c (ffffffff81351d97)
Location: include/linux/mm.h:964
Inline: True
```
```
In fs/buffer.c (ffffffff81367617)
Location: include/linux/mm.h:964
Inline: True
```
```
In fs/direct-io.c (ffffffff8136f3bd)
Location: include/linux/mm.h:964
Inline: True
```
```
In fs/mpage.c (ffffffff813712b3)
Location: include/linux/mm.h:964
Inline: True
```
```
In fs/io_uring.c (ffffffff8138a52a)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/iomap/buffered-io.c (ffffffff813bbca7)
Location: include/linux/mm.h:964
Inline: True
```
```
In fs/ext4/inline.c (ffffffff814056e8)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff81408427)
Location: include/linux/mm.h:964
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff81421d2d)
Location: include/linux/mm.h:964
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff8142aed3)
Location: include/linux/mm.h:964
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8142c6a4)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e574)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff814917a8)
Location: include/linux/mm.h:964
Inline: True
```
```
In block/bio.c (ffffffff8155aac0)
Location: include/linux/mm.h:964
Inline: True
```
```
In lib/iov_iter.c (ffffffff815a5b0f)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183b2ab)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In net/xdp/xsk.c (ffffffff81bb694a)
Location: include/linux/mm.h:964
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/truncate.c (ffffffff8126ff4a)
Location: include/linux/mm.h:987
Inline: True
```
```
In mm/shmem.c (ffffffff8127bed2)
Location: include/linux/mm.h:987
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812b2bc2)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/page_alloc.c (ffffffff812c51ff)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff812c8681)
Location: include/linux/mm.h:987
Inline: True
```
```
In mm/hugetlb.c (ffffffff812de6f5)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff812e2581)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff812eb899)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - mm/slub.c:__ksize
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812f3750)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff813126d5)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff813145da)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In fs/libfs.c (ffffffff81358ab9)
Location: include/linux/mm.h:987
Inline: True
```
```
In fs/buffer.c (ffffffff8136e059)
Location: include/linux/mm.h:987
Inline: True
```
```
In fs/direct-io.c (ffffffff81375c6f)
Location: include/linux/mm.h:987
Inline: True
```
```
In fs/mpage.c (ffffffff81377c65)
Location: include/linux/mm.h:987
Inline: True
```
```
In fs/io_uring.c (ffffffff813915e2)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/iomap/buffered-io.c (ffffffff813c3939)
Location: include/linux/mm.h:987
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8140ba26)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff8140e739)
Location: include/linux/mm.h:987
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff8142852f)
Location: include/linux/mm.h:987
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81431a45)
Location: include/linux/mm.h:987
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81433373)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff81484048)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff814966ca)
Location: include/linux/mm.h:987
Inline: True
```
```
In block/bio.c (ffffffff815630c7)
Location: include/linux/mm.h:987
Inline: True
```
```
In lib/iov_iter.c (ffffffff815ad9cd)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e4b9)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In net/xdp/xsk.c (ffffffff81ba58ea)
Location: include/linux/mm.h:987
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/truncate.c (ffffffff812ad35b)
Location: include/linux/mm.h:991
Inline: True
```
```
In mm/shmem.c (ffffffff812ba049)
Location: include/linux/mm.h:991
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812f475e)
Location: include/linux/mm.h:991
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812f8ad8)
Location: include/linux/mm.h:991
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
```
```
In mm/page_alloc.c (ffffffff8130973f)
Location: include/linux/mm.h:991
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff8130d603)
Location: include/linux/mm.h:991
Inline: True
```
```
In mm/hugetlb.c (ffffffff81325a55)
Location: include/linux/mm.h:991
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff813297a4)
Location: include/linux/mm.h:991
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff8133427b)
Location: include/linux/mm.h:991
Inline: True
Inline callers:
  - mm/slub.c:__ksize
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff8133dca7)
Location: include/linux/mm.h:991
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8135e135)
Location: include/linux/mm.h:991
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff81360752)
Location: include/linux/mm.h:991
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In fs/libfs.c (ffffffff813a70ef)
Location: include/linux/mm.h:991
Inline: True
```
```
In fs/buffer.c (ffffffff813bcdbf)
Location: include/linux/mm.h:991
Inline: True
```
```
In fs/direct-io.c (ffffffff813c20b4)
Location: include/linux/mm.h:991
Inline: True
```
```
In fs/mpage.c (ffffffff813c4306)
Location: include/linux/mm.h:991
Inline: True
```
```
In fs/io_uring.c (ffffffff813df3ee)
Location: include/linux/mm.h:991
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/iomap/buffered-io.c (ffffffff814121df)
Location: include/linux/mm.h:991
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8145d276)
Location: include/linux/mm.h:991
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8146160f)
Location: include/linux/mm.h:991
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff8147c244)
Location: include/linux/mm.h:991
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81485276)
Location: include/linux/mm.h:991
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81486506)
Location: include/linux/mm.h:991
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff814db196)
Location: include/linux/mm.h:991
Inline: True
```
```
In fs/fuse/file.c (ffffffff814edf8b)
Location: include/linux/mm.h:991
Inline: True
```
```
In block/bio.c (ffffffff815c6c85)
Location: include/linux/mm.h:991
Inline: True
```
```
In lib/iov_iter.c (ffffffff81614f47)
Location: include/linux/mm.h:991
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff818a892b)
Location: include/linux/mm.h:991
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In net/xdp/xsk.c (ffffffff81c73498)
Location: include/linux/mm.h:991
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/truncate.c (ffffffff81307ca3)
Location: include/linux/mm.h:927
Inline: True
```
```
In mm/shmem.c (ffffffff81317679)
Location: include/linux/mm.h:927
Inline: True
```
```
In mm/madvise.c (ffffffff81375fdf)
Location: include/linux/mm.h:927
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/hugetlb.c (ffffffff81394745)
Location: include/linux/mm.h:927
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/mempolicy.c (ffffffff81398b88)
Location: include/linux/mm.h:927
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/migrate.c (ffffffff813b1787)
Location: include/linux/mm.h:927
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff813d8565)
Location: include/linux/mm.h:927
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff813dc122)
Location: include/linux/mm.h:927
Inline: True
Inline callers:
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/page_isolation.c (ffffffff813ddd20)
Location: include/linux/mm.h:927
Inline: True
```
```
In mm/secretmem.c (ffffffff813e36f0)
Location: include/linux/mm.h:927
Inline: True
```
```
In fs/libfs.c (ffffffff8142c52f)
Location: include/linux/mm.h:927
Inline: True
```
```
In fs/buffer.c (ffffffff8144322f)
Location: include/linux/mm.h:927
Inline: True
```
```
In fs/direct-io.c (ffffffff81448f83)
Location: include/linux/mm.h:927
Inline: True
```
```
In fs/mpage.c (ffffffff8144afa6)
Location: include/linux/mm.h:927
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8148813f)
Location: include/linux/mm.h:927
Inline: True
```
```
In fs/ext4/inline.c (ffffffff814dbdb6)
Location: include/linux/mm.h:927
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814e075f)
Location: include/linux/mm.h:927
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff814fe8d3)
Location: include/linux/mm.h:927
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815085c6)
Location: include/linux/mm.h:927
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81509996)
Location: include/linux/mm.h:927
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81554873)
Location: include/linux/mm.h:927
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff81568d56)
Location: include/linux/mm.h:927
Inline: True
```
```
In fs/fuse/file.c (ffffffff8157d67b)
Location: include/linux/mm.h:927
Inline: True
```
```
In block/bio.c (ffffffff81671bf3)
Location: include/linux/mm.h:927
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81e90a4f)
Location: include/linux/mm.h:927
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
  - io_uring/io_uring.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff816e1016)
Location: include/linux/mm.h:927
Inline: True
Inline callers:
  - lib/iov_iter.c:page_copy_sane
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f277d)
Location: include/linux/mm.h:927
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In net/xdp/xsk.c (ffffffff81e16005)
Location: include/linux/mm.h:927
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/truncate.c (ffffffff813713b3)
Location: include/linux/mm.h:1057
Inline: True
```
```
In mm/shmem.c (ffffffff8138a763)
Location: include/linux/mm.h:1057
Inline: True
```
```
In mm/madvise.c (ffffffff813f3856)
Location: include/linux/mm.h:1057
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/hugetlb.c (ffffffff814077da)
Location: include/linux/mm.h:1057
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/secretmem.c (ffffffff8146b0c0)
Location: include/linux/mm.h:1057
Inline: True
```
```
In fs/libfs.c (ffffffff814b9b5f)
Location: include/linux/mm.h:1057
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
  - fs/libfs.c:zero_user_segments
```
```
In fs/buffer.c (ffffffff814d256f)
Location: include/linux/mm.h:1057
Inline: True
Inline callers:
  - fs/buffer.c:zero_user_segments
  - fs/buffer.c:zero_user_segments
```
```
In fs/direct-io.c (ffffffff814d7273)
Location: include/linux/mm.h:1057
Inline: True
```
```
In fs/mpage.c (ffffffff814d97d6)
Location: include/linux/mm.h:1057
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8151bdbf)
Location: include/linux/mm.h:1057
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:zero_user_segments
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/ext4/inline.c (ffffffff81574d36)
Location: include/linux/mm.h:1057
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815799bf)
Location: include/linux/mm.h:1057
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/move_extent.c (ffffffff81599113)
Location: include/linux/mm.h:1057
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815a30b6)
Location: include/linux/mm.h:1057
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815a4606)
Location: include/linux/mm.h:1057
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6343)
Location: include/linux/mm.h:1057
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff8160c6c6)
Location: include/linux/mm.h:1057
Inline: True
```
```
In fs/fuse/file.c (ffffffff8162317b)
Location: include/linux/mm.h:1057
Inline: True
```
```
In block/bio.c (ffffffff8172d4b3)
Location: include/linux/mm.h:1057
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81789c13)
Location: include/linux/mm.h:1057
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
```
```
In io_uring/rsrc.c (ffffffff817a0b2f)
Location: include/linux/mm.h:1057
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff817d14c4)
Location: include/linux/mm.h:1057
Inline: True
Inline callers:
  - lib/iov_iter.c:page_copy_sane
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b70546)
Location: include/linux/mm.h:1057
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
```
```
In net/xdp/xsk.c (ffffffff81fed052)
Location: include/linux/mm.h:1057
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/truncate.c (ffffffff813a3584)
Location: include/linux/mm.h:1253
Inline: True
```
```
In mm/shmem.c (ffffffff813bcaf4)
Location: include/linux/mm.h:1253
Inline: True
```
```
In mm/madvise.c (ffffffff814293bb)
Location: include/linux/mm.h:1253
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In mm/hugetlb.c (ffffffff8143acaa)
Location: include/linux/mm.h:1253
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/secretmem.c (ffffffff8149ff81)
Location: include/linux/mm.h:1253
Inline: True
```
```
In fs/libfs.c (ffffffff814eeaff)
Location: include/linux/mm.h:1253
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
  - fs/libfs.c:zero_user_segments
```
```
In fs/buffer.c (ffffffff81508d1f)
Location: include/linux/mm.h:1253
Inline: True
Inline callers:
  - fs/buffer.c:zero_user_segments
  - fs/buffer.c:zero_user_segments
```
```
In fs/mpage.c (ffffffff8150d844)
Location: include/linux/mm.h:1253
Inline: True
```
```
In fs/direct-io.c (ffffffff81510324)
Location: include/linux/mm.h:1253
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff815540cf)
Location: include/linux/mm.h:1253
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:zero_user_segments
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/ext4/inline.c (ffffffff815acc14)
Location: include/linux/mm.h:1253
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815b094f)
Location: include/linux/mm.h:1253
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/move_extent.c (ffffffff815cfbf4)
Location: include/linux/mm.h:1253
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815d9aa4)
Location: include/linux/mm.h:1253
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815daf54)
Location: include/linux/mm.h:1253
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e4c4)
Location: include/linux/mm.h:1253
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff816445a6)
Location: include/linux/mm.h:1253
Inline: True
```
```
In fs/fuse/file.c (ffffffff8165b5e6)
Location: include/linux/mm.h:1253
Inline: True
```
```
In block/bio.c (ffffffff81769774)
Location: include/linux/mm.h:1253
Inline: True
```
```
In io_uring/io_uring.c (ffffffff817c9a0a)
Location: include/linux/mm.h:1253
Inline: True
```
```
In io_uring/rsrc.c (ffffffff817e1d7c)
Location: include/linux/mm.h:1253
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff8181406c)
Location: include/linux/mm.h:1253
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81bc3e4a)
Location: include/linux/mm.h:1253
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
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
In mm/truncate.c (ffffffff813cd133)
Location: include/linux/mm.h:1309
Inline: True
```
```
In mm/shmem.c (ffffffff813e7942)
Location: include/linux/mm.h:1309
Inline: True
```
```
In mm/madvise.c (ffffffff81462beb)
Location: include/linux/mm.h:1309
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
```
```
In mm/migrate.c (ffffffff81498c9c)
Location: include/linux/mm.h:1309
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In mm/secretmem.c (ffffffff814cf6d1)
Location: include/linux/mm.h:1309
Inline: True
```
```
In fs/libfs.c (ffffffff81522ae2)
Location: include/linux/mm.h:1309
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
  - fs/libfs.c:zero_user_segments
```
```
In fs/buffer.c (ffffffff8153da00)
Location: include/linux/mm.h:1309
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/buffer.c:decrypt_bh
  - fs/buffer.c:verify_bh
  - fs/buffer.c:zero_user_segments
  - fs/buffer.c:zero_user_segments
```
```
In fs/mpage.c (ffffffff81542563)
Location: include/linux/mm.h:1309
Inline: True
```
```
In fs/direct-io.c (ffffffff815447d3)
Location: include/linux/mm.h:1309
Inline: True
```
```
In fs/crypto/inline_crypt.c (ffffffff8156fc2b)
Location: include/linux/mm.h:1309
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:bh_get_inode_and_lblk_num
```
```
In fs/iomap/buffered-io.c (ffffffff8158a0b2)
Location: include/linux/mm.h:1309
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:zero_user_segments
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/ext4/inline.c (ffffffff815e5b41)
Location: include/linux/mm.h:1309
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815ed71a)
Location: include/linux/mm.h:1309
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:zero_user_segments
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/move_extent.c (ffffffff81608483)
Location: include/linux/mm.h:1309
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff816131e3)
Location: include/linux/mm.h:1309
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81613783)
Location: include/linux/mm.h:1309
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff8164c546)
Location: include/linux/mm.h:1309
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff816500de)
Location: include/linux/mm.h:1309
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/hugetlbfs/inode.c (ffffffff81667983)
Location: include/linux/mm.h:1309
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff8167dad6)
Location: include/linux/mm.h:1309
Inline: True
```
```
In fs/fuse/file.c (ffffffff816952c6)
Location: include/linux/mm.h:1309
Inline: True
```
```
In block/bio.c (ffffffff817ab993)
Location: include/linux/mm.h:1309
Inline: True
```
```
In io_uring/io_uring.c (ffffffff8180f59e)
Location: include/linux/mm.h:1309
Inline: True
```
```
In io_uring/rsrc.c (ffffffff81826122)
Location: include/linux/mm.h:1309
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In lib/iov_iter.c (ffffffff818584f7)
Location: include/linux/mm.h:1309
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_to_iter_nofault
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81c18669)
Location: include/linux/mm.h:1309
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
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
In arch/arm64/mm/flush.c (ffff8000100add20)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - arch/arm64/mm/flush.c:__sync_icache_dcache
```
```
In mm/gup.c (ffff8000102f0cf8)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffff8000103074c0)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffff800010309c68)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/page_alloc.c (ffff80001031a35c)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffff800010336278)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffff80001033a6b4)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffff800010343090)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/slub.c:__ksize
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffff800010351204)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffff80001036d920)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffff80001036def0)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffff800010372300)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/io_uring.c (ffff800010400374)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In lib/iov_iter.c (ffff80001062f2e8)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
```
```
In net/xdp/xsk.c (ffff800010d7dfa0)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In arch/arm/mm/flush.c (c031ebb8)
Location: include/linux/mm.h:810
Inline: True
```
```
In mm/rmap.c (c05264a0)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/slub.c (c0548808)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/slub.c:__ksize
  - mm/slub.c:allocate_slab
```
```
In fs/io_uring.c (c05d2704)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In lib/iov_iter.c (c07d5c84)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (c0e78b2c)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/gup.c (c0000000003b5890)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (c0000000003d5c28)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (c0000000003d9598)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/page_alloc.c (c0000000003ed470)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (c000000000410b3c)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (c000000000414ed8)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (c00000000042069c)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/slub.c:__ksize
  - mm/slub.c:allocate_slab
```
```
In mm/memory_hotplug.c (c00000000042db9c)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (c000000000437510)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (c00000000045da98)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (c00000000045ef0c)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (c000000000463c3c)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/io_uring.c (c000000000509a8c)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In lib/iov_iter.c (c0000000007d7010)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (c000000000ebdb5c)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/gup.c (ffffffe0002043e2)
Location: include/linux/mm.h:810
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffe00021276e)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffe000213c24)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/page_alloc.c (ffffffe00021fcbe)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffe0002322b0)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/slub.c (ffffffe000236c6e)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/slub.c:__ksize
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffe00023fb28)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a5e0)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/page_isolation.c (ffffffe00024b556)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/io_uring.c (ffffffe0002acad0)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In lib/iov_iter.c (ffffffe00045e7c2)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
```
```
In net/xdp/xsk.c (ffffffe0008ab786)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/gup.c (ffffffff81251204)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff81269e70)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126c5c9)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/page_alloc.c (ffffffff8127a267)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff812903f5)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff81293d01)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff8129c109)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/slub.c:__ksize
  - mm/slub.c:allocate_slab
```
```
In mm/memory_hotplug.c (ffffffff812a47ba)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812a9301)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff812c25d5)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812c2db6)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812c6397)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/io_uring.c (ffffffff81339831)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In lib/iov_iter.c (ffffffff8151d557)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (ffffffff81a4ac57)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/gup.c (ffffffff812440f4)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff8125c103)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8125e639)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/page_alloc.c (ffffffff8126c157)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff81282085)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff81285911)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff8128dcc9)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/slub.c:__ksize
  - mm/slub.c:allocate_slab
```
```
In mm/memory_hotplug.c (ffffffff8129628a)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8129ac61)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff812b3625)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812b3e06)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812b73d7)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/io_uring.c (ffffffff8132a561)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In lib/iov_iter.c (ffffffff8150d847)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (ffffffff81a07847)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/gup.c (ffffffff8124efa4)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff81267c10)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126a369)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/page_alloc.c (ffffffff81278007)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff8128e205)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff81291b11)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff81299f19)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/slub.c:__ksize
  - mm/slub.c:allocate_slab
```
```
In mm/memory_hotplug.c (ffffffff812a25ca)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812a7111)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff812c03e5)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812c0bc6)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812c41a7)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/io_uring.c (ffffffff81337301)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In lib/iov_iter.c (ffffffff815195e7)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (ffffffff81ab6b07)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
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
In mm/gup.c (ffffffff8125e914)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/page_vma_mapped.c (ffffffff812775a6)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81279cd9)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/page_alloc.c (ffffffff81287bf7)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff8129dfa5)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (ffffffff812a1921)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/mempolicy.c:new_page
```
```
In mm/slub.c (ffffffff812a9d59)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/slub.c:__ksize
  - mm/slub.c:allocate_slab
```
```
In mm/memory_hotplug.c (ffffffff812b292a)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff812b7421)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0e75)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_migrate
```
```
In mm/memory-failure.c (ffffffff812d1686)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812d4c67)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/io_uring.c (ffffffff8134a3c1)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
```
```
In lib/iov_iter.c (ffffffff81532de7)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
```
```
In net/xdp/xsk.c (ffffffff81ac2c47)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
</details>
</li>
</ul>

## Differences
