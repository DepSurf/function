# Function: <code>ext4_group_desc_csum_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812bad00)
Location: fs/ext4/super.c:2110
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
```
**Symbols:**

```
ffffffff812bad00-ffffffff812bad34: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e9c10)
Location: fs/ext4/super.c:2229
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff812e9c10-ffffffff812e9c45: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ff980)
Location: fs/ext4/super.c:2254
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
```
**Symbols:**

```
ffffffff812ff980-ffffffff812ff9b5: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81334770)
Location: fs/ext4/super.c:2312
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81334770-ffffffff813347af: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81358c80)
Location: fs/ext4/super.c:2315
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81358c80-ffffffff81358cbe: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813875f0)
Location: fs/ext4/super.c:2356
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff813875f0-ffffffff8138762e: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813a0130)
Location: fs/ext4/super.c:2418
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff813a0130-ffffffff813a016e: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ca960)
Location: fs/ext4/super.c:2461
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813ca960-ffffffff813ca9a1: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3d10)
Location: fs/ext4/super.c:2479
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813e3d10-ffffffff813e3d51: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81431170)
Location: fs/ext4/super.c:2633
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff81431170-ffffffff814311b4: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81449f40)
Location: fs/ext4/super.c:2838
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff81449f40-ffffffff81449f84: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144f8c0)
Location: fs/ext4/super.c:2864
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff8144f8c0-ffffffff8144f904: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814a3440)
Location: fs/ext4/super.c:2850
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff814a3440-ffffffff814a3484: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8152a900)
Location: fs/ext4/super.c:3229
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff8152a900-ffffffff8152a950: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c9520)
Location: fs/ext4/super.c:3218
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff815c9520-ffffffff815c9570: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81601310)
Location: fs/ext4/super.c:3272
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff81601310-ffffffff81601360: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8163a070)
Location: fs/ext4/super.c:3278
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff8163a070-ffffffff8163a0c0: ext4_group_desc_csum_set (STB_GLOBAL)
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
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104bd408)
Location: fs/ext4/super.c:2479
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffff8000104bd408-ffff8000104bd48c: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0680af4)
Location: fs/ext4/super.c:2479
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
c0680af4-c0680ba8: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f3440)
Location: fs/ext4/super.c:2479
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
c0000000005f3440-c0000000005f34bc: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000338f92)
Location: fs/ext4/super.c:2479
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffe000338f92-ffffffe000338fee: ext4_group_desc_csum_set (STB_GLOBAL)
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
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813dc2f0)
Location: fs/ext4/super.c:2479
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813dc2f0-ffffffff813dc331: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ccd70)
Location: fs/ext4/super.c:2479
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813ccd70-ffffffff813ccdb1: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d9790)
Location: fs/ext4/super.c:2479
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813d9790-ffffffff813d97d1: ext4_group_desc_csum_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_group_desc_csum_set(struct super_block *sb, __u32 block_group, struct ext4_group_desc *gdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813eea70)
Location: fs/ext4/super.c:2479
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/resize.c:ext4_setup_new_descs
```
**Symbols:**

```
ffffffff813eea70-ffffffff813eeab1: ext4_group_desc_csum_set (STB_GLOBAL)
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
