# Function: <code>pagecache_get_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118dfb0)
Location: mm/filemap.c:1132
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:free_swap_and_cache
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:__generic_file_splice_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/aio.c:SyS_io_setup
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff8118dfb0-ffffffff8118e16d: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a1090)
Location: mm/filemap.c:1183
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:__generic_file_splice_read
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__find_get_block_slow
  - fs/aio.c:aio_setup_ring
  - fs/dax.c:dax_fault
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff811a1090-ffffffff811a1327: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b0c90)
Location: mm/filemap.c:1285
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
  - fs/aio.c:aio_setup_ring
  - fs/dax.c:dax_iomap_fault
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff811b0c90-ffffffff811b0f27: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b81c0)
Location: mm/filemap.c:1413
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff811b81c0-ffffffff811b83c3: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cc8b0)
Location: mm/filemap.c:1535
Inline: False
Direct callers:
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:generic_file_read_iter
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff811cc8b0-ffffffff811ccb49: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ed990)
Location: mm/filemap.c:1535
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff811ed990-ffffffff811edc47: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fef40)
Location: mm/filemap.c:1573
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff811fef40-ffffffff811ff1f7: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81215f50)
Location: mm/filemap.c:1626
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff81215f50-ffffffff8121623c: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81223850)
Location: mm/filemap.c:1629
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff81223850-ffffffff81223b4b: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int index, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81251d60)
Location: mm/filemap.c:1600
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
  - fs/aio.c:aio_setup_ring
  - fs/verity/enable.c:read_file_data_page
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_get_buddy_page_lock
  - fs/ext4/mballoc.c:ext4_mb_get_buddy_page_lock
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
**Symbols:**

```
ffffffff81251d60-ffffffff812520d2: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int index, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125d380)
Location: mm/filemap.c:1792
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
  - fs/aio.c:aio_setup_ring
  - fs/verity/enable.c:read_file_data_page
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_get_buddy_page_lock
  - fs/ext4/mballoc.c:ext4_mb_get_buddy_page_lock
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
**Symbols:**

```
ffffffff8125d380-ffffffff8125d728: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int index, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125ffe0)
Location: mm/filemap.c:1833
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
  - fs/aio.c:aio_setup_ring
  - fs/verity/enable.c:read_file_data_page
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff8125ffe0-ffffffff812604f7: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int index, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:1888
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/secretmem.c:secretmem_fault
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
  - fs/aio.c:aio_setup_ring
  - fs/verity/enable.c:read_file_data_page
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - lib/buildid.c:build_id_parse
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81cb9f30-ffffffff81cb9f79: pagecache_get_page.cold (STB_LOCAL)
ffffffff8129c960-ffffffff8129cee5: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int index, int fgp_flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81300a00)
Location: mm/folio-compat.c:121
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/folio-compat.c:grab_cache_page_write_begin
  - mm/truncate.c:pagecache_isize_extended
  - mm/shmem.c:shmem_get_link
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/secretmem.c:secretmem_fault
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - lib/buildid.c:build_id_parse
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81300a00-ffffffff81300a97: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int index, int fgp_flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8136b2e0)
Location: mm/folio-compat.c:93
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/folio-compat.c:grab_cache_page_write_begin
  - mm/truncate.c:pagecache_isize_extended
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/secretmem.c:secretmem_fault
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:__find_get_block_slow
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff8136b2e0-ffffffff8136b34f: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int index, int fgp_flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8139d460)
Location: mm/folio-compat.c:94
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/folio-compat.c:grab_cache_page_write_begin
  - mm/truncate.c:pagecache_isize_extended
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/secretmem.c:secretmem_fault
  - fs/namei.c:page_get_link
  - fs/aio.c:aio_setup_ring
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff8139d460-ffffffff8139d4ce: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int index, fgf_t fgp_flags, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813c71d0)
Location: mm/folio-compat.c:88
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/folio-compat.c:grab_cache_page_write_begin
  - mm/truncate.c:pagecache_isize_extended
  - mm/khugepaged.c:collapse_file
  - mm/secretmem.c:secretmem_fault
  - fs/namei.c:page_get_link
  - fs/aio.c:aio_setup_ring
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/block.c:squashfs_bio_read
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
  - lib/buildid.c:build_id_parse
```
**Symbols:**

```
ffffffff813c71d0-ffffffff813c7229: pagecache_get_page (STB_GLOBAL)
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
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b1250)
Location: mm/filemap.c:1629
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffff8000102b1250-ffff8000102b1574: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04ddb58)
Location: mm/filemap.c:1629
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_slow
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_retrieve
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
c04ddb58-c04dded8: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000366880)
Location: mm/filemap.c:1629
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
c000000000366880-c000000000366d5c: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d6a54)
Location: mm/filemap.c:1629
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:__try_to_reclaim_swap
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffe0001d6a54-ffffffe0001d6ca4: pagecache_get_page (STB_GLOBAL)
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
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121bea0)
Location: mm/filemap.c:1629
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff8121bea0-ffffffff8121c19b: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120f090)
Location: mm/filemap.c:1629
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff8120f090-ffffffff8120f38b: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219c40)
Location: mm/filemap.c:1629
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff81219c40-ffffffff81219f3b: pagecache_get_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *pagecache_get_page(struct address_space *mapping, long unsigned int offset, int fgp_flags, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81228d40)
Location: mm/filemap.c:1629
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:grab_cache_page_write_begin
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/mincore.c:mincore_page
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:try_to_unuse
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/khugepaged.c:collapse_file
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - fs/namei.c:page_get_link
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
  - fs/aio.c:aio_setup_ring
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/squashfs/file.c:squashfs_copy_cache
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff81228d40-ffffffff81229023: pagecache_get_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int index</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int offset</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int fgp_flags</code> ➡️ <code>fgf_t fgp_flags</code>
</li>
</ul>
</details>
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
