# Function: <code>ext4_get_group_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8128f3e0)
Location: fs/ext4/balloc.c:276
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff8128f3e0-ffffffff8128f47d: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812bc8f0)
Location: fs/ext4/balloc.c:279
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
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
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff812bc8f0-ffffffff812bc98d: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812d1f40)
Location: fs/ext4/balloc.c:279
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
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
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff812d1f40-ffffffff812d1fdd: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812e35b0)
Location: fs/ext4/balloc.c:279
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
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
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff812e35b0-ffffffff812e3648: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81307fa0)
Location: fs/ext4/balloc.c:280
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff81307fa0-ffffffff81308038: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81335e90)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff81335e90-ffffffff81335f28: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8134d110)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff8134d110-ffffffff8134d1a8: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81375af0)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff81375af0-ffffffff81375b84: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8138dd60)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff8138dd60-ffffffff8138ddfb: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813d9260)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:recently_deleted
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff813d9260-ffffffff813d930a: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813eaeb0)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:recently_deleted
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff813eaeb0-ffffffff813eaf9d: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813f13e0)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff813f13e0-ffffffff813f14cd: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff81cc8b12-ffffffff81cc8b39: ext4_get_group_desc.cold (STB_LOCAL)
ffffffff814433e0-ffffffff814434ce: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff81e7b856-ffffffff81e7b879: ext4_get_group_desc.cold (STB_LOCAL)
ffffffff814bf1d0-ffffffff814bf2e9: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff8206bfe7-ffffffff8206c00a: ext4_get_group_desc.cold (STB_LOCAL)
ffffffff81557100-ffffffff81557219: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:266
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff820ebe34-ffffffff820ebe5b: ext4_get_group_desc.cold (STB_LOCAL)
ffffffff8158ec50-ffffffff8158ed56: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:265
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_other
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_fill_flex_info
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff821c9098-ffffffff821c90bf: ext4_get_group_desc.cold (STB_LOCAL)
ffffffff815c7960-ffffffff815c7a66: ext4_get_group_desc (STB_GLOBAL)
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
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffff80001045fdf8)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffff80001045fdf8-ffff80001045fed4: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c0620630)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
c0620630-c06206f4: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c00000000057c110)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
c00000000057c110-c00000000057c208: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffe0002ef508)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffe0002ef508-ffffffe0002ef5ce: ext4_get_group_desc (STB_GLOBAL)
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
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81386340)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff81386340-ffffffff813863db: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81376dd0)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff81376dd0-ffffffff81376e6b: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81383e10)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff81383e10-ffffffff81383eab: ext4_get_group_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ext4_group_desc *ext4_get_group_desc(struct super_block *sb, ext4_group_t block_group, struct buffer_head **bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81397930)
Location: fs/ext4/balloc.c:264
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_count_dirs
  - fs/ext4/ialloc.c:ext4_count_free_inodes
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:find_group_orlov
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff81397930-ffffffff81397a14: ext4_get_group_desc (STB_GLOBAL)
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
