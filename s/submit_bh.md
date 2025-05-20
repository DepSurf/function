# Function: <code>submit_bh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int rw, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81244b60)
Location: fs/buffer.c:3055
Inline: True
Inline callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff81244b60-ffffffff81244b74: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126dbca)
Location: fs/buffer.c:3113
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff8126d720-ffffffff8126d735: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81280e1a)
Location: fs/buffer.c:3154
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff81280970-ffffffff81280985: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128e6fa)
Location: fs/buffer.c:3141
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/bitmap.c:read_page
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff8128e230-ffffffff8128e245: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b12ea)
Location: fs/buffer.c:3109
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff812b0e40-ffffffff812b0e55: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d914e)
Location: fs/buffer.c:3080
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff812d8cb0-ffffffff812d8cc5: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ee61e)
Location: fs/buffer.c:3092
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff812ee180-ffffffff812ee195: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130fe15)
Location: fs/buffer.c:3099
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff8130f940-ffffffff8130f955: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81322de5)
Location: fs/buffer.c:3076
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff813228c0-ffffffff813228d5: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135d873)
Location: fs/buffer.c:3077
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81359820-ffffffff81359835: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136b463)
Location: fs/buffer.c:3058
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff813675b0-ffffffff813675c5: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81371d03)
Location: fs/buffer.c:3079
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff8136dff0-ffffffff8136e005: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813c0d23)
Location: fs/buffer.c:3058
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/super.c:ext4_read_bh_nowait
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff813bccf0-ffffffff813bcd05: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814447bb)
Location: fs/buffer.c:3043
Inline: True
Inline callers:
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff814430b0-ffffffff814430ce: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void submit_bh(blk_opf_t opf, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d33ea)
Location: fs/buffer.c:2705
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff814d2370-ffffffff814d238c: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void submit_bh(blk_opf_t opf, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150a67a)
Location: fs/buffer.c:2843
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/mmp.c:write_mmp_block_thawed
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81508c30-ffffffff81508c4c: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void submit_bh(blk_opf_t opf, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153f62a)
Location: fs/buffer.c:2803
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/mmp.c:write_mmp_block_thawed
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:write_file_page
```
**Symbols:**

```
ffffffff8153dad0-ffffffff8153daec: submit_bh (STB_GLOBAL)
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
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103dbf24)
Location: fs/buffer.c:3076
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffff8000103db7d8-ffff8000103db824: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b5294)
Location: fs/buffer.c:3076
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
c05b4b88-c05b4bb4: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e3cec)
Location: fs/buffer.c:3076
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
c0000000004e0b60-c0000000004e0b7c: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000294462)
Location: fs/buffer.c:3076
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffe000293efe-ffffffe000293f3c: submit_bh (STB_GLOBAL)
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
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131b3c5)
Location: fs/buffer.c:3076
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff8131aea0-ffffffff8131aeb5: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130bf65)
Location: fs/buffer.c:3076
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff8130ba40-ffffffff8130ba55: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318e95)
Location: fs/buffer.c:3076
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81318970-ffffffff81318985: submit_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int submit_bh(int op, int op_flags, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132aac5)
Location: fs/buffer.c:3076
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_write_superblock
  - drivers/md/md-bitmap.c:read_page
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff8132a5b0-ffffffff8132a5c5: submit_bh (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, bh</code> ➡️ <code>op, op_flags, bh</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, op_flags, bh</code> ➡️ <code>opf, bh</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
