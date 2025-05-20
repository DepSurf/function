# Function: <code>xa_to_internal</code>

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
In fs/dax.c (ffffffff8130d57b)
Location: include/linux/xarray.h:149
Inline: True
```
```
In lib/xarray.c (ffffffff81a17e99)
Location: include/linux/xarray.h:149
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
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
In fs/dax.c (ffffffff8133578c)
Location: include/linux/xarray.h:155
Inline: True
```
```
In lib/xarray.c (ffffffff81a87a62)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
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
In fs/dax.c (ffffffff8134938c)
Location: include/linux/xarray.h:155
Inline: True
```
```
In lib/xarray.c (ffffffff81abed02)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
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
In fs/dax.c (ffffffff8138f715)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In lib/xarray.c (ffffffff815fb265)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff8125a2b1)
Location: include/linux/xarray.h:155
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
In fs/dax.c (ffffffff813a0d73)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In lib/xarray.c (ffffffff8161fdce)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff8125e15e)
Location: include/linux/xarray.h:155
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
In fs/dax.c (ffffffff813a7f02)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In lib/iov_iter.c (ffffffff815ab2ad)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/xarray.c (ffffffff8160354e)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff8129a999)
Location: include/linux/xarray.h:155
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
In fs/dax.c (ffffffff813f756c)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In lib/iov_iter.c (ffffffff81614ce4)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/xarray.c (ffffffff81671f21)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff812f15c6)
Location: include/linux/xarray.h:156
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
  - mm/filemap.c:__filemap_get_folio
```
```
In fs/dax.c (ffffffff8146a353)
Location: include/linux/xarray.h:156
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In lib/iov_iter.c (ffffffff816e199c)
Location: include/linux/xarray.h:156
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/xarray.c (ffffffff8178c6db)
Location: include/linux/xarray.h:156
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff8135bf66)
Location: include/linux/xarray.h:157
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
```
```
In fs/dax.c (ffffffff814fae00)
Location: include/linux/xarray.h:157
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In lib/iov_iter.c (ffffffff817d2635)
Location: include/linux/xarray.h:157
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/xarray.c (ffffffff82049d7b)
Location: include/linux/xarray.h:157
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff8138e250)
Location: include/linux/xarray.h:157
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
```
```
In fs/dax.c (ffffffff81532253)
Location: include/linux/xarray.h:157
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In lib/iov_iter.c (ffffffff81810d32)
Location: include/linux/xarray.h:157
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/xarray.c (ffffffff820c61cf)
Location: include/linux/xarray.h:157
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
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
In mm/filemap.c (ffffffff813b919d)
Location: include/linux/xarray.h:157
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
```
```
In fs/dax.c (ffffffff81567143)
Location: include/linux/xarray.h:157
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In lib/iov_iter.c (ffffffff8185715f)
Location: include/linux/xarray.h:157
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
```
```
In lib/xarray.c (ffffffff821a0b4f)
Location: include/linux/xarray.h:157
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
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
In fs/dax.c (0)
Location: include/linux/xarray.h:155
Inline: True
```
```
In lib/xarray.c (ffff800010d99d10)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
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
Location: include/linux/xarray.h:155
Inline: True
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
In fs/dax.c (c000000000515f30)
Location: include/linux/xarray.h:155
Inline: True
```
```
In lib/xarray.c (c000000000edfd88)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
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
In fs/dax.c (0)
Location: include/linux/xarray.h:155
Inline: True
```
```
In lib/xarray.c (0)
Location: include/linux/xarray.h:155
Inline: True
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
In fs/dax.c (ffffffff8134196c)
Location: include/linux/xarray.h:155
Inline: True
```
```
In lib/xarray.c (ffffffff81a5db52)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
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
In fs/dax.c (ffffffff8133242c)
Location: include/linux/xarray.h:155
Inline: True
```
```
In lib/xarray.c (ffffffff81a1ac22)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
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
In fs/dax.c (ffffffff8133f43c)
Location: include/linux/xarray.h:155
Inline: True
```
```
In lib/xarray.c (ffffffff81ac9f42)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
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
In fs/dax.c (ffffffff813525da)
Location: include/linux/xarray.h:155
Inline: True
```
```
In lib/xarray.c (ffffffff81ad64c6)
Location: include/linux/xarray.h:155
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
</details>
</li>
</ul>

## Differences
