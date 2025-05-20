# Function: <code>mark_buffer_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812429f0)
Location: fs/buffer.c:1158
Inline: False
Direct callers:
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff812429f0-ffffffff81242b05: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126ad20)
Location: fs/buffer.c:1149
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff8126ad20-ffffffff8126ae2b: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127de50)
Location: fs/buffer.c:1149
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff8127de50-ffffffff8127df5b: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128ba10)
Location: fs/buffer.c:1146
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff8128ba10-ffffffff8128baf8: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ae5c0)
Location: fs/buffer.c:1106
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff812ae5c0-ffffffff812ae6ae: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d61a0)
Location: fs/buffer.c:1077
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff812d61a0-ffffffff812d6290: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812eb570)
Location: fs/buffer.c:1085
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff812eb570-ffffffff812eb660: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130cc70)
Location: fs/buffer.c:1086
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff8130cc70-ffffffff8130cd60: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131ff60)
Location: fs/buffer.c:1086
Inline: True
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff8131ff60-ffffffff81320050: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81359fa0)
Location: fs/buffer.c:1112
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff81359fa0-ffffffff8135a090: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813680d0)
Location: fs/buffer.c:1111
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff813680d0-ffffffff813681ae: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136eb90)
Location: fs/buffer.c:1107
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff8136eb90-ffffffff8136ec6e: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813bc6d0)
Location: fs/buffer.c:1082
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff813bc6d0-ffffffff813bc7ab: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81446380)
Location: fs/buffer.c:1079
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/resize.c:update_backups
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff81446380-ffffffff81446500: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d5460)
Location: fs/buffer.c:1079
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/resize.c:update_backups
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff814d5460-ffffffff814d55e0: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff815082d0)
Location: fs/buffer.c:1191
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/resize.c:update_backups
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff815082d0-ffffffff815083ca: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153d080)
Location: fs/buffer.c:1174
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_commit_write
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/resize.c:update_backups
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff8153d080-ffffffff8153d17a: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d8a20)
Location: fs/buffer.c:1086
Inline: True
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffff8000103d8a20-ffff8000103d8bd0: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b1910)
Location: fs/buffer.c:1086
Inline: True
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
c05b1910-c05b1a88: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dc270)
Location: fs/buffer.c:1086
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:mark_buffer_dirty_inode
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
c0000000004dc270-c0000000004dc488: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000291608)
Location: fs/buffer.c:1086
Inline: True
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffe000291608-ffffffe000291732: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318540)
Location: fs/buffer.c:1086
Inline: True
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff81318540-ffffffff81318630: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81309130)
Location: fs/buffer.c:1086
Inline: True
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff81309130-ffffffff81309220: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81316010)
Location: fs/buffer.c:1086
Inline: True
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff81316010-ffffffff81316100: mark_buffer_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_dirty(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81327d20)
Location: fs/buffer.c:1086
Inline: True
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_super
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/resize.c:update_backups
  - fs/ext4/super.c:ext4_commit_super
  - fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer
  - fs/jbd2/recovery.c:do_one_pass
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
```
**Symbols:**

```
ffffffff81327d20-ffffffff81327e25: mark_buffer_dirty (STB_GLOBAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
