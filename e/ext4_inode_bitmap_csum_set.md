# Function: <code>ext4_inode_bitmap_csum_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81290540)
Location: fs/ext4/bitmap.c:40
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81290540-ffffffff81290643: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff812bda60)
Location: fs/ext4/bitmap.c:40
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff812bda60-ffffffff812bdb63: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff812d30b0)
Location: fs/ext4/bitmap.c:40
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff812d30b0-ffffffff812d31b3: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff812e4660)
Location: fs/ext4/bitmap.c:40
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff812e4660-ffffffff812e4709: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81309090)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81309090-ffffffff81309139: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81336fc0)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81336fc0-ffffffff8133706b: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff8134e240)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff8134e240-ffffffff8134e2eb: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81376c00)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff81376c00-ffffffff81376ca4: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff8138ee70)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff8138ee70-ffffffff8138ef14: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff813da410)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813da410-ffffffff813da4b4: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff813ec0e0)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813ec0e0-ffffffff813ec184: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff813f2610)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813f2610-ffffffff813f26b4: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff814445f0)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff814445f0-ffffffff81444694: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff814c0510)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff814c0510-ffffffff814c05d5: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81558590)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff81558590-ffffffff81558655: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff815903e0)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff815903e0-ffffffff815904a1: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff815c9120)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff815c9120-ffffffff815c91e1: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffff800010461670)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffff800010461670-ffff800010461724: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (c0621b18)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
c0621b18-c0621bd8: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (c00000000057dbd0)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
c00000000057dbd0-c00000000057dcdc: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffe0002f0662)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffe0002f0662-ffffffe0002f0702: ext4_inode_bitmap_csum_set (STB_GLOBAL)
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
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81387450)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff81387450-ffffffff813874f4: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81377ee0)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff81377ee0-ffffffff81377f84: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81384f20)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff81384f20-ffffffff81384fc4: ext4_inode_bitmap_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_inode_bitmap_csum_set(struct super_block *sb, ext4_group_t group, struct ext4_group_desc *gdp, struct buffer_head *bh, int sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/bitmap.c (ffffffff81398aa0)
Location: fs/ext4/bitmap.c:41
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff81398aa0-ffffffff81398b44: ext4_inode_bitmap_csum_set (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>ext4_group_t group</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, group, gdp, bh, sz</code> ➡️ <code>sb, gdp, bh, sz</code>
</li>
</ul>
</details>
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
