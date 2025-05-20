# Function: <code>ext4_bg_has_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8128f780)
Location: fs/ext4/balloc.c:746
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff8128f780-ffffffff8128f8d0: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812bccb0)
Location: fs/ext4/balloc.c:752
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff812bccb0-ffffffff812bce00: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812d2300)
Location: fs/ext4/balloc.c:752
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff812d2300-ffffffff812d2450: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812e3990)
Location: fs/ext4/balloc.c:752
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff812e3990-ffffffff812e3ae0: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81308380)
Location: fs/ext4/balloc.c:752
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff81308380-ffffffff813084d0: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81336280)
Location: fs/ext4/balloc.c:761
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff81336280-ffffffff813363d4: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8134d500)
Location: fs/ext4/balloc.c:761
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff8134d500-ffffffff8134d654: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81375f00)
Location: fs/ext4/balloc.c:761
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff81375f00-ffffffff81376025: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8138e170)
Location: fs/ext4/balloc.c:769
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff8138e170-ffffffff8138e295: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813d9690)
Location: fs/ext4/balloc.c:771
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_sb
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff813d9690-ffffffff813d97b5: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813eb340)
Location: fs/ext4/balloc.c:797
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_sb
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff813eb340-ffffffff813eb465: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813f1870)
Location: fs/ext4/balloc.c:797
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff813f1870-ffffffff813f19a7: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff814438c0)
Location: fs/ext4/balloc.c:803
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff814438c0-ffffffff814439f7: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff814bf760)
Location: fs/ext4/balloc.c:804
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff814bf760-ffffffff814bf89c: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff815576f0)
Location: fs/ext4/balloc.c:804
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff815576f0-ffffffff8155782c: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8158f510)
Location: fs/ext4/balloc.c:846
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff8158f510-ffffffff8158f64e: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff815c8220)
Location: fs/ext4/balloc.c:854
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_blocks
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff815c8220-ffffffff815c835e: ext4_bg_has_super (STB_GLOBAL)
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
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffff8000104602d8)
Location: fs/ext4/balloc.c:769
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffff8000104602d8-ffff800010460474: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c0620b04)
Location: fs/ext4/balloc.c:769
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
c0620b04-c0620c94: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c00000000057c760)
Location: fs/ext4/balloc.c:769
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
c00000000057c760-c00000000057c918: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffe0002ef914)
Location: fs/ext4/balloc.c:769
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffe0002ef914-ffffffe0002efa2a: ext4_bg_has_super (STB_GLOBAL)
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
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81386750)
Location: fs/ext4/balloc.c:769
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff81386750-ffffffff81386875: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813771e0)
Location: fs/ext4/balloc.c:769
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff813771e0-ffffffff81377305: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81384220)
Location: fs/ext4/balloc.c:769
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff81384220-ffffffff81384345: ext4_bg_has_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_bg_has_super(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81397da0)
Location: fs/ext4/balloc.c:769
Inline: True
Direct callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_group_overhead_blocks
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:descriptor_loc
```
**Symbols:**

```
ffffffff81397da0-ffffffff81397ec5: ext4_bg_has_super (STB_GLOBAL)
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
