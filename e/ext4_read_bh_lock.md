# Function: <code>ext4_read_bh_lock</code>

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
int ext4_read_bh_lock(struct buffer_head *bh, int op_flags, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81444eb0)
Location: fs/ext4/super.c:190
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
**Symbols:**

```
ffffffff81444eb0-ffffffff81444f13: ext4_read_bh_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_bh_lock(struct buffer_head *bh, int op_flags, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144a7d0)
Location: fs/ext4/super.c:190
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
**Symbols:**

```
ffffffff8144a7d0-ffffffff8144a833: ext4_read_bh_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_bh_lock(struct buffer_head *bh, int op_flags, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8149e290)
Location: fs/ext4/super.c:187
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
**Symbols:**

```
ffffffff8149e290-ffffffff8149e2f3: ext4_read_bh_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_bh_lock(struct buffer_head *bh, int op_flags, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81524870)
Location: fs/ext4/super.c:206
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
**Symbols:**

```
ffffffff81524870-ffffffff815248ed: ext4_read_bh_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_bh_lock(struct buffer_head *bh, blk_opf_t op_flags, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c1ce0)
Location: fs/ext4/super.c:206
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
```
**Symbols:**

```
ffffffff815c1ce0-ffffffff815c1d49: ext4_read_bh_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_bh_lock(struct buffer_head *bh, blk_opf_t op_flags, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f9460)
Location: fs/ext4/super.c:206
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/super.c:ext4_get_dev_journal
```
**Symbols:**

```
ffffffff815f9460-ffffffff815f94c9: ext4_read_bh_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_read_bh_lock(struct buffer_head *bh, blk_opf_t op_flags, bool wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81631ff0)
Location: fs/ext4/super.c:207
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
```
**Symbols:**

```
ffffffff81631ff0-ffffffff81632059: ext4_read_bh_lock (STB_GLOBAL)
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
