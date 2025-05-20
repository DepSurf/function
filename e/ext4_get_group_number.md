# Function: <code>ext4_get_group_number</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8128f340)
Location: fs/ext4/balloc.c:34
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
Direct callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_discard_preallocations
```
**Symbols:**

```
ffffffff8128f340-ffffffff8128f383: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812bd440)
Location: fs/ext4/balloc.c:34
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
```
**Symbols:**

```
ffffffff812bc850-ffffffff812bc892: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812d2a90)
Location: fs/ext4/balloc.c:34
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
```
**Symbols:**

```
ffffffff812d1ea0-ffffffff812d1ee2: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812e410f)
Location: fs/ext4/balloc.c:34
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
**Symbols:**

```
ffffffff812e3520-ffffffff812e355c: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81308a2a)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
**Symbols:**

```
ffffffff81307f10-ffffffff81307f4c: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813369b9)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
**Symbols:**

```
ffffffff81335e00-ffffffff81335e3c: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8134dc39)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
**Symbols:**

```
ffffffff8134d080-ffffffff8134d0bc: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81376618)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
**Symbols:**

```
ffffffff81375a60-ffffffff81375a9c: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8138e888)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
**Symbols:**

```
ffffffff8138dcd0-ffffffff8138dd0c: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813d9c5d)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
**Symbols:**

```
ffffffff813d91d0-ffffffff813d920c: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813eb90d)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
**Symbols:**

```
ffffffff813eae20-ffffffff813eae5c: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813f1e4d)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
**Symbols:**

```
ffffffff813f1350-ffffffff813f138c: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:35
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
**Symbols:**

```
ffffffff81cc8aaf-ffffffff81cc8aee: ext4_get_group_number.cold (STB_LOCAL)
ffffffff81443310-ffffffff81443366: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:35
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
**Symbols:**

```
ffffffff81e7b7f3-ffffffff81e7b832: ext4_get_group_number.cold (STB_LOCAL)
ffffffff814bf0f0-ffffffff814bf15e: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:35
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
**Symbols:**

```
ffffffff8206bf84-ffffffff8206bfc3: ext4_get_group_number.cold (STB_LOCAL)
ffffffff81557000-ffffffff8155706e: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:35
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
**Symbols:**

```
ffffffff820ebdd1-ffffffff820ebe10: ext4_get_group_number.cold (STB_LOCAL)
ffffffff8158eb50-ffffffff8158ebbe: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/balloc.c (0)
Location: fs/ext4/balloc.c:36
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/ioctl.c:ext4_update_superblocks_fn
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
**Symbols:**

```
ffffffff821c9035-ffffffff821c9074: ext4_get_group_number.cold (STB_LOCAL)
ffffffff815c7860-ffffffff815c78ce: ext4_get_group_number (STB_GLOBAL)
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
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffff800010460c3c)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
**Symbols:**

```
ffff80001045fd20-ffff80001045fd88: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c062057c)
Location: fs/ext4/balloc.c:35
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
**Symbols:**

```
c062057c-c0620630: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c00000000057d1b4)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
**Symbols:**

```
c00000000057c070-c00000000057c0c0: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffe0002effa6)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
**Symbols:**

```
ffffffe0002ef444-ffffffe0002ef4a6: ext4_get_group_number (STB_GLOBAL)
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
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81386e68)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
**Symbols:**

```
ffffffff813862b0-ffffffff813862ec: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813778f8)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
**Symbols:**

```
ffffffff81376d40-ffffffff81376d7c: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81384938)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
**Symbols:**

```
ffffffff81383d80-ffffffff81383dbc: ext4_get_group_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ext4_group_t ext4_get_group_number(struct super_block *sb, ext4_fsblk_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813984b3)
Location: fs/ext4/balloc.c:35
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
**Symbols:**

```
ffffffff813978a0-ffffffff813978dc: ext4_get_group_number (STB_GLOBAL)
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
