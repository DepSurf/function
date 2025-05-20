# Function: <code>find_or_create_page</code>

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
In fs/splice.c (ffffffff8123ee19)
Location: include/linux/pagemap.h:324
Inline: True
Inline callers:
  - fs/splice.c:__generic_file_splice_read
```
```
In fs/buffer.c (ffffffff81243c64)
Location: include/linux/pagemap.h:324
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
```
```
In fs/aio.c (ffffffff8125ccaa)
Location: include/linux/pagemap.h:324
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_setup
```
```
In fs/dax.c (ffffffff8125e338)
Location: include/linux/pagemap.h:324
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
```
```
In fs/ext4/inode.c (ffffffff812991a2)
Location: include/linux/pagemap.h:324
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff812cf487)
Location: include/linux/pagemap.h:324
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
```
```
In fs/fuse/dev.c (ffffffff8130f5c3)
Location: include/linux/pagemap.h:324
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/splice.c (ffffffff81266fd1)
Location: include/linux/pagemap.h:296
Inline: True
Inline callers:
  - fs/splice.c:__generic_file_splice_read
```
```
In fs/buffer.c (ffffffff8126e8d3)
Location: include/linux/pagemap.h:296
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
```
```
In fs/aio.c (ffffffff81284d97)
Location: include/linux/pagemap.h:296
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff8128823a)
Location: include/linux/pagemap.h:296
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
```
```
In fs/ext4/inode.c (ffffffff812c6399)
Location: include/linux/pagemap.h:296
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff812ff2fc)
Location: include/linux/pagemap.h:296
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff81343e9c)
Location: include/linux/pagemap.h:296
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
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
In fs/buffer.c (ffffffff81281af3)
Location: include/linux/pagemap.h:306
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/aio.c (ffffffff81298fa3)
Location: include/linux/pagemap.h:306
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff8129c616)
Location: include/linux/pagemap.h:306
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/ext4/inode.c (ffffffff812dbbf9)
Location: include/linux/pagemap.h:306
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff8131537c)
Location: include/linux/pagemap.h:306
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff81359703)
Location: include/linux/pagemap.h:306
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/buffer.c (ffffffff8128f2ad)
Location: include/linux/pagemap.h:322
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/aio.c (ffffffff812a668a)
Location: include/linux/pagemap.h:322
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff81300488)
Location: include/linux/pagemap.h:322
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff8130c8a5)
Location: include/linux/pagemap.h:322
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff8136df31)
Location: include/linux/pagemap.h:322
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/buffer.c (ffffffff812b1eb3)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/aio.c (ffffffff812c9bbd)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff81324cab)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff8133146d)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff81392b07)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/buffer.c (ffffffff812d9e11)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/aio.c (ffffffff812f2ed9)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff81352f01)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff8135f9f5)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff813c2bc2)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
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
In fs/buffer.c (ffffffff812ef2ff)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/aio.c (ffffffff81307bfc)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff8136b02e)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff81377e82)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff813dc1f1)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In fs/fuse/readdir.c (ffffffff813e9ead)
Location: include/linux/pagemap.h:319
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In fs/buffer.c (ffffffff81310b4f)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/aio.c (ffffffff8132c3cb)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff81394543)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff813a1319)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff8140701b)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In fs/fuse/readdir.c (ffffffff81416034)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In fs/buffer.c (ffffffff81323b2f)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/aio.c (ffffffff8133f21b)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff813acec3)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff813ba19c)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff81421dfb)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In fs/fuse/readdir.c (ffffffff8142ff18)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In fs/buffer.c (ffffffff8135d1e2)
Location: include/linux/pagemap.h:345
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:grow_dev_page
```
```
In fs/aio.c (ffffffff8137782b)
Location: include/linux/pagemap.h:345
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff813f9132)
Location: include/linux/pagemap.h:345
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff81405df2)
Location: include/linux/pagemap.h:345
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_get_buddy_page_lock
  - fs/ext4/mballoc.c:ext4_mb_get_buddy_page_lock
```
```
In fs/fuse/dev.c (ffffffff81470da5)
Location: include/linux/pagemap.h:345
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff8147fd45)
Location: include/linux/pagemap.h:345
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In fs/buffer.c (ffffffff8136a6d2)
Location: include/linux/pagemap.h:401
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:grow_dev_page
```
```
In fs/aio.c (ffffffff81385188)
Location: include/linux/pagemap.h:401
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff8140b7e5)
Location: include/linux/pagemap.h:401
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff814190a1)
Location: include/linux/pagemap.h:401
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_get_buddy_page_lock
  - fs/ext4/mballoc.c:ext4_mb_get_buddy_page_lock
