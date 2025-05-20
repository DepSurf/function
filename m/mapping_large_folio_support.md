# Function: <code>mapping_large_folio_support</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f1dbd)
Location: include/linux/pagemap.h:313
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/readahead.c (ffffffff81301be1)
Location: include/linux/pagemap.h:313
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
```
```
In mm/huge_memory.c (ffffffff813bfd55)
Location: include/linux/pagemap.h:313
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff813c5b20)
Location: include/linux/pagemap.h:313
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/iomap/buffered-io.c (ffffffff8148b194)
Location: include/linux/pagemap.h:313
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
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
In mm/filemap.c (ffffffff8135999c)
Location: include/linux/pagemap.h:313
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/readahead.c (ffffffff8136c350)
Location: include/linux/pagemap.h:313
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
```
```
In mm/huge_memory.c (ffffffff81442058)
Location: include/linux/pagemap.h:313
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8144a4db)
Location: include/linux/pagemap.h:313
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/iomap/buffered-io.c (ffffffff8151f1cc)
Location: include/linux/pagemap.h:313
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
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
In mm/filemap.c (ffffffff8138b2ec)
Location: include/linux/pagemap.h:317
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/readahead.c (ffffffff8139e560)
Location: include/linux/pagemap.h:317
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
```
```
In mm/huge_memory.c (ffffffff8147795e)
Location: include/linux/pagemap.h:317
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8147ffdc)
Location: include/linux/pagemap.h:317
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/iomap/buffered-io.c (ffffffff815572f7)
Location: include/linux/pagemap.h:317
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
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
In mm/filemap.c (ffffffff813bac08)
Location: include/linux/pagemap.h:367
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/readahead.c (ffffffff813c81fe)
Location: include/linux/pagemap.h:367
Inline: True
Inline callers:
  - mm/readahead.c:page_cache_ra_order
```
```
In mm/huge_memory.c (ffffffff814a714d)
Location: include/linux/pagemap.h:367
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff814adbed)
Location: include/linux/pagemap.h:367
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/iomap/buffered-io.c (ffffffff8158d827)
Location: include/linux/pagemap.h:367
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_begin
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
