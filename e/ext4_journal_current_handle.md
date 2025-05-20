# Function: <code>ext4_journal_current_handle</code>

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
In fs/ext4/fsync.c (ffffffff81292b32)
Location: fs/ext4/ext4_jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff81298f21)
Location: fs/ext4/ext4_jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/namei.c (ffffffff812a644d)
Location: fs/ext4/ext4_jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
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
In fs/ext4/fsync.c (ffffffff812c0083)
Location: fs/ext4/ext4_jbd2.h:337
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff812cc456)
Location: fs/ext4/ext4_jbd2.h:337
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff812d68ae)
Location: fs/ext4/ext4_jbd2.h:337
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff812d56b3)
Location: fs/ext4/ext4_jbd2.h:337
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff812e2266)
Location: fs/ext4/ext4_jbd2.h:337
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff812ec5ae)
Location: fs/ext4/ext4_jbd2.h:337
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff812f33ad)
Location: fs/ext4/ext4_jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff81306539)
Location: fs/ext4/ext4_jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff8131c2bf)
Location: fs/ext4/ext4_jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff8131793d)
Location: fs/ext4/ext4_jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff8132b109)
Location: fs/ext4/ext4_jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_overwrite
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff813408da)
Location: fs/ext4/ext4_jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff813457da)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff8135517f)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_overwrite
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff8136e8d5)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff8135d92d)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff8136d4aa)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_overwrite
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff81386d65)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff81386ae3)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff81396a9a)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff813b0d0b)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff8139f533)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff813af4ca)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff813c9d34)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff813eb444)
Location: fs/ext4/ext4_jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff813fb53a)
Location: fs/ext4/ext4_jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff8140fc7b)
Location: fs/ext4/ext4_jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_whiteout_for_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff813fd671)
Location: fs/ext4/ext4_jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff8140dc6a)
Location: fs/ext4/ext4_jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/namei.c (ffffffff8142330f)
Location: fs/ext4/ext4_jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_whiteout_for_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff81403a81)
Location: fs/ext4/ext4_jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff81413e2c)
Location: fs/ext4/ext4_jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/namei.c (ffffffff8142f83b)
Location: fs/ext4/ext4_jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff81456251)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff8145eaa3)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff814671ac)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/namei.c (ffffffff81483e8b)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff814d3c51)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff814dd1d5)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff814e6d5c)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/namei.c (ffffffff8150700d)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff8156c8a1)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff81576205)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8158056a)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/namei.c (ffffffff815a1ebe)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff815a473e)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff815adb05)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815b7b2a)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/namei.c (ffffffff815d8843)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff815dd57e)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff815e68c5)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815f08b1)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/namei.c (ffffffff81610eae)
Location: fs/ext4/ext4_jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffff80001047294c)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffff800010483de0)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffff8000104a18dc)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (c0633d78)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (c0645408)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (c0663a88)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (c0000000005937c8)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (c0000000005a8ea4)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (c0000000005ce404)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffe0002fe7ec)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffe00030c3a2)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffe000323850)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff81397b13)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff813a7aaa)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff813c2314)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff813885a3)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff8139853a)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff813b2da4)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff81395473)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff813a530a)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff813bf7c4)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
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
In fs/ext4/fsync.c (ffffffff813a9593)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff813b9a4a)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff813d48a4)
Location: fs/ext4/ext4_jbd2.h:330
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
</details>
</li>
</ul>

## Differences