```
```
In fs/fuse/dev.c (ffffffff8148b668)
Location: include/linux/pagemap.h:401
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff8149b425)
Location: include/linux/pagemap.h:401
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In fs/buffer.c (ffffffff81371239)
Location: include/linux/pagemap.h:417
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:grow_dev_page
```
```
In fs/aio.c (ffffffff8138bf38)
Location: include/linux/pagemap.h:417
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff81411995)
Location: include/linux/pagemap.h:417
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff8141f932)
Location: include/linux/pagemap.h:417
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff8149063b)
Location: include/linux/pagemap.h:417
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff814a0635)
Location: include/linux/pagemap.h:417
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In fs/buffer.c (ffffffff813bfb54)
Location: include/linux/pagemap.h:417
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:grow_dev_page
```
```
In fs/aio.c (ffffffff813d94eb)
Location: include/linux/pagemap.h:417
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff81464845)
Location: include/linux/pagemap.h:417
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff81473028)
Location: include/linux/pagemap.h:417
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff814e80cb)
Location: include/linux/pagemap.h:417
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff814f8503)
Location: include/linux/pagemap.h:417
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In fs/buffer.c (ffffffff814467e5)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:grow_dev_page
```
```
In fs/aio.c (ffffffff814635b8)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff814e3e5d)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff814f4355)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff815770a0)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff815889b3)
Location: include/linux/pagemap.h:612
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In fs/buffer.c (ffffffff814d58f5)
Location: include/linux/pagemap.h:609
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:grow_dev_page
```
```
In fs/aio.c (ffffffff814f26a8)
Location: include/linux/pagemap.h:609
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff8157d38d)
Location: include/linux/pagemap.h:609
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff8158e826)
Location: include/linux/pagemap.h:609
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff8161b780)
Location: include/linux/pagemap.h:609
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff8162ee73)
Location: include/linux/pagemap.h:609
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In fs/aio.c (ffffffff815292de)
Location: include/linux/pagemap.h:636
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/mballoc.c (ffffffff815c5196)
Location: include/linux/pagemap.h:636
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff816538f0)
Location: include/linux/pagemap.h:636
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff816670d6)
Location: include/linux/pagemap.h:636
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In fs/aio.c (ffffffff8155e1ae)
Location: include/linux/pagemap.h:754
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/mballoc.c (ffffffff815fd416)
Location: include/linux/pagemap.h:754
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff8168cf00)
Location: include/linux/pagemap.h:754
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify_store
```
```
In fs/fuse/readdir.c (ffffffff816a1426)
Location: include/linux/pagemap.h:754
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
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
In fs/buffer.c (ffff8000103dcea4)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/aio.c (ffff8000103fb1e4)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffff800010481660)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffff8000104909d8)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffff800010504b58)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In fs/fuse/readdir.c (ffff8000105147dc)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In fs/buffer.c (c05b63a0)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_slow
```
```
In fs/aio.c (c05d0540)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (c0642808)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (c0651b3c)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (c06c1280)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In fs/fuse/readdir.c (c06cf560)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In fs/buffer.c (c0000000004e2548)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/aio.c (c000000000508118)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (c0000000005a5d20)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (c0000000005b8100)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (c000000000649d80)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In fs/fuse/readdir.c (c00000000065ce30)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In fs/buffer.c (ffffffe00029507a)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/aio.c (ffffffe0002aaa9c)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffe00030a2ca)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffe0003158fc)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffe0003716d4)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In fs/fuse/readdir.c (ffffffe00037e400)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In fs/buffer.c (ffffffff8131c10f)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/aio.c (ffffffff813377fb)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff813a54a3)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff813b277c)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff8141a3db)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In fs/fuse/readdir.c (ffffffff814284f8)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In fs/buffer.c (ffffffff8130ccaf)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/aio.c (ffffffff8132852b)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff81395f33)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff813a320c)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff8140ae5b)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In fs/fuse/readdir.c (ffffffff81418f78)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In fs/buffer.c (ffffffff81319bdf)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/aio.c (ffffffff813352cb)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff813a2d03)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff813affdc)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff8141657b)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In fs/fuse/readdir.c (ffffffff81424698)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
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
In fs/buffer.c (ffffffff8132b89f)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:__getblk_gfp
```
```
In fs/aio.c (ffffffff813482bb)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/ext4/inode.c (ffffffff813b73e3)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
```
```
In fs/ext4/mballoc.c (ffffffff813c4a3b)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/fuse/dev.c (ffffffff8142d2db)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
```
In fs/fuse/readdir.c (ffffffff8143b668)
Location: include/linux/pagemap.h:307
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
</ul>

## Differences
