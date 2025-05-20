# Function: <code>ext4_es_type</code>

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
In fs/ext4/inode.c (ffffffff81296ead)
Location: fs/ext4/extents_status.h:103
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/extents_status.c (ffffffff812dad66)
Location: fs/ext4/extents_status.h:103
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
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
In fs/ext4/file.c (0)
Location: fs/ext4/extents_status.h:103
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812c44d0)
Location: fs/ext4/extents_status.h:103
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/extents_status.c (ffffffff8130abfa)
Location: fs/ext4/extents_status.h:103
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
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
In fs/ext4/file.c (0)
Location: fs/ext4/extents_status.h:103
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812d9b80)
Location: fs/ext4/extents_status.h:103
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/extents_status.c (ffffffff81320bfa)
Location: fs/ext4/extents_status.h:103
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
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
In fs/ext4/extents_status.c (ffffffff812efba2)
Location: fs/ext4/extents_status.h:103
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/file.c (0)
Location: fs/ext4/extents_status.h:103
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812fda9d)
Location: fs/ext4/extents_status.h:103
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
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
In fs/ext4/extents_status.c (ffffffff813146a2)
Location: fs/ext4/extents_status.h:104
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff8132227d)
Location: fs/ext4/extents_status.h:104
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
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
In fs/ext4/extents_status.c (ffffffff8134251a)
Location: fs/ext4/extents_status.h:104
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/ext4/inode.c (ffffffff8135136d)
Location: fs/ext4/extents_status.h:104
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
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
In fs/ext4/extents.c (ffffffff81350420)
Location: fs/ext4/extents_status.h:156
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_es_is_delayed
```
```
In fs/ext4/extents_status.c (ffffffff8135b62c)
Location: fs/ext4/extents_status.h:156
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff8136a20d)
Location: fs/ext4/extents_status.h:156
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffff813790e0)
Location: fs/ext4/extents_status.h:156
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_es_is_delayed
```
```
In fs/ext4/extents_status.c (ffffffff81384646)
Location: fs/ext4/extents_status.h:156
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813941cd)
Location: fs/ext4/extents_status.h:156
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffff81391791)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff8139d2c6)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813acb61)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffff813dd26d)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813e6e82)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff813f8e14)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffff813eeb5d)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813f9142)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff8140b4a9)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffff813fd469)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
```
```
In fs/ext4/extents_status.c (ffffffff8140108e)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff81411661)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffff814473d0)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff814513ce)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff81464437)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffff814c3a5a)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff814ceb37)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff814e3bb5)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffff8155bd9a)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff815673a7)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff8157d0b5)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffff81593bb0)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff8159f577)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff815b4485)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffff815cc8a0)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff815d80c7)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff815ed293)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffff800010464334)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffff8000104704e8)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffff800010481344)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (c062538c)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (c0631904)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:count_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (c06423f4)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (c000000000582588)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (c000000000590b7c)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:count_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (c0000000005a5890)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffe0002f321e)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffe0002fcc04)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:count_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffe000309fc8)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffff81389d71)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813958a6)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813a5141)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffff8137a801)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81386336)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff81395bd1)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffff813876d1)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81393206)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813a29a1)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
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
In fs/ext4/extents.c (ffffffff8139b3b1)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813a7299)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813b7081)
Location: fs/ext4/extents_status.h:157
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
  - fs/ext4/inode.c:ext4_es_is_mapped
```
</details>
</li>
</ul>

## Differences
