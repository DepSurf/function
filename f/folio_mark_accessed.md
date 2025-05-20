# Function: <code>folio_mark_accessed</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void folio_mark_accessed(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81305a80)
Location: mm/swap.c:418
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:__filemap_get_folio
  - mm/folio-compat.c:mark_page_accessed
  - mm/folio-compat.c:mark_page_accessed
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_folio
  - fs/iomap/buffered-io.c:iomap_zero_range
```
**Symbols:**

```
ffffffff81305a80-ffffffff81305b9b: folio_mark_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void folio_mark_accessed(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81370970)
Location: mm/swap.c:488
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:__filemap_get_folio
  - mm/folio-compat.c:mark_page_accessed
  - mm/folio-compat.c:mark_page_accessed
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - fs/iomap/buffered-io.c:iomap_zero_range
```
**Symbols:**

```
ffffffff81370970-ffffffff81370a93: folio_mark_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void folio_mark_accessed(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813a2b40)
Location: mm/swap.c:458
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:__filemap_get_folio
  - mm/folio-compat.c:mark_page_accessed
  - mm/folio-compat.c:mark_page_accessed
  - mm/folio-compat.c:mark_page_accessed
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - fs/iomap/buffered-io.c:iomap_zero_range
```
**Symbols:**

```
ffffffff813a2b40-ffffffff813a2c76: folio_mark_accessed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void folio_mark_accessed(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813cc7c0)
Location: mm/swap.c:458
Inline: False
Direct callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:filemap_read
  - mm/filemap.c:__filemap_get_folio
  - mm/folio-compat.c:mark_page_accessed
  - mm/folio-compat.c:mark_page_accessed
  - mm/folio-compat.c:mark_page_accessed
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/memory.c:zap_pte_range
  - fs/iomap/buffered-io.c:iomap_zero_range
  - drivers/gpu/drm/drm_gem.c:drm_gem_put_pages
```
**Symbols:**

```
ffffffff813cc7c0-ffffffff813cc8f9: folio_mark_accessed (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
