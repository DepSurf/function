# Function: <code>ext4_read_bh</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_bh(struct buffer_head *bh, int op_flags, bh_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81444e00)
Location: fs/ext4/super.c:173
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff81444e00-ffffffff81444ea4: ext4_read_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_bh(struct buffer_head *bh, int op_flags, bh_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144a720)
Location: fs/ext4/super.c:173
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff8144a720-ffffffff8144a7c4: ext4_read_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_bh(struct buffer_head *bh, int op_flags, bh_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8149e1f0)
Location: fs/ext4/super.c:170
Inline: True
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff8149e1f0-ffffffff8149e28d: ext4_read_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_read_bh(struct buffer_head *bh, int op_flags, bh_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815247d0)
Location: fs/ext4/super.c:189
Inline: False
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff815247d0-ffffffff81524870: ext4_read_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_read_bh(struct buffer_head *bh, blk_opf_t op_flags, bh_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c1c30)
Location: fs/ext4/super.c:189
Inline: False
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff815c1c30-ffffffff815c1cc3: ext4_read_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_read_bh(struct buffer_head *bh, blk_opf_t op_flags, bh_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f93b0)
Location: fs/ext4/super.c:189
Inline: False
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff815f93b0-ffffffff815f9441: ext4_read_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_read_bh(struct buffer_head *bh, blk_opf_t op_flags, bh_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81631f40)
Location: fs/ext4/super.c:190
Inline: False
Direct callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
**Symbols:**

```
ffffffff81631f40-ffffffff81631fd1: ext4_read_bh (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param type changed. </b>
<code>int op_flags</code> ➡️ <code>blk_opf_t op_flags</code>
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
