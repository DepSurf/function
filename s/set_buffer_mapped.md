# Function: <code>set_buffer_mapped</code>

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
In fs/buffer.c (ffffffff81242f06)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff812470e8)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffff81297139)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff812f2da0)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff812fb68a)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/bitmap.c (ffffffff8169b9e9)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
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
In fs/buffer.c (ffffffff8126e15b)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8126f9e8)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffff812c4762)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff81320771)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff8132f2fd)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/bitmap.c (ffffffff816fcbde)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
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
In fs/buffer.c (ffffffff812813b4)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff81282be8)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffff812d9e12)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff81336614)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff8134505d)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/bitmap.c (ffffffff8172e762)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
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
In fs/buffer.c (ffffffff8128ec9e)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff812905c8)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffff812fdabb)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff8134b2a4)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff81359aa5)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/bitmap.c (ffffffff81747633)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
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
In fs/buffer.c (ffffffff812b186f)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff812b3288)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffff8132229b)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff8136f947)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff8137e7b5)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff817b98c3)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff812d960a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff812dbd17)
Location: include/linux/buffer_head.h:126
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81351559)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff8139de3f)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff813ad081)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff81801a7a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff812eeae2)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff812f1407)
Location: include/linux/buffer_head.h:126
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8136a385)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff813b6baf)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff813c6432)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff8182dc8c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff813102af)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff81313868)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffff813939d5)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff813e1296)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff813f366f)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff818702dc)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff8132327f)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff81326778)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffff813ac375)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff813fb2e6)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff8140d54f)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff818a20dc)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff8135b985)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8135f998)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffff813f86a5)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff81448a53)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff81459fa8)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff81973d49)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff81369f35)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8136d1a8)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffff8140a345)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff8146564f)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff814762f8)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff81978c49)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff8136f0b5)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff81373a18)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffff81410515)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff8146ada0)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff8147bd68)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff8195c139)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff813bdd11)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:init_page_buffers
```
```
In fs/ext4/inode.c (ffffffff81465b85)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff814c15b0)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff814d34e5)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
```
In block/fops.c (ffffffff815c59ef)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - block/fops.c:blkdev_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff81a01949)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff814429db)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:init_page_buffers
```
```
In fs/ext4/inode.c (ffffffff814e552d)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff8154bf68)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff815608e9)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
```
In block/fops.c (ffffffff8167041f)
Location: include/linux/buffer_head.h:125
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff81b6984d)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff814d19e0)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:init_page_buffers
```
```
In fs/ext4/inode.c (ffffffff8157ebfd)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff815ebd38)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff81603b09)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
```
In block/fops.c (ffffffff8172b36f)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - block/fops.c:blkdev_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff81d0570d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff815080f0)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:folio_init_buffers
```
```
In fs/ext4/inode.c (ffffffff815b298d)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff81623818)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff8163ba29)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
```
In block/fops.c (ffffffff817673df)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - block/fops.c:blkdev_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff81d6e7f5)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff8153ce50)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:folio_init_buffers
```
```
In fs/ext4/inode.c (ffffffff815eb78d)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff8165c79d)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff81674f89)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
```
```
In block/fops.c (ffffffff817a90ff)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - block/fops.c:blkdev_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff81e23530)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_file_page
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
In fs/buffer.c (ffff8000103dc5dc)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffff8000103e0c34)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffff800010480780)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffff8000104d88ec)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffff8000104ecffc)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/md-bitmap.c (ffff800010af7070)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (c05b5a20)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (c05b8688)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (c063fe8c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (c069a7c0)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (c06a9564)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/md-bitmap.c (c0bd79c4)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (c0000000004e19e0)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (c0000000004e4028)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (c0000000005a28ac)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (c000000000613748)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (c000000000629980)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/md-bitmap.c (c000000000be312c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffe000294728)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffe00029616e)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffe000309866)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffe00034e3ae)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffe00035e62a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/md-bitmap.c (ffffffe0006e8d08)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff8131b85f)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8131ed58)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffff813a4955)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff813f38c6)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff81405b2f)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff81847f5c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff8130c3ff)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8130f8f8)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffff813953e5)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff813e4346)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff813f65af)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff8180f5bc)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff8131932f)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8131c828)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffff813a21b5)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff813f0c46)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff81402eaf)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff8189758c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
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
In fs/buffer.c (ffffffff8132af6d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:init_page_buffers
```
```
In fs/block_dev.c (ffffffff8132eb28)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_block
```
```
In fs/ext4/inode.c (ffffffff813b5635)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/jbd2/journal.c (ffffffff81406709)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/fat/inode.c (ffffffff81418b0f)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
```
In drivers/md/md-bitmap.c (ffffffff818b366c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
</ul>

## Differences
