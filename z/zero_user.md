# Function: <code>zero_user</code>

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
In fs/libfs.c (ffffffff81234b60)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff81244469)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
```
```
In fs/direct-io.c (ffffffff8124a4a0)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/ext4/inode.c (ffffffff8129929e)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/move_extent.c (ffffffff812d682e)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813043bd)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
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
In fs/libfs.c (ffffffff8125d05e)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff8126cea0)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffffffff81272e6e)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff8129c6a5)
Location: include/linux/highmem.h:217
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812c649d)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/move_extent.c (ffffffff813064cc)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81338442)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
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
In fs/libfs.c (ffffffff812705a4)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff81280130)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffffffff81286980)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff812b13c5)
Location: include/linux/highmem.h:217
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812dbd49)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff8131c48c)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e20f)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
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
In fs/libfs.c (ffffffff8127dcb3)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff8128da30)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffffffff81294012)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff812be879)
Location: include/linux/highmem.h:217
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8130058d)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff81315037)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81362de1)
Location: include/linux/highmem.h:217
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
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
In fs/libfs.c (ffffffff812a0790)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff812b05ea)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffffffff812b6f75)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff812e22f9)
Location: include/linux/highmem.h:218
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81324db0)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff81339dd2)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ecryptfs/mmap.c (ffffffff81387a4e)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
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
In fs/libfs.c (ffffffff812c6d03)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff812d83d8)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffffffff812e0025)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff8130ec55)
Location: include/linux/highmem.h:218
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8135300e)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff81368326)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813b675f)
Location: include/linux/highmem.h:218
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
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
In fs/libfs.c (ffffffff812dbed3)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff812ed8a8)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffffffff812f4b51)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff81324820)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/iomap.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff8136b13b)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff813807a9)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ecryptfs/mmap.c (ffffffff813cfcaf)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
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
In fs/libfs.c (ffffffff812fa57a)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff8130f065)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffffffff81315f0b)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (ffffffff8134ba49)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff81394679)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff813a95da)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (ffffffff813fa89a)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
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
In fs/libfs.c (ffffffff8130c2fa)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff81323bef)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffffffff81328d8b)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (ffffffff81363d19)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff813acff9)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff813c24fa)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (ffffffff8141476a)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffffffff814dfa2a)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In fs/libfs.c (ffffffff813457e0)
Location: include/linux/highmem.h:311
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff8135d2af)
Location: include/linux/highmem.h:311
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:page_zero_new_buffers
```
```
In fs/direct-io.c (ffffffff81362e36)
Location: include/linux/highmem.h:311
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (ffffffff813aae9d)
Location: include/linux/highmem.h:311
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff813f9326)
Location: include/linux/highmem.h:311
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff8140ec0f)
Location: include/linux/highmem.h:311
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (ffffffff81462a9c)
Location: include/linux/highmem.h:311
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffffffff8153e93f)
Location: include/linux/highmem.h:311
Inline: True
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
In fs/libfs.c (ffffffff81351f16)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff8136a794)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:page_zero_new_buffers
```
```
In fs/direct-io.c (ffffffff8136ffe1)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (ffffffff813bcd24)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff8140b8ee)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff81422134)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e544)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffffffff8155aab8)
Location: include/linux/highmem.h:242
Inline: True
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
In fs/libfs.c (ffffffff81358c39)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff8137130b)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:page_zero_new_buffers
```
```
In fs/direct-io.c (ffffffff8137688a)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (ffffffff813c3e49)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff81411aaf)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff814287f8)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (ffffffff81484018)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffffffff815630bf)
Location: include/linux/highmem.h:242
Inline: True
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
In fs/libfs.c (ffffffff813a7326)
Location: include/linux/highmem.h:228
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff813bfc1c)
Location: include/linux/highmem.h:228
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffffffff813c2c35)
Location: include/linux/highmem.h:228
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (ffffffff81414887)
Location: include/linux/highmem.h:228
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_zero_range
  - fs/iomap/buffered-io.c:iomap_readpage_iter
