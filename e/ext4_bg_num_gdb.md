# Function: <code>ext4_bg_num_gdb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8128f8d0)
Location: fs/ext4/balloc.c:802
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff8128f8d0-ffffffff8128f958: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812bce00)
Location: fs/ext4/balloc.c:808
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff812bce00-ffffffff812bce93: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812d2450)
Location: fs/ext4/balloc.c:808
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff812d2450-ffffffff812d24e3: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812e3ae0)
Location: fs/ext4/balloc.c:808
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff812e3ae0-ffffffff812e3b6f: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813084d0)
Location: fs/ext4/balloc.c:808
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff813084d0-ffffffff8130855f: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813363e0)
Location: fs/ext4/balloc.c:817
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff813363e0-ffffffff81336471: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8134d660)
Location: fs/ext4/balloc.c:817
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff8134d660-ffffffff8134d6f1: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81376030)
Location: fs/ext4/balloc.c:817
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff81376030-ffffffff813760c9: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8138e2a0)
Location: fs/ext4/balloc.c:825
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff8138e2a0-ffffffff8138e339: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813d97c0)
Location: fs/ext4/balloc.c:827
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_sb
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff813d97c0-ffffffff813d985e: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813eb470)
Location: fs/ext4/balloc.c:853
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_sb
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff813eb470-ffffffff813eb50e: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813f19b0)
Location: fs/ext4/balloc.c:853
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff813f19b0-ffffffff813f1a4e: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81443a00)
Location: fs/ext4/balloc.c:859
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff81443a00-ffffffff81443a9e: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff814bf8a0)
Location: fs/ext4/balloc.c:860
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff814bf8a0-ffffffff814bf968: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81557840)
Location: fs/ext4/balloc.c:860
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff81557840-ffffffff81557908: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff815900b0)
Location: fs/ext4/balloc.c:902
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff815900b0-ffffffff81590178: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff815c8370)
Location: fs/ext4/balloc.c:910
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff815c8370-ffffffff815c8438: ext4_bg_num_gdb (STB_GLOBAL)
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
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffff800010460478)
Location: fs/ext4/balloc.c:825
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffff800010460478-ffff800010460550: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c0620c94)
Location: fs/ext4/balloc.c:825
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
c0620c94-c0620d48: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c00000000057c920)
Location: fs/ext4/balloc.c:825
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
c00000000057c920-c00000000057ca30: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffe0002efa2a)
Location: fs/ext4/balloc.c:825
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffe0002efa2a-ffffffe0002efacc: ext4_bg_num_gdb (STB_GLOBAL)
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
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81386880)
Location: fs/ext4/balloc.c:825
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff81386880-ffffffff81386919: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81377310)
Location: fs/ext4/balloc.c:825
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff81377310-ffffffff813773a9: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81384350)
Location: fs/ext4/balloc.c:825
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff81384350-ffffffff813843e9: ext4_bg_num_gdb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int ext4_bg_num_gdb(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81397ed0)
Location: fs/ext4/balloc.c:825
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_check_descriptors
```
**Symbols:**

```
ffffffff81397ed0-ffffffff81397f69: ext4_bg_num_gdb (STB_GLOBAL)
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
