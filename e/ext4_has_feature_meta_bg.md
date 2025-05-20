# Function: <code>ext4_has_feature_meta_bg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8128f8fd)
Location: fs/ext4/ext4.h:1710
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
```
```
In fs/ext4/super.c (0)
Location: fs/ext4/ext4.h:1710
Inline: True
```
```
In fs/ext4/resize.c (ffffffff812bfb38)
Location: fs/ext4/ext4.h:1710
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_resize_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812bcec4)
Location: fs/ext4/ext4.h:1778
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/super.c (0)
Location: fs/ext4/ext4.h:1778
Inline: True
```
```
In fs/ext4/resize.c (ffffffff812f1393)
Location: fs/ext4/ext4.h:1778
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812d2514)
Location: fs/ext4/ext4.h:1763
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/super.c (ffffffff81301c09)
Location: fs/ext4/ext4.h:1763
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff81307363)
Location: fs/ext4/ext4.h:1763
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812e3b94)
Location: fs/ext4/ext4.h:1768
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
```
```
In fs/ext4/fsmap.c (ffffffff812f2b4b)
Location: fs/ext4/ext4.h:1768
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
```
In fs/ext4/resize.c (ffffffff81321e43)
Location: fs/ext4/ext4.h:1768
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
```
```
In fs/ext4/super.c (ffffffff81336abc)
Location: fs/ext4/ext4.h:1768
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81308584)
Location: fs/ext4/ext4.h:1728
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
```
```
In fs/ext4/fsmap.c (ffffffff813170db)
Location: fs/ext4/ext4.h:1728
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
```
In fs/ext4/resize.c (ffffffff81346583)
Location: fs/ext4/ext4.h:1728
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
```
```
In fs/ext4/super.c (ffffffff8135b073)
Location: fs/ext4/ext4.h:1728
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/balloc.c (ffffffff813364ab)
Location: fs/ext4/ext4.h:1731
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff81344e7e)
Location: fs/ext4/ext4.h:1731
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/resize.c (ffffffff813743e7)
Location: fs/ext4/ext4.h:1731
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
```
```
In fs/ext4/super.c (ffffffff813898c7)
Location: fs/ext4/ext4.h:1731
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (ffffffff8134d72b)
Location: fs/ext4/ext4.h:1744
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff8135cfce)
Location: fs/ext4/ext4.h:1744
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/resize.c (ffffffff8138c81c)
Location: fs/ext4/ext4.h:1744
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
```
```
In fs/ext4/super.c (ffffffff813a246e)
Location: fs/ext4/ext4.h:1744
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (ffffffff813760f5)
Location: fs/ext4/ext4.h:1764
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff81386161)
Location: fs/ext4/ext4.h:1764
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/resize.c (ffffffff813b6efa)
Location: fs/ext4/ext4.h:1764
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff813ccd96)
Location: fs/ext4/ext4.h:1764
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (ffffffff8138e365)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff8139ebb1)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/resize.c (ffffffff813cfe20)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff813e625a)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (ffffffff813d988a)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff813ea88a)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_sb
```
```
In fs/ext4/resize.c (ffffffff8141ca8b)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff81433358)
Location: fs/ext4/ext4.h:1918
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (ffffffff813eb53a)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff813fcb3a)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_sb
```
```
In fs/ext4/resize.c (ffffffff8143085d)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff8144c17f)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (ffffffff813f1a7a)
Location: fs/ext4/ext4.h:2052
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff8140297f)
Location: fs/ext4/ext4.h:2052
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
```
In fs/ext4/resize.c (ffffffff8143746b)
Location: fs/ext4/ext4.h:2052
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff81451a89)
Location: fs/ext4/ext4.h:2052
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81443ace)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff8145504f)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
```
In fs/ext4/resize.c (ffffffff8148b0e7)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff814a5107)
Location: fs/ext4/ext4.h:2119
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (ffffffff814bf99e)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff814d2893)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
```
In fs/ext4/resize.c (ffffffff8150eef2)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff8152d09b)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (ffffffff8155794e)
Location: fs/ext4/ext4.h:2131
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff8156b433)
Location: fs/ext4/ext4.h:2131
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
```
In fs/ext4/resize.c (ffffffff815a9d95)
Location: fs/ext4/ext4.h:2131
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff815c930d)
Location: fs/ext4/ext4.h:2131
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:descriptor_loc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8158f685)
Location: fs/ext4/ext4.h:2125
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff815a32e4)
Location: fs/ext4/ext4.h:2125
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
```
In fs/ext4/resize.c (ffffffff815e05f5)
Location: fs/ext4/ext4.h:2125
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff816010cc)
Location: fs/ext4/ext4.h:2125
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:descriptor_loc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff815c8471)
Location: fs/ext4/ext4.h:2143
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_blocks
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff815dc066)
Location: fs/ext4/ext4.h:2143
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
```
In fs/ext4/resize.c (ffffffff816190b1)
Location: fs/ext4/ext4.h:2143
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff81639e1c)
Location: fs/ext4/ext4.h:2143
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_init
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (ffff800010460588)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffff8000104720b8)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/resize.c (ffff8000104a8830)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffff8000104bf558)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (c0620d7c)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (c0633174)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
```
In fs/ext4/resize.c (c066ac04)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (c0683178)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (c00000000057ca74)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (c000000000592cec)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/resize.c (c0000000005d6614)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (c0000000005f5c10)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (ffffffe0002efafc)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffe0002fe0a4)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/resize.c (ffffffe000328dba)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffe00033a824)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (ffffffff81386945)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff81397191)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/resize.c (ffffffff813c8400)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff813de83a)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (ffffffff813773d5)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff81387c21)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/resize.c (ffffffff813b8e80)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff813cf2ba)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (ffffffff81384415)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff81394af1)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/resize.c (ffffffff813c5890)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff813dbbf7)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
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
In fs/ext4/balloc.c (ffffffff81397f95)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_num_base_meta_clusters
  - fs/ext4/balloc.c:ext4_bg_num_gdb
  - fs/ext4/balloc.c:ext4_bg_num_gdb
```
```
In fs/ext4/fsmap.c (ffffffff813a8be1)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
```
In fs/ext4/resize.c (ffffffff813daac0)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
```
In fs/ext4/super.c (ffffffff813f0faa)
Location: fs/ext4/ext4.h:1821
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:descriptor_loc
```
</details>
</li>
</ul>

## Differences
