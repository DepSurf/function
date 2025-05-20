# Function: <code>ext4_read_bh_nowait</code>

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
void ext4_read_bh_nowait(struct buffer_head *bh, int op_flags, bh_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81444d90)
Location: fs/ext4/super.c:161
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
**Symbols:**

```
ffffffff81444d90-ffffffff81444df3: ext4_read_bh_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ext4_read_bh_nowait(struct buffer_head *bh, int op_flags, bh_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144a6b0)
Location: fs/ext4/super.c:161
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
**Symbols:**

```
ffffffff8144a6b0-ffffffff8144a713: ext4_read_bh_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_read_bh_nowait(struct buffer_head *bh, int op_flags, bh_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8149e190)
Location: fs/ext4/super.c:158
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
**Symbols:**

```
ffffffff8149e190-ffffffff8149e1ec: ext4_read_bh_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_read_bh_nowait(struct buffer_head *bh, int op_flags, bh_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81524750)
Location: fs/ext4/super.c:177
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
**Symbols:**

```
ffffffff81524750-ffffffff815247c2: ext4_read_bh_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_read_bh_nowait(struct buffer_head *bh, blk_opf_t op_flags, bh_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c1ba0)
Location: fs/ext4/super.c:177
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
**Symbols:**

```
ffffffff815c1ba0-ffffffff815c1c1a: ext4_read_bh_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_read_bh_nowait(struct buffer_head *bh, blk_opf_t op_flags, bh_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f9320)
Location: fs/ext4/super.c:177
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
**Symbols:**

```
ffffffff815f9320-ffffffff815f9398: ext4_read_bh_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_read_bh_nowait(struct buffer_head *bh, blk_opf_t op_flags, bh_end_io_t *end_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81631eb0)
Location: fs/ext4/super.c:178
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
**Symbols:**

```
ffffffff81631eb0-ffffffff81631f28: ext4_read_bh_nowait (STB_GLOBAL)
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
