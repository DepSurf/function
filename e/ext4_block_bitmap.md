# Function: <code>ext4_block_bitmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b7b30)
Location: fs/ext4/super.c:175
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_fill_super
Direct callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff812b7b30-ffffffff812b7b56: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ebeed)
Location: fs/ext4/super.c:204
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff812e6830-ffffffff812e6856: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81301eae)
Location: fs/ext4/super.c:206
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff812fc3e0-ffffffff812fc406: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81336dd2)
Location: fs/ext4/super.c:208
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff81331030-ffffffff81331054: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8135b374)
Location: fs/ext4/super.c:208
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff813554f0-ffffffff81355514: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81389bca)
Location: fs/ext4/super.c:208
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff81383920-ffffffff81383944: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813a2745)
Location: fs/ext4/super.c:231
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff8139c400-ffffffff8139c424: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813cb6e1)
Location: fs/ext4/super.c:232
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff813c6650-ffffffff813c6674: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e4aa1)
Location: fs/ext4/super.c:227
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff813dfa10-ffffffff813dfa34: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8142cd03)
Location: fs/ext4/super.c:207
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff8142c2d0-ffffffff8142c2f4: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81445b03)
Location: fs/ext4/super.c:296
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff814450f0-ffffffff81445114: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144b3d8)
Location: fs/ext4/super.c:296
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff8144aa10-ffffffff8144aa34: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8149f35f)
Location: fs/ext4/super.c:293
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff8149e920-ffffffff8149e944: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81525c04)
Location: fs/ext4/super.c:312
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
**Symbols:**

```
ffffffff81525020-ffffffff8152504e: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c3324)
Location: fs/ext4/super.c:306
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
**Symbols:**

```
ffffffff815c2510-ffffffff815c253e: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815faa74)
Location: fs/ext4/super.c:306
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
**Symbols:**

```
ffffffff815f9c90-ffffffff815f9cbe: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81633654)
Location: fs/ext4/super.c:314
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
**Symbols:**

```
ffffffff81632890-ffffffff816328be: ext4_block_bitmap (STB_GLOBAL)
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
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104bdf48)
Location: fs/ext4/super.c:227
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffff8000104b8838-ffff8000104b887c: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0681748)
Location: fs/ext4/super.c:227
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
c067c028-c067c05c: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f42a4)
Location: fs/ext4/super.c:227
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
c0000000005eda20-c0000000005eda4c: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe0003399de)
Location: fs/ext4/super.c:227
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffe00033525c-ffffffe00033529c: ext4_block_bitmap (STB_GLOBAL)
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
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813dd081)
Location: fs/ext4/super.c:227
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff813d7ff0-ffffffff813d8014: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813cdb01)
Location: fs/ext4/super.c:227
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff813c8a70-ffffffff813c8a94: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813da521)
Location: fs/ext4/super.c:227
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff813d5480-ffffffff813d54a4: ext4_block_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block *sb, struct ext4_group_desc *bg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ef801)
Location: fs/ext4/super.c:227
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff813ea700-ffffffff813ea724: ext4_block_bitmap (STB_GLOBAL)
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
