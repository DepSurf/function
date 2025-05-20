# Function: <code>ll_rw_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ll_rw_block(int rw, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81244f90)
Location: fs/buffer.c:3086
Inline: False
Direct callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/super.c:ext4_load_journal
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff81244f90-ffffffff8124502b: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126db60)
Location: fs/buffer.c:3145
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff8126db60-ffffffff8126dc10: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81280db0)
Location: fs/buffer.c:3186
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff81280db0-ffffffff81280e60: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128e690)
Location: fs/buffer.c:3173
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff8128e690-ffffffff8128e741: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b1280)
Location: fs/buffer.c:3141
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_load_journal
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff812b1280-ffffffff812b1331: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d90e0)
Location: fs/buffer.c:3112
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_load_journal
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff812d90e0-ffffffff812d9195: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ee5b0)
Location: fs/buffer.c:3124
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff812ee5b0-ffffffff812ee665: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130fdb0)
Location: fs/buffer.c:3131
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff8130fdb0-ffffffff8130fe5e: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81322d80)
Location: fs/buffer.c:3108
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff81322d80-ffffffff81322e2e: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135a230)
Location: fs/buffer.c:3109
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff8135a230-ffffffff8135a2e7: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81368350)
Location: fs/buffer.c:3090
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff81368350-ffffffff81368407: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136ef90)
Location: fs/buffer.c:3111
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff8136ef90-ffffffff8136f047: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813bdbd0)
Location: fs/buffer.c:3090
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff813bdbd0-ffffffff813bdc87: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81444000)
Location: fs/buffer.c:3075
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff81444000-ffffffff814440cc: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103dbe38)
Location: fs/buffer.c:3108
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffff8000103dbe38-ffff8000103dbfc0: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b51a8)
Location: fs/buffer.c:3108
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
c05b51a8-c05b52dc: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e1240)
Location: fs/buffer.c:3108
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
c0000000004e1240-c0000000004e13d4: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe0002943c4)
Location: fs/buffer.c:3108
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffe0002943c4-ffffffe0002944b8: ll_rw_block (STB_GLOBAL)
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
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131b360)
Location: fs/buffer.c:3108
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff8131b360-ffffffff8131b40e: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130bf00)
Location: fs/buffer.c:3108
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff8130bf00-ffffffff8130bfae: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318e30)
Location: fs/buffer.c:3108
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff81318e30-ffffffff81318ede: ll_rw_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ll_rw_block(int op, int op_flags, int nr, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132aa60)
Location: fs/buffer.c:3108
Inline: False
Direct callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__breadahead
  - fs/buffer.c:write_boundary_block
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_bread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
**Symbols:**

```
ffffffff8132aa60-ffffffff8132ab0e: ll_rw_block (STB_GLOBAL)
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
<code>rw, nr, bhs</code> ➡️ <code>op, op_flags, nr, bhs</code>
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
