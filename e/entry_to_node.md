# Function: <code>entry_to_node</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a187e)
Location: include/linux/radix-tree.h:449
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/shmem.c (ffffffff811bf708)
Location: include/linux/radix-tree.h:449
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811c8cde)
Location: include/linux/radix-tree.h:449
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8121c82a)
Location: include/linux/radix-tree.h:449
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff812623a8)
Location: include/linux/radix-tree.h:449
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/radix-tree.c (ffffffff81435985)
Location: include/linux/radix-tree.h:449
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/radix-tree.c:radix_tree_locate_item
  - lib/radix-tree.c:radix_tree_locate_item
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_range_tag_if_tagged
  - lib/radix-tree.c:radix_tree_range_tag_if_tagged
  - lib/radix-tree.c:radix_tree_range_tag_if_tagged
  - lib/radix-tree.c:radix_tree_range_tag_if_tagged
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81450a68)
Location: lib/radix-tree.c:72
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff818f2b73)
Location: lib/radix-tree.c:90
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81978fdd)
Location: lib/radix-tree.c:90
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free_cmn
  - lib/radix-tree.c:idr_get_free_cmn
  - lib/radix-tree.c:idr_get_free_cmn
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d568d)
Location: lib/radix-tree.c:91
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0ce25)
Location: lib/radix-tree.c:89
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a7c78d)
Location: lib/radix-tree.c:76
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81ab3abd)
Location: lib/radix-tree.c:76
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815eeece)
Location: lib/radix-tree.c:68
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8161361e)
Location: lib/radix-tree.c:68
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff815f598b)
Location: lib/radix-tree.c:68
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81662deb)
Location: lib/radix-tree.c:68
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff8177cf67)
Location: lib/radix-tree.c:68
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82039817)
Location: lib/radix-tree.c:68
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff820b7b37)
Location: lib/radix-tree.c:67
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff82192447)
Location: lib/radix-tree.c:67
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffff800010d8d774)
Location: lib/radix-tree.c:76
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c0e87d54)
Location: lib/radix-tree.c:76
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (c000000000ecfda0)
Location: lib/radix-tree.c:76
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffe0008b69ee)
Location: lib/radix-tree.c:76
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a5290d)
Location: lib/radix-tree.c:76
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81a0fa0d)
Location: lib/radix-tree.c:76
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81abecfd)
Location: lib/radix-tree.c:76
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81acb1bd)
Location: lib/radix-tree.c:76
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
</ul>

## Differences
