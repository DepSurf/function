# Function: <code>__getblk</code>

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
In fs/buffer.c (ffffffff812450a6)
Location: include/linux/buffer_head.h:366
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff812eb569)
Location: include/linux/buffer_head.h:366
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff812ef6fc)
Location: include/linux/buffer_head.h:366
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffff8126dc86)
Location: include/linux/buffer_head.h:370
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff81319d41)
Location: include/linux/buffer_head.h:370
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8131dc6c)
Location: include/linux/buffer_head.h:370
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffff81280ed6)
Location: include/linux/buffer_head.h:373
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff8132fd31)
Location: include/linux/buffer_head.h:373
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff81335ad0)
Location: include/linux/buffer_head.h:373
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffff8128e7c6)
Location: include/linux/buffer_head.h:374
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff81344cdf)
Location: include/linux/buffer_head.h:374
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8134a860)
Location: include/linux/buffer_head.h:374
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffff812b13b6)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff8136937f)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8136eeb0)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffff812d9231)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff81397b2d)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8139d460)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffff812ee701)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff813b08b3)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff813b61d0)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffff8130fef1)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff813dae42)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff813e08ff)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffff81322ec1)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff813f4e92)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff813fa93f)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffff8135bf6c)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff814421e8)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff814480d0)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffff8136a50c)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff8145e539)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff81464c10)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
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
In fs/buffer.c (ffffffff813710e1)
Location: include/linux/buffer_head.h:378
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff81463dbe)
Location: include/linux/buffer_head.h:378
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8146a3a0)
Location: include/linux/buffer_head.h:378
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
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
In fs/buffer.c (ffffffff813c0ac1)
Location: include/linux/buffer_head.h:378
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff814b9390)
Location: include/linux/buffer_head.h:378
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff814c0b00)
Location: include/linux/buffer_head.h:378
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
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
In fs/buffer.c (ffffffff81445aa2)
Location: include/linux/buffer_head.h:400
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff815430bc)
Location: include/linux/buffer_head.h:400
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8154b398)
Location: include/linux/buffer_head.h:400
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
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
In fs/buffer.c (ffffffff814d4b55)
Location: include/linux/buffer_head.h:407
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff815e1f14)
Location: include/linux/buffer_head.h:407
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff815eb038)
Location: include/linux/buffer_head.h:407
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
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
In fs/buffer.c (ffffffff8150c7f8)
Location: include/linux/buffer_head.h:420
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff8161972c)
Location: include/linux/buffer_head.h:420
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff81622aa8)
Location: include/linux/buffer_head.h:420
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
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
In fs/ext4/balloc.c (ffffffff815c8874)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff815ce1d9)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff815df044)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815e1e4a)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff815e57f9)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815ec0a9)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff816074ea)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff8161755a)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/xattr.c (ffffffff81641fd6)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/jbd2/recovery.c (ffffffff8165264d)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8165baff)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
```
```
In fs/fat/dir.c (ffffffff8166d827)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8166f18a)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/buffer.c (ffff8000103dc0c4)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffff8000104d07f0)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffff8000104d7c38)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (c05b53cc)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (c0693458)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (c0699b58)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (c0000000004e14cc)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (c0000000006099c0)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (c0000000006128c8)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffe000294546)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffe000347eee)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffe00034d88e)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffff8131b4a1)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff813ed472)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff813f2f1f)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffff8130c041)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff813ddef2)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff813e399f)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffff81318f71)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff813ea7f2)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff813f029f)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In fs/buffer.c (ffffffff8132aba1)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/buffer.c:__breadahead
```
```
In fs/jbd2/recovery.c (ffffffff81400159)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff81405cef)
Location: include/linux/buffer_head.h:376
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
</details>
</li>
</ul>

## Differences
