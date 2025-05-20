# Function: <code>mapping_gfp_mask</code>

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
In kernel/sched/fair.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In mm/shmem.c (ffffffff811ab70a)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In fs/splice.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In drivers/block/loop.c (ffffffff8156fa23)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_switch
  - drivers/block/loop.c:lo_ioctl
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
In kernel/sched/fair.c (ffffffff810b5164)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/events/uprobes.c (ffffffff81199a91)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In mm/filemap.c (ffffffff811a1340)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/readahead.c (ffffffff811b0ff6)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In mm/shmem.c (ffffffff811c3104)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff811d6f4a)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_page_mkwrite
```
```
In mm/mempolicy.c (ffffffff811ffd6f)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
```
```
In mm/migrate.c (ffffffff81212a33)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - mm/migrate.c:SyS_move_pages
```
```
In fs/namei.c (ffffffff8123db25)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
```
```
In fs/splice.c (ffffffff81266fcd)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:__generic_file_splice_read
```
```
In fs/buffer.c (ffffffff8126e8e1)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
```
```
In fs/mpage.c (ffffffff81277014)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
```
```
In fs/dax.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:67
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81312e2f)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffff8132248d)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff81324ded)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/dev.c (ffffffff81343e98)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In drivers/block/loop.c (ffffffff815c5866)
Location: include/linux/pagemap.h:67
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_switch
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
In kernel/sched/fair.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/pagemap.h:78
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/pagemap.h:78
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/pagemap.h:97
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/pagemap.h:97
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/pagemap.h:100
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/pagemap.h:100
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/iomap.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/pagemap.h:100
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/pagemap.h:100
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/pagemap.h:100
Inline: True
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
In kernel/events/uprobes.c (ffffffff81246207)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - kernel/events/uprobes.c:copy_insn
```
```
In mm/filemap.c (ffffffff812537cc)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/readahead.c (ffffffff8125ce34)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_readahead_unbounded
  - mm/readahead.c:read_cache_pages
```
```
In mm/shmem.c (ffffffff8126f7ea)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff8129469b)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mempolicy.c (ffffffff812ce76e)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In fs/namei.c (ffffffff813216f5)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/buffer.c (ffffffff8135d1e2)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:grow_dev_page
```
```
In fs/mpage.c (ffffffff81364d65)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/dax.c (ffffffff8138e3ca)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In fs/iomap/buffered-io.c (ffffffff813ab00d)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff813f9132)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/squashfs/file.c (ffffffff8144b61c)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8144dbe8)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/dev.c (ffffffff81470da5)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff8147fd45)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/block/loop.c (ffffffff817e9a31)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8182ca83)
Location: include/linux/pagemap.h:101
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066026)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
```
```
In kernel/events/uprobes.c (ffffffff81250877)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - kernel/events/uprobes.c:copy_insn
```
```
In mm/filemap.c (ffffffff8125e44c)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:generic_file_buffered_read_get_pages
```
```
In mm/readahead.c (ffffffff812671a6)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_cache_pages
```
```
In mm/shmem.c (ffffffff8127ab5a)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff8129ef1b)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mempolicy.c (ffffffff812da0ae)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In fs/namei.c (ffffffff8132cc95)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/buffer.c (ffffffff8136a6d2)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:grow_dev_page
```
```
In fs/mpage.c (ffffffff81371ce5)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/dax.c (ffffffff8139fb1a)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In fs/iomap/buffered-io.c (ffffffff813bcdec)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff8140b7e5)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/squashfs/file.c (ffffffff81467cfc)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8146a1a8)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/dev.c (ffffffff8148b668)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff8149b425)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/block/loop.c (ffffffff817fe52d)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dma-buf/udmabuf.c (ffffffff8183dbb4)
Location: include/linux/pagemap.h:103
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066492)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
```
```
In kernel/events/uprobes.c (ffffffff81255d8e)
Location: include/linux/pagemap.h:108
Inline: True
```
```
In mm/filemap.c (ffffffff812609ac)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
```
```
In mm/readahead.c (ffffffff8126b959)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_cache_pages
```
```
In mm/shmem.c (ffffffff8127fccc)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff812a3f68)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mempolicy.c (ffffffff812e190e)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In fs/namei.c (ffffffff81332855)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/buffer.c (ffffffff81371239)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:grow_dev_page
```
```
In fs/mpage.c (ffffffff81377e11)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/dax.c (ffffffff813a70a0)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In fs/iomap/buffered-io.c (ffffffff813c3f34)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff81411995)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/squashfs/file.c (ffffffff8146d2fe)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8146f781)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/dev.c (ffffffff8149063b)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff814a0635)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/block/loop.c (ffffffff817e3121)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81820d44)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810705b1)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
```
```
In kernel/events/uprobes.c (ffffffff81291a41)
Location: include/linux/pagemap.h:108
Inline: True
```
```
In mm/filemap.c (ffffffff8129d39c)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
```
```
In mm/readahead.c (ffffffff812a8629)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
  - mm/readahead.c:read_cache_pages
