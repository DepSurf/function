# Function: <code>ext4_free_group_clusters</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b7bc0)
Location: fs/ext4/super.c:199
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
```
**Symbols:**

```
ffffffff812b7bc0-ffffffff812b7be7: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812edb90)
Location: fs/ext4/super.c:228
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff812e68c0-ffffffff812e68e7: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81303b2d)
Location: fs/ext4/super.c:230
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff812fc470-ffffffff812fc497: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81338261)
Location: fs/ext4/super.c:232
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff813310c0-ffffffff813310e5: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8135c741)
Location: fs/ext4/super.c:232
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff81355580-ffffffff813555a5: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8138b17e)
Location: fs/ext4/super.c:232
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff813839b0-ffffffff813839d5: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813a33f2)
Location: fs/ext4/super.c:255
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff8139c490-ffffffff8139c4b5: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce095)
Location: fs/ext4/super.c:256
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff813c66e0-ffffffff813c6705: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e7b3b)
Location: fs/ext4/super.c:251
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff813dfaa0-ffffffff813dfac5: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81430be7)
Location: fs/ext4/super.c:231
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff8142c360-ffffffff8142c385: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814499ac)
Location: fs/ext4/super.c:320
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
**Symbols:**

```
ffffffff81445180-ffffffff814451a5: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144f32c)
Location: fs/ext4/super.c:320
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
**Symbols:**

```
ffffffff8144aaa0-ffffffff8144aac5: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814a2ead)
Location: fs/ext4/super.c:317
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
**Symbols:**

```
ffffffff8149e9b0-ffffffff8149e9d5: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8152a331)
Location: fs/ext4/super.c:336
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
**Symbols:**

```
ffffffff815250b0-ffffffff815250df: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c8cd1)
Location: fs/ext4/super.c:330
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
**Symbols:**

```
ffffffff815c25d0-ffffffff815c25ff: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81600a92)
Location: fs/ext4/super.c:330
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
**Symbols:**

```
ffffffff815f9d50-ffffffff815f9d7f: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff816397e2)
Location: fs/ext4/super.c:338
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
**Symbols:**

```
ffffffff81632950-ffffffff8163297f: ext4_free_group_clusters (STB_GLOBAL)
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
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104c0500)
Location: fs/ext4/super.c:251
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffff8000104b8910-ffff8000104b8954: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0683c58)
Location: fs/ext4/super.c:251
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
c067c0c4-c067c0f4: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f6d8c)
Location: fs/ext4/super.c:251
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
c0000000005edab0-c0000000005edae4: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe00033c3de)
Location: fs/ext4/super.c:251
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffe00033531c-ffffffe000335364: ext4_free_group_clusters (STB_GLOBAL)
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
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e011b)
Location: fs/ext4/super.c:251
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff813d8080-ffffffff813d80a5: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d0b9b)
Location: fs/ext4/super.c:251
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff813c8b00-ffffffff813c8b25: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813dd494)
Location: fs/ext4/super.c:251
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff813d5510-ffffffff813d5535: ext4_free_group_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_group_clusters(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813f28b4)
Location: fs/ext4/super.c:251
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
**Symbols:**

```
ffffffff813ea790-ffffffff813ea7b5: ext4_free_group_clusters (STB_GLOBAL)
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