```
```
In fs/ext4/inode.c (ffffffff81464972)
Location: include/linux/highmem.h:228
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff8147c555)
Location: include/linux/highmem.h:228
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (ffffffff814db636)
Location: include/linux/highmem.h:228
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffffffff815c6c5c)
Location: include/linux/highmem.h:228
Inline: True
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
In fs/libfs.c (ffffffff8142c88a)
Location: include/linux/highmem.h:299
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff814468b2)
Location: include/linux/highmem.h:299
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
```
```
In fs/direct-io.c (ffffffff81449b05)
Location: include/linux/highmem.h:299
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/ext4/inode.c (ffffffff814e4046)
Location: include/linux/highmem.h:299
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff814fed07)
Location: include/linux/highmem.h:299
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (ffffffff815692d5)
Location: include/linux/highmem.h:299
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffffffff816735b5)
Location: include/linux/highmem.h:299
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
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
In fs/libfs.c (ffffffff814ba0fa)
Location: include/linux/highmem.h:299
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff814d59bf)
Location: include/linux/highmem.h:299
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
```
```
In fs/direct-io.c (ffffffff814d83de)
Location: include/linux/highmem.h:299
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/ext4/inode.c (ffffffff8157d4af)
Location: include/linux/highmem.h:299
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff81599556)
Location: include/linux/highmem.h:299
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (ffffffff8160cd92)
Location: include/linux/highmem.h:299
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffffffff8172f160)
Location: include/linux/highmem.h:299
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
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
In fs/libfs.c (ffffffff814ef095)
Location: include/linux/highmem.h:295
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff815093b1)
Location: include/linux/highmem.h:295
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
```
```
In fs/direct-io.c (ffffffff815111aa)
Location: include/linux/highmem.h:295
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/ecryptfs/mmap.c (ffffffff81644b99)
Location: include/linux/highmem.h:295
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffffffff8176b3bf)
Location: include/linux/highmem.h:295
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
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
In fs/buffer.c (ffffffff8153e2d1)
Location: include/linux/highmem.h:295
Inline: True
Inline callers:
  - fs/buffer.c:cont_expand_zero
  - fs/buffer.c:cont_expand_zero
```
```
In fs/direct-io.c (ffffffff8154564a)
Location: include/linux/highmem.h:295
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e0c6)
Location: include/linux/highmem.h:295
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffffffff817ad84f)
Location: include/linux/highmem.h:295
Inline: True
Inline callers:
  - block/bio.c:guard_bio_eod
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
In fs/libfs.c (ffff8000103c0b04)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffff8000103dcf80)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffff8000103e42a4)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (ffff80001042c0d8)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffff8000104818a8)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffff800010499f2c)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (ffff8000104f5e20)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffff8000105dc598)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In fs/libfs.c (c059e018)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (c05b64a0)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (c05bc1ec)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (c05f3a00)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (c064294c)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (c065b6f0)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (c06b369c)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (c0789a04)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In fs/libfs.c (c0000000004bf2b0)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (c0000000004e264c)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (c0000000004ea388)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (c00000000053b3a4)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (c0000000005a5e94)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (c0000000005c424c)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (c000000000636bc0)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (c00000000076d63c)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In fs/libfs.c (ffffffe0002810a6)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffe000295132)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffffffe000299d3c)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8316)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffe00030a478)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffe00031d59e)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (ffffffe000364c48)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffffffe00041f906)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In fs/libfs.c (ffffffff813048da)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff8131c1cf)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffffffff8132136b)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (ffffffff8135c2f9)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff813a55d9)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff813baada)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (ffffffff8140cd4a)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffffffff814d800a)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In fs/libfs.c (ffffffff812f54fa)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff8130cd6f)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffffffff81311f0b)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (ffffffff8134cf99)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff81396069)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff813ab56a)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (ffffffff813fd7ca)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffffffff814c89ba)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In fs/libfs.c (ffffffff813026ca)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff81319c9f)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffffffff8131ee3b)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (ffffffff81359dc9)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff813a2e39)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff813b833a)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a0ca)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffffffff814d409a)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
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
In fs/libfs.c (ffffffff81313cea)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/buffer.c (ffffffff8132b95f)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/direct-io.c (ffffffff81330b3b)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/iomap/buffered-io.c (ffffffff8136d4d9)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/ext4/inode.c (ffffffff813b7505)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
```
```
In fs/ext4/move_extent.c (ffffffff813cd03a)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ecryptfs/mmap.c (ffffffff8141fdb3)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In block/bio.c (ffffffff814ecc2a)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - block/bio.c:bio_truncate
```
</details>
</li>
</ul>

## Differences
