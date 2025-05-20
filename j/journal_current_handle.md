# Function: <code>journal_current_handle</code>

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
Location: include/linux/jbd2.h:1211
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff81298f21)
Location: include/linux/jbd2.h:1211
Inline: True
Inline callers:
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/namei.c (ffffffff812a644d)
Location: include/linux/jbd2.h:1211
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/super.c (ffffffff812b8897)
Location: include/linux/jbd2.h:1211
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/jbd2/transaction.c (ffffffff812e7405)
Location: include/linux/jbd2.h:1211
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_stop
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
Location: include/linux/jbd2.h:1227
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff812cc456)
Location: include/linux/jbd2.h:1227
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
Location: include/linux/jbd2.h:1227
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff812e7a68)
Location: include/linux/jbd2.h:1227
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffffffff813158e4)
Location: include/linux/jbd2.h:1227
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
Location: include/linux/jbd2.h:1227
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff812e2266)
Location: include/linux/jbd2.h:1227
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
Location: include/linux/jbd2.h:1227
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff812fd7a8)
Location: include/linux/jbd2.h:1227
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffffffff8132b8d4)
Location: include/linux/jbd2.h:1227
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
Location: include/linux/jbd2.h:1229
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff81306539)
Location: include/linux/jbd2.h:1229
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
Location: include/linux/jbd2.h:1229
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff813324f2)
Location: include/linux/jbd2.h:1229
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffffffff81340b00)
Location: include/linux/jbd2.h:1229
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
Location: include/linux/jbd2.h:1334
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff8132b109)
Location: include/linux/jbd2.h:1334
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
Location: include/linux/jbd2.h:1334
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff81356a02)
Location: include/linux/jbd2.h:1334
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffffffff81365110)
Location: include/linux/jbd2.h:1334
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
Location: include/linux/jbd2.h:1334
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff8135517f)
Location: include/linux/jbd2.h:1334
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
Location: include/linux/jbd2.h:1334
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff81384d40)
Location: include/linux/jbd2.h:1334
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffffffff81393884)
Location: include/linux/jbd2.h:1334
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
Location: include/linux/jbd2.h:1335
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff8136d4aa)
Location: include/linux/jbd2.h:1335
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
Location: include/linux/jbd2.h:1335
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff8139d830)
Location: include/linux/jbd2.h:1335
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffffffff813ac5a4)
Location: include/linux/jbd2.h:1335
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff81396a9a)
Location: include/linux/jbd2.h:1348
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff813c7a70)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffffffff813d6813)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff813af4ca)
Location: include/linux/jbd2.h:1348
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff813e0e30)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffffffff813f0853)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
Location: include/linux/jbd2.h:1351
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff813fb53a)
Location: include/linux/jbd2.h:1351
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
Location: include/linux/jbd2.h:1351
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_whiteout_for_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff8142d9e0)
Location: include/linux/jbd2.h:1351
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffffffff8143ca1a)
Location: include/linux/jbd2.h:1351
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2__journal_start
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
Location: include/linux/jbd2.h:1460
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff8140dc6a)
Location: include/linux/jbd2.h:1460
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
Location: include/linux/jbd2.h:1460
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_whiteout_for_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff814466a0)
Location: include/linux/jbd2.h:1460
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/ext4/xattr.c (ffffffff8144ff0e)
Location: include/linux/jbd2.h:1460
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/jbd2/transaction.c (ffffffff81458d9a)
Location: include/linux/jbd2.h:1460
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2__journal_start
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
Location: include/linux/jbd2.h:1469
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff81413e2c)
Location: include/linux/jbd2.h:1469
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
Location: include/linux/jbd2.h:1469
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff8144be50)
Location: include/linux/jbd2.h:1469
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/ext4/xattr.c (ffffffff814556fe)
Location: include/linux/jbd2.h:1469
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/jbd2/transaction.c (ffffffff8145e79a)
Location: include/linux/jbd2.h:1469
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2__journal_start
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
Location: include/linux/jbd2.h:1508
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff8145eaa3)
Location: include/linux/jbd2.h:1508
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff814671ac)
Location: include/linux/jbd2.h:1508
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
Location: include/linux/jbd2.h:1508
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff8149fec4)
Location: include/linux/jbd2.h:1508
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/ext4/xattr.c (ffffffff814a971e)
Location: include/linux/jbd2.h:1508
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/jbd2/transaction.c (ffffffff814b3b0a)
Location: include/linux/jbd2.h:1508
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2__journal_start
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
Location: include/linux/jbd2.h:1500
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff814dd1d5)
Location: include/linux/jbd2.h:1500
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff814e6d5c)
Location: include/linux/jbd2.h:1500
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
Location: include/linux/jbd2.h:1500
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff81526af4)
Location: include/linux/jbd2.h:1500
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/ext4/xattr.c (ffffffff81531a3e)
Location: include/linux/jbd2.h:1500
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/jbd2/transaction.c (ffffffff8153d33a)
Location: include/linux/jbd2.h:1500
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2__journal_start
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
Location: include/linux/jbd2.h:1499
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff81576205)
Location: include/linux/jbd2.h:1499
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8158056a)
Location: include/linux/jbd2.h:1499
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
Location: include/linux/jbd2.h:1499
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff815c43d4)
Location: include/linux/jbd2.h:1499
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/ext4/xattr.c (ffffffff815cffbe)
Location: include/linux/jbd2.h:1499
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/jbd2/transaction.c (ffffffff815dbb5a)
Location: include/linux/jbd2.h:1499
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2__journal_start
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
Location: include/linux/jbd2.h:1502
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff815adb05)
Location: include/linux/jbd2.h:1502
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815b7b2a)
Location: include/linux/jbd2.h:1502
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
Location: include/linux/jbd2.h:1502
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff815fbab4)
Location: include/linux/jbd2.h:1502
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/ext4/xattr.c (ffffffff816077ee)
Location: include/linux/jbd2.h:1502
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/jbd2/transaction.c (ffffffff8161361a)
Location: include/linux/jbd2.h:1502
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2__journal_start
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
Location: include/linux/jbd2.h:1496
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inline.c (ffffffff815e68c5)
Location: include/linux/jbd2.h:1496
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815f08b1)
Location: include/linux/jbd2.h:1496
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
Location: include/linux/jbd2.h:1496
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff81634654)
Location: include/linux/jbd2.h:1496
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/ext4/xattr.c (ffffffff8164052e)
Location: include/linux/jbd2.h:1496
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
```
```
In fs/jbd2/transaction.c (ffffffff8164c41a)
Location: include/linux/jbd2.h:1496
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:stop_this_handle
  - fs/jbd2/transaction.c:jbd2__journal_start
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffff800010483de0)
Location: include/linux/jbd2.h:1348
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffff8000104ba1b8)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffff8000104ca468)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (c0645408)
Location: include/linux/jbd2.h:1348
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (c067d834)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (c068ddd0)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (c0000000005a8ea4)
Location: include/linux/jbd2.h:1348
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (c0000000005ef89c)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (c000000000603218)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2__journal_start
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffe00030c3a2)
Location: include/linux/jbd2.h:1348
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffe0003366ec)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffffffe0003436e4)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff813a7aaa)
Location: include/linux/jbd2.h:1348
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff813d9410)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffffffff813e8e33)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff8139853a)
Location: include/linux/jbd2.h:1348
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff813c9e90)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffffffff813d98b3)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff813a530a)
Location: include/linux/jbd2.h:1348
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff813d68a0)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffffffff813e61b3)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff813b9a4a)
Location: include/linux/jbd2.h:1348
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
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
```
```
In fs/ext4/super.c (ffffffff813ebb51)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:__ext4_std_error
```
```
In fs/jbd2/transaction.c (ffffffff813fb6a3)
Location: include/linux/jbd2.h:1348
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
</details>
</li>
</ul>

## Differences
