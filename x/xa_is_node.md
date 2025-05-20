# Function: <code>xa_is_node</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0ce3e)
Location: include/linux/xarray.h:1046
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81a17fe7)
Location: include/linux/xarray.h:1046
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
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
In lib/radix-tree.c (ffffffff81a7c7a2)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81a87baa)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
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
In lib/radix-tree.c (ffffffff81ab3ad2)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81abee4a)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
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
In lib/radix-tree.c (ffffffff815edb54)
Location: include/linux/xarray.h:1222
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_free_nodes
```
```
In lib/xarray.c (ffffffff815fb763)
Location: include/linux/xarray.h:1222
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_expand
  - lib/xarray.c:xas_expand
  - lib/xarray.c:xas_expand
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_shrink
  - lib/xarray.c:xas_shrink
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_start
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
In lib/radix-tree.c (ffffffff81612284)
Location: include/linux/xarray.h:1222
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_free_nodes
```
```
In lib/xarray.c (ffffffff816202d3)
Location: include/linux/xarray.h:1222
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_expand
  - lib/xarray.c:xas_expand
  - lib/xarray.c:xas_expand
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_shrink
  - lib/xarray.c:xas_shrink
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_start
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
In lib/radix-tree.c (ffffffff815f59a1)
Location: include/linux/xarray.h:1224
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81603912)
Location: include/linux/xarray.h:1224
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_start
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
In lib/radix-tree.c (ffffffff81662e07)
Location: include/linux/xarray.h:1224
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81672044)
Location: include/linux/xarray.h:1224
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff812f53f5)
Location: include/linux/xarray.h:1225
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813077d4)
Location: include/linux/xarray.h:1225
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/vmscan.c (ffffffff8130cd42)
Location: include/linux/xarray.h:1225
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/workingset.c (ffffffff81335ce7)
Location: include/linux/xarray.h:1225
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/inode.c (ffffffff81417a31)
Location: include/linux/xarray.h:1225
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_add_lru
```
```
In lib/radix-tree.c (ffffffff8177cf83)
Location: include/linux/xarray.h:1225
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff8178c7f8)
Location: include/linux/xarray.h:1225
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff8135f265)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/truncate.c (ffffffff81371944)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/vmscan.c (ffffffff813761f7)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/workingset.c (ffffffff813acae7)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/inode.c (ffffffff814a31d1)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_add_lru
```
```
In lib/maple_tree.c (ffffffff82030999)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mtree_alloc_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_prev_entry
  - lib/maple_tree.c:mas_prev_entry
  - lib/maple_tree.c:mas_next_entry
  - lib/maple_tree.c:mas_next_entry
```
```
In lib/radix-tree.c (ffffffff82039833)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff82049ea8)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff81390384)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813a3a51)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/vmscan.c (ffffffff813a6224)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/workingset.c (ffffffff813e0e95)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/inode.c (ffffffff814d8321)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_add_lru
```
```
In lib/maple_tree.c (ffffffff820ac4b6)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_empty_area
  - lib/maple_tree.c:mas_walk
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
```
```
In lib/radix-tree.c (ffffffff820b7b53)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff820c873a)
Location: include/linux/xarray.h:1240
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_descend
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff813b9dc4)
Location: include/linux/xarray.h:1258
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813cd573)
Location: include/linux/xarray.h:1258
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/vmscan.c (ffffffff813cfd91)
Location: include/linux/xarray.h:1258
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/workingset.c (ffffffff8140b765)
Location: include/linux/xarray.h:1258
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/inode.c (ffffffff8150ab01)
Location: include/linux/xarray.h:1258
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_add_lru
```
```
In lib/maple_tree.c (ffffffff8218db8f)
Location: include/linux/xarray.h:1258
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mas_preallocate
  - lib/maple_tree.c:mas_empty_area_rev
  - lib/maple_tree.c:mas_walk
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
```
```
In lib/radix-tree.c (ffffffff82192463)
Location: include/linux/xarray.h:1258
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff821a30ba)
Location: include/linux/xarray.h:1258
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_descend
  - lib/xarray.c:xas_start
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
In lib/radix-tree.c (ffff800010d8d79c)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffff800010d9acb0)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
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
In lib/radix-tree.c (c0e87d88)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (c0e96dd0)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
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
In lib/radix-tree.c (c000000000ecfde8)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (c000000000ee0344)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
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
In lib/radix-tree.c (ffffffe0008b69f6)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffe0008c2c1a)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
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
In lib/radix-tree.c (ffffffff81a52922)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81a5dc9a)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
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
In lib/radix-tree.c (ffffffff81a0fa22)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81a1ad6a)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
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
In lib/radix-tree.c (ffffffff81abed12)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81aca08a)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
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
In lib/radix-tree.c (ffffffff81acb1d2)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
```
```
In lib/xarray.c (ffffffff81ad661a)
Location: include/linux/xarray.h:1187
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_load
```
</details>
</li>
</ul>

## Differences
