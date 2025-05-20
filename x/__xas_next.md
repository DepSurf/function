# Function: <code>__xas_next</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a172c0)
Location: lib/xarray.c:1009
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff81a172c0-ffffffff81a17390: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a86f50)
Location: lib/xarray.c:1028
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff81a86f50-ffffffff81a87020: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abe1d0)
Location: lib/xarray.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81abe1d0-ffffffff81abe2a1: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815faa10)
Location: lib/xarray.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff815faa10-ffffffff815faaeb: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161f210)
Location: lib/xarray.c:1183
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8161f210-ffffffff8161f2eb: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81602860)
Location: lib/xarray.c:1184
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
```
**Symbols:**

```
ffffffff81602860-ffffffff81602932: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1184
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
```
**Symbols:**

```
ffffffff81cdff0d-ffffffff81cdff61: __xas_next.cold (STB_LOCAL)
ffffffff81670c60-ffffffff81670daf: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1191
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
```
**Symbols:**

```
ffffffff81ea6689-ffffffff81ea66dd: __xas_next.cold (STB_LOCAL)
ffffffff8178b7e0-ffffffff8178b928: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1191
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
```
**Symbols:**

```
ffffffff820b7df1-ffffffff820b7e45: __xas_next.cold (STB_LOCAL)
ffffffff82048b60-ffffffff82048ca8: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1189
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
```
**Symbols:**

```
ffffffff8213925d-ffffffff821392b1: __xas_next.cold (STB_LOCAL)
ffffffff820c73f0-ffffffff820c7538: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1189
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:folio_migrate_mapping
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - lib/iov_iter.c:iter_xarray_populate_pages
  - lib/iov_iter.c:iter_xarray_populate_pages
```
**Symbols:**

```
ffffffff8221b002-ffffffff8221b056: __xas_next.cold (STB_LOCAL)
ffffffff821a1d70-ffffffff821a1eb8: __xas_next (STB_GLOBAL)
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
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d99460)
Location: lib/xarray.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffff800010d99460-ffff800010d99560: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e95eec)
Location: lib/xarray.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
**Symbols:**

```
c0e95eec-c0e95ffc: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000edf1d0)
Location: lib/xarray.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
c000000000edf1d0-c000000000edf2e0: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c2448)
Location: lib/xarray.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
**Symbols:**

```
ffffffe0008c2448-ffffffe0008c2508: __xas_next (STB_GLOBAL)
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
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5d020)
Location: lib/xarray.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81a5d020-ffffffff81a5d0f1: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1a0f0)
Location: lib/xarray.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81a1a0f0-ffffffff81a1a1c1: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac9410)
Location: lib/xarray.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81ac9410-ffffffff81ac94e1: __xas_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__xas_next(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad58e0)
Location: lib/xarray.c:1033
Inline: False
Direct callers:
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:page_cache_next_miss
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/migrate.c:migrate_page_move_mapping
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81ad58e0-ffffffff81ad59b1: __xas_next (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