```
```
In mm/shmem.c (ffffffff812bdfdc)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff812e5288)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mempolicy.c (ffffffff813289de)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In fs/namei.c (ffffffff8137ffe5)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/buffer.c (ffffffff813bfb54)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:grow_dev_page
```
```
In fs/mpage.c (ffffffff813c44fd)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/dax.c (ffffffff813f6f63)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In fs/iomap/buffered-io.c (ffffffff814133c3)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inode.c (ffffffff81464845)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/squashfs/file.c (ffffffff814c3b85)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff814c61eb)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/dev.c (ffffffff814e80cb)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff814f8503)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/block/loop.c (ffffffff8186e2ef)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818ab685)
Location: include/linux/pagemap.h:108
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107db01)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_get_backing
```
```
In kernel/events/uprobes.c (ffffffff812e71a3)
Location: include/linux/pagemap.h:272
Inline: True
```
```
In mm/filemap.c (ffffffff812f43e5)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:read_cache_folio
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
```
```
In mm/folio-compat.c (ffffffff81300aa5)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/folio-compat.c:grab_cache_page_write_begin
```
```
In mm/readahead.c (ffffffff813018f9)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/shmem.c (ffffffff8131a883)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/memory.c (ffffffff8134755f)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mempolicy.c (ffffffff81397c3b)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/huge_memory.c (ffffffff813bf690)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/namei.c (ffffffff81400092)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/buffer.c (ffffffff814467e5)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:grow_dev_page
```
```
In fs/mpage.c (ffffffff8144b2ca)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/dax.c (ffffffff814693e0)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In fs/iomap/buffered-io.c (ffffffff8148b1eb)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inode.c (ffffffff814e3e5d)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/squashfs/file.c (ffffffff8154e7c1)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff815511a9)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/dev.c (ffffffff815770a0)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff815889b3)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/block/loop.c (ffffffff819b7b21)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5e18)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f097)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
```
```
In kernel/events/uprobes.c (ffffffff81350ca3)
Location: include/linux/pagemap.h:272
Inline: True
```
```
In mm/filemap.c (ffffffff8135e505)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:read_cache_folio
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
```
```
In mm/folio-compat.c (ffffffff8136b365)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/folio-compat.c:grab_cache_page_write_begin
```
```
In mm/readahead.c (ffffffff8136bfc9)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/shmem.c (ffffffff8138d9a3)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff813bf95c)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mempolicy.c (ffffffff81417848)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/huge_memory.c (ffffffff81441bc7)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/namei.c (ffffffff8148a0e2)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/buffer.c (ffffffff814d58f5)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:grow_dev_page
```
```
In fs/mpage.c (ffffffff814d9a0a)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/dax.c (ffffffff814f9e70)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In fs/iomap/buffered-io.c (ffffffff8151f215)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inode.c (ffffffff8157d38d)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/squashfs/file.c (ffffffff815ef281)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff815f2301)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/dev.c (ffffffff8161b780)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff8162ee73)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/block/loop.c (ffffffff81b2ce61)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b733e2)
Location: include/linux/pagemap.h:272
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81091f97)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
```
```
In kernel/events/uprobes.c (ffffffff81381f02)
Location: include/linux/pagemap.h:276
Inline: True
```
```
In mm/filemap.c (ffffffff813912a5)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:read_cache_folio
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
```
```
In mm/folio-compat.c (ffffffff8139d4e5)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - mm/folio-compat.c:grab_cache_page_write_begin
```
```
In mm/readahead.c (ffffffff8139e249)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/shmem.c (ffffffff813c1b33)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_get_partial_folio
```
```
In mm/memory.c (ffffffff813f461f)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/madvise.c (ffffffff81427562)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/mempolicy.c (ffffffff8144adde)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/huge_memory.c (ffffffff8147756e)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/namei.c (ffffffff814befbf)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/buffer.c (ffffffff8150c16d)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__getblk_slow
```
```
In fs/mpage.c (ffffffff8150d971)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/dax.c (ffffffff815312ea)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In fs/iomap/buffered-io.c (ffffffff8155742c)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inline.c (ffffffff815adfc2)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815b473d)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff815d019e)
Location: include/linux/pagemap.h:276
Inline: True
```
```
In fs/squashfs/file.c (ffffffff81627261)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8162a3f1)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/dev.c (ffffffff816538f0)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff816670d6)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/block/loop.c (ffffffff81b7d089)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81bc6d2a)
Location: include/linux/pagemap.h:276
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099307)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_get_backing
```
```
In kernel/events/uprobes.c (ffffffff813ab2e2)
Location: include/linux/pagemap.h:326
Inline: True
```
```
In mm/filemap.c (ffffffff813bb045)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:read_cache_folio
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
```
```
In mm/folio-compat.c (ffffffff813c7245)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - mm/folio-compat.c:grab_cache_page_write_begin
```
```
In mm/readahead.c (ffffffff813c7ee9)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
```
In mm/shmem.c (ffffffff813ec8b3)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_get_partial_folio
```
```
In mm/memory.c (ffffffff81420c1f)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/madvise.c (ffffffff81460c46)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/mempolicy.c (ffffffff8148481e)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/huge_memory.c (ffffffff814a6cde)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/namei.c (ffffffff814f165f)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/libfs.c (ffffffff81523055)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff81540d6d)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__bread_gfp
```
```
In fs/mpage.c (ffffffff81542658)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/dax.c (ffffffff815661ca)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In fs/iomap/buffered-io.c (ffffffff81589e01)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_get_folio
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/balloc.c (ffffffff815c8874)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff815ce1d9)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff815df044)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815e1e4a)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff815e57f9)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815ec0a9)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff816074ea)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff81608a22)
Location: include/linux/pagemap.h:326
Inline: True
```
```
In fs/ext4/resize.c (ffffffff8161755a)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff81639f13)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (ffffffff81641fd6)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/jbd2/recovery.c (ffffffff8165264d)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8165ab21)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_load_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
```
```
In fs/squashfs/file.c (ffffffff816603c1)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffff8166371b)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fat/dir.c (ffffffff8166d827)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8166f18a)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
```
In fs/fuse/dev.c (ffffffff8168cf00)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff816a1426)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/block/loop.c (ffffffff81bd1014)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b899)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9bf51)
Location: include/linux/pagemap.h:326
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
  - drivers/gpu/drm/drm_gem.c:drm_gem_get_pages
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
In kernel/sched/fair.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/pagemap.h:100
Inline: True
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
In kernel/events/uprobes.c (c04d5464)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/filemap.c (c04de6a8)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/readahead.c (c04eaf98)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In mm/shmem.c (c04fda8c)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (c051bd34)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In fs/namei.c (c05799a4)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/buffer.c (c05b63a0)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_slow
```
```
In fs/mpage.c (c05bec20)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/iomap/buffered-io.c (c05f38ac)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (c0642808)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/readpage.c (c06665e0)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (c069d43c)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (c069fd18)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/dev.c (c06c1280)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In fs/fuse/readdir.c (c06cf560)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In drivers/block/loop.c (c0a08370)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/udmabuf.c (c0a420d8)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In kernel/sched/fair.c (c000000000192988)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/events/uprobes.c (c000000000358940)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uprobe
```
```
In mm/filemap.c (c0000000003694e0)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/readahead.c (c000000000378194)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In mm/shmem.c (c0000000003957c4)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (c0000000003c3a88)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mempolicy.c (c000000000414898)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_test_walk
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c000000000438a10)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In fs/namei.c (c00000000048adb0)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/buffer.c (c0000000004e2548)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (c0000000004ed3c0)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/dax.c (c000000000515ac8)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In fs/iomap/buffered-io.c (c00000000053b248)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (c0000000005a5d20)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/readpage.c (c0000000005d1b08)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (c000000000616dfc)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (c000000000619dc4)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/dev.c (c000000000649d80)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In fs/fuse/readdir.c (c00000000065ce30)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In drivers/block/loop.c (c0000000009c8dc0)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/udmabuf.c (c000000000a25398)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In mm/filemap.c (ffffffe0001d73a2)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/readahead.c (ffffffe0001e16a4)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
  - mm/readahead.c:read_cache_pages
```
```
In mm/shmem.c (ffffffe0001f1368)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffe000209870)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In fs/namei.c (ffffffe0002615ec)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/namei.c:page_symlink
  - fs/namei.c:page_get_link
```
```
In fs/buffer.c (ffffffe00029508e)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/mpage.c (ffffffe00029c042)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/dax.c (ffffffe0002b38f2)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffe0002c821c)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffe00030a2e8)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/readpage.c (ffffffe000325b60)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/squashfs/file.c (ffffffe000350904)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffe000352aee)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/fuse/dev.c (ffffffe0003716d4)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In fs/fuse/readdir.c (ffffffe00037e400)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In drivers/block/loop.c (ffffffe0005a1d4c)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/udmabuf.c (ffffffe0005d73f2)
Location: include/linux/pagemap.h:100
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In kernel/sched/fair.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/pagemap.h:100
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/pagemap.h:100
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/pagemap.h:100
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/buffer.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/mpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/ext4/readpage.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/linux/pagemap.h:100
Inline: True
```
</details>
</li>
</ul>

## Differences
