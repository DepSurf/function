# Function: <code>ext4_get_group_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct ext4_group_info *ext4_get_group_info(struct super_block *sb, ext4_group_t group);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8128efad)
Location: fs/ext4/ext4.h:2772
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81292f20)
Location: fs/ext4/ext4.h:2772
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_init_inode_table
Direct callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff812ce1bd)
Location: fs/ext4/ext4.h:2772
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff81292f20-ffffffff81292f57: ext4_get_group_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct ext4_group_info *ext4_get_group_info(struct super_block *sb, ext4_group_t group);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812bcc45)
Location: fs/ext4/ext4.h:2807
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812c2fac)
Location: fs/ext4/ext4.h:2807
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8130542c)
Location: fs/ext4/ext4.h:2807
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff812c04d0-ffffffff812c0507: ext4_get_group_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct ext4_group_info *ext4_get_group_info(struct super_block *sb, ext4_group_t group);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812d2295)
Location: fs/ext4/ext4.h:2785
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff812d859c)
Location: fs/ext4/ext4.h:2785
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8131b3fc)
Location: fs/ext4/ext4.h:2785
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff812d5b00-ffffffff812d5b37: ext4_get_group_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct ext4_group_info *ext4_get_group_info(struct super_block *sb, ext4_group_t group);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812e391b)
Location: fs/ext4/ext4.h:2803
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812f69bc)
Location: fs/ext4/ext4.h:2803
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813127ec)
Location: fs/ext4/ext4.h:2803
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff812e3190-ffffffff812e31c7: ext4_get_group_info (STB_LOCAL)
ffffffff812f3d90-ffffffff812f3dc7: ext4_get_group_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct ext4_group_info *ext4_get_group_info(struct super_block *sb, ext4_group_t group);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8130830b)
Location: fs/ext4/ext4.h:2760
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff8131afd6)
Location: fs/ext4/ext4.h:2760
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81336fbf)
Location: fs/ext4/ext4.h:2760
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff81318370-ffffffff813183a6: ext4_get_group_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8133620d)
Location: fs/ext4/ext4.h:2765
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff81348f0c)
Location: fs/ext4/ext4.h:2765
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813655bf)
Location: fs/ext4/ext4.h:2765
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff813870cb)
Location: fs/ext4/ext4.h:2765
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8134d48d)
Location: fs/ext4/ext4.h:2792
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff813610cc)
Location: fs/ext4/ext4.h:2792
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8137d97f)
Location: fs/ext4/ext4.h:2792
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff8139fbdb)
Location: fs/ext4/ext4.h:2792
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81375e8f)
Location: fs/ext4/ext4.h:2872
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff8138a16f)
Location: fs/ext4/ext4.h:2872
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813a7566)
Location: fs/ext4/ext4.h:2872
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff813c9ecb)
Location: fs/ext4/ext4.h:2872
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8138e0fd)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff813a2b85)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813c03f6)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff813e31cb)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813d9616)
Location: fs/ext4/ext4.h:3045
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff813eef05)
Location: fs/ext4/ext4.h:3045
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8140c526)
Location: fs/ext4/ext4.h:3045
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff8143076b)
Location: fs/ext4/ext4.h:3045
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813eb2b3)
Location: fs/ext4/ext4.h:3219
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff8140167a)
Location: fs/ext4/ext4.h:3219
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8141f984)
Location: fs/ext4/ext4.h:3219
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff814494fd)
Location: fs/ext4/ext4.h:3219
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813f17e1)
Location: fs/ext4/ext4.h:3281
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff81407ad7)
Location: fs/ext4/ext4.h:3281
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81426256)
Location: fs/ext4/ext4.h:3281
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff8144ee6d)
Location: fs/ext4/ext4.h:3281
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct ext4_group_info *ext4_get_group_info(struct super_block *sb, ext4_group_t group);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81443836)
Location: fs/ext4/ext4.h:3351
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff8145996b)
Location: fs/ext4/ext4.h:3351
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81479f09)
Location: fs/ext4/ext4.h:3351
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff814a29ad)
Location: fs/ext4/ext4.h:3351
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff8146ef20-ffffffff8146ef86: ext4_get_group_info (STB_LOCAL)
ffffffff81ccb1e8-ffffffff81ccb20d: ext4_get_group_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff814bf6b3)
Location: fs/ext4/ext4.h:3314
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff814d75bb)
Location: fs/ext4/ext4.h:3314
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff814fc155)
Location: fs/ext4/ext4.h:3314
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff81529dcc)
Location: fs/ext4/ext4.h:3314
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81557633)
Location: fs/ext4/ext4.h:3327
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81570332)
Location: fs/ext4/ext4.h:3327
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff815968d5)
Location: fs/ext4/ext4.h:3327
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff815c870c)
Location: fs/ext4/ext4.h:3327
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct ext4_group_info *ext4_get_group_info(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:324
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff820ebe5b-ffffffff820ebe7f: ext4_get_group_info.cold (STB_LOCAL)
ffffffff8158ed70-ffffffff8158edfc: ext4_get_group_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct ext4_group_info *ext4_get_group_info(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:326
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init_backend
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
**Symbols:**

```
ffffffff821c90bf-ffffffff821c90e3: ext4_get_group_info.cold (STB_LOCAL)
ffffffff815c7a80-ffffffff815c7b0c: ext4_get_group_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffff800010460254)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffff800010476328)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffff800010497010)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffff8000104bc734)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c0620a94)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (c0637d04)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (c0659264)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (c067fda0)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c00000000057c684)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (c0000000005982c8)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (c0000000005c1478)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (c0000000005f24c4)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffe0002ef8ac)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffe000301c3a)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffe00031ba48)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffe000338470)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813866dd)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff8139b165)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813b89d6)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff813db7ab)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8137716d)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff8138bbf5)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813a9466)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff813cc22b)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813841ad)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff813989c5)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813b6236)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff813d8c4b)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81397d17)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_count_free_clusters
  - fs/ext4/balloc.c:ext4_count_free_clusters
```
```
In fs/ext4/ialloc.c (ffffffff813acdd5)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813caf3e)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_from_pa
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_show
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In fs/ext4/super.c (ffffffff813edefc)
Location: fs/ext4/ext4.h:2934
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_mark_group_bitmap_corrupted
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
