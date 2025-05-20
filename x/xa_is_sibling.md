# Function: <code>xa_is_sibling</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a17e84)
Location: include/linux/xarray.h:1069
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff81a87a4d)
Location: include/linux/xarray.h:1210
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff81abeced)
Location: include/linux/xarray.h:1210
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff815fb251)
Location: include/linux/xarray.h:1245
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In mm/filemap.c (ffffffff8125a181)
Location: include/linux/xarray.h:1245
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In lib/xarray.c (ffffffff8161fdba)
Location: include/linux/xarray.h:1245
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff8125e14a)
Location: include/linux/xarray.h:1247
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
```
```
In lib/iov_iter.c (ffffffff815ab299)
Location: include/linux/xarray.h:1247
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/xarray.c (ffffffff8160353a)
Location: include/linux/xarray.h:1247
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff8129a881)
Location: include/linux/xarray.h:1247
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
```
```
In lib/iov_iter.c (ffffffff81614c2d)
Location: include/linux/xarray.h:1247
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/xarray.c (ffffffff81671ef5)
Location: include/linux/xarray.h:1247
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
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
In mm/filemap.c (ffffffff812f14ce)
Location: include/linux/xarray.h:1248
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
```
```
In lib/iov_iter.c (ffffffff816e18bb)
Location: include/linux/xarray.h:1248
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/xarray.c (ffffffff8178c6ac)
Location: include/linux/xarray.h:1248
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
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
In mm/filemap.c (ffffffff8135be6e)
Location: include/linux/xarray.h:1263
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
```
```
In lib/iov_iter.c (ffffffff817d255b)
Location: include/linux/xarray.h:1263
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/xarray.c (ffffffff82049d4c)
Location: include/linux/xarray.h:1263
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
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
In mm/filemap.c (ffffffff8138e14d)
Location: include/linux/xarray.h:1263
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
```
```
In lib/iov_iter.c (ffffffff81810c5c)
Location: include/linux/xarray.h:1263
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/xarray.c (ffffffff820c719b)
Location: include/linux/xarray.h:1263
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
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
In mm/filemap.c (ffffffff813b90a3)
Location: include/linux/xarray.h:1281
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
```
```
In lib/iov_iter.c (ffffffff8185708c)
Location: include/linux/xarray.h:1281
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/xarray.c (ffffffff821a1b1b)
Location: include/linux/xarray.h:1281
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_order
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d99cf8)
Location: include/linux/xarray.h:1210
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (0)
Location: include/linux/xarray.h:1210
Inline: True
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
In lib/xarray.c (c000000000edfd6c)
Location: include/linux/xarray.h:1210
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (0)
Location: include/linux/xarray.h:1210
Inline: True
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
In lib/xarray.c (ffffffff81a5db3d)
Location: include/linux/xarray.h:1210
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff81a1ac0d)
Location: include/linux/xarray.h:1210
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff81ac9f2d)
Location: include/linux/xarray.h:1210
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff81ad64b1)
Location: include/linux/xarray.h:1210
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_find
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
</details>
</li>
</ul>

## Differences
