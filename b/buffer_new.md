# Function: <code>buffer_new</code>

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
In fs/buffer.c (ffffffff812444e1)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
```
```
In fs/direct-io.c (ffffffff8124aec6)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8124da03)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff8125e0e5)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
  - fs/dax.c:dax_do_io
```
```
In fs/ext4/balloc.c (ffffffff8128f485)
Location: include/linux/buffer_head.h:123
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8129774f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/page-io.c (ffffffff8129feee)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8126f0c1)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff8127379d)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff8127616f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/dax.c (ffffffff81287f2b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_do_io
```
```
In fs/ext4/balloc.c (ffffffff812bc995)
Location: include/linux/buffer_head.h:123
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812cca2c)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812ce7ea)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812822b3)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff81287215)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff81289e6d)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff812d1fe5)
Location: include/linux/buffer_head.h:123
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812dab5b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812e45ca)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8128f9c2)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff81294728)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff81296b5f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff812e3655)
Location: include/linux/buffer_head.h:123
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812fe945)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8131e287)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812b26af)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff812b766d)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812b9dca)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff81308045)
Location: include/linux/buffer_head.h:124
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81323109)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813428a7)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812da592)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff812e0350)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812e294d)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff81335f35)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81350eef)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81370727)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812efa72)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff812f4fa3)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/mpage.c (ffffffff812f75ae)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff8134d1b5)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81368f3f)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81388bb4)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81311306)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff81316b72)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81317be8)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff81375b95)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8139235b)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813b2ca4)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff813242e6)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff813299f0)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8132aa63)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff8138de05)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813aaceb)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813cbd12)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8135e31e)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff813637e1)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8136479c)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff813da205)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
```
```
In fs/ext4/inode.c (ffffffff813f6b1b)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81417e5b)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8136be18)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff8137011a)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/mpage.c (ffffffff813717a5)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff813ebed7)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
```
```
In fs/ext4/inode.c (ffffffff81409282)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8142b960)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81372748)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff813769b9)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/mpage.c (ffffffff81378a76)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff813f14d5)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8140f252)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8143257f)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff813c17a9)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff813c2f5b)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/mpage.c (ffffffff813c5422)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff814434d5)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81462255)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81485e3f)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8144867b)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff8144a6a6)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff8144c3c7)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff814bf2f5)
Location: include/linux/buffer_head.h:126
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814e16a5)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81509427)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff814d6992)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff814d8da8)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff814da7b9)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff81557235)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
```
```
In fs/ext4/inode.c (ffffffff8157a9b5)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff815a3fe5)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8150cfa5)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/mpage.c (ffffffff8150ecdc)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/direct-io.c (ffffffff81511c86)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/ext4/balloc.c (ffffffff8158f0b5)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
```
```
In fs/ext4/inode.c (ffffffff815b0b40)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff815daa38)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In fs/buffer.c (ffffffff8153d2ab)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:__block_commit_write
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/mpage.c (ffffffff815435a4)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/direct-io.c (ffffffff81546149)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/ext4/balloc.c (ffffffff815c7dc5)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
```
```
In fs/ext4/inode.c (ffffffff815e99e0)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81613245)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In fs/buffer.c (ffff8000103dd65c)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffff8000103e4e04)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffff8000103e6174)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffff80001045fefc)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffff80001047f3d0)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffff8000104a3eb0)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (c05b6b5c)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (c05bcd48)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (c05bdd4c)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (c062070c)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (c06405d8)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (c0665d3c)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (c0000000004e2fac)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (c0000000004eb190)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (c0000000004ec488)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (c00000000057c220)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (c0000000005a3138)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (c0000000005d0fc0)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffe000295692)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffe00029aa0e)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffe00029b566)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffe0002ef5ee)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffe0003083f8)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffe000325408)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8131c8c6)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff81321fd0)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81323043)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff813863e5)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a32cb)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813c42f2)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8130d466)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff81312b70)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81313be3)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff81376e75)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81393d5b)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813b4d72)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8131a396)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff8131faa0)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81320b13)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff81383eb5)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a0b2b)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813c1782)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8132c092)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/direct-io.c (ffffffff813317c0)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81332833)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/balloc.c (ffffffff81397a25)
Location: include/linux/buffer_head.h:127
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813b56fb)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff813d68e2)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
</ul>

## Differences
