# Function: <code>ext4_free_inodes_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b7bf0)
Location: fs/ext4/super.c:207
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_count_free_inodes
```
**Symbols:**

```
ffffffff812b7bf0-ffffffff812b7c17: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812edb5a)
Location: fs/ext4/super.c:236
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
**Symbols:**

```
ffffffff812e68f0-ffffffff812e6917: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81303af8)
Location: fs/ext4/super.c:238
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
**Symbols:**

```
ffffffff812fc4a0-ffffffff812fc4c7: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81338229)
Location: fs/ext4/super.c:240
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
**Symbols:**

```
ffffffff813310f0-ffffffff81331115: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8135c70c)
Location: fs/ext4/super.c:240
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
**Symbols:**

```
ffffffff813555b0-ffffffff813555d5: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8138b153)
Location: fs/ext4/super.c:240
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813839e0-ffffffff81383a05: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813a33c7)
Location: fs/ext4/super.c:263
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8139c4c0-ffffffff8139c4e5: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce06a)
Location: fs/ext4/super.c:264
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813c6710-ffffffff813c6735: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e7b14)
Location: fs/ext4/super.c:259
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813dfad0-ffffffff813dfaf5: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81430bc8)
Location: fs/ext4/super.c:239
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8142c390-ffffffff8142c3b5: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144998c)
Location: fs/ext4/super.c:328
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff814451b0-ffffffff814451d5: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144f30c)
Location: fs/ext4/super.c:328
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8144aad0-ffffffff8144aaf5: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814a2e8d)
Location: fs/ext4/super.c:325
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8149e9e0-ffffffff8149ea05: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8152a311)
Location: fs/ext4/super.c:344
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff815250e0-ffffffff8152510f: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c8cb1)
Location: fs/ext4/super.c:338
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff815c2610-ffffffff815c263f: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81600a72)
Location: fs/ext4/super.c:338
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff815f9d90-ffffffff815f9dbf: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff816397c2)
Location: fs/ext4/super.c:346
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81632990-ffffffff816329bf: ext4_free_inodes_count (STB_GLOBAL)
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
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104c04d0)
Location: fs/ext4/super.c:259
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffff8000104b8958-ffff8000104b899c: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0683c1c)
Location: fs/ext4/super.c:259
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
c067c0f4-c067c124: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f6d54)
Location: fs/ext4/super.c:259
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
c0000000005edaf0-c0000000005edb24: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe00033c3b4)
Location: fs/ext4/super.c:259
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffe000335364-ffffffe0003353ac: ext4_free_inodes_count (STB_GLOBAL)
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
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e00f4)
Location: fs/ext4/super.c:259
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813d80b0-ffffffff813d80d5: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d0b74)
Location: fs/ext4/super.c:259
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813c8b30-ffffffff813c8b55: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813dd46d)
Location: fs/ext4/super.c:259
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813d5540-ffffffff813d5565: ext4_free_inodes_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
__u32 ext4_free_inodes_count(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813f288b)
Location: fs/ext4/super.c:259
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
Direct callers:
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813ea7c0-ffffffff813ea7e5: ext4_free_inodes_count (STB_GLOBAL)
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
