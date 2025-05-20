# Function: <code>xas_nomem</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a17c40)
Location: lib/xarray.c:290
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff81a17c40-ffffffff81a17c96: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a878f0)
Location: lib/xarray.c:295
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff81a878f0-ffffffff81a87957: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abeb90)
Location: lib/xarray.c:296
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff81abeb90-ffffffff81abebf7: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fa620)
Location: lib/xarray.c:296
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff815fa620-ffffffff815fa68d: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161ee10)
Location: lib/xarray.c:297
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff8161ee10-ffffffff8161ee8d: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81602460)
Location: lib/xarray.c:297
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff81602460-ffffffff816024dd: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81670010)
Location: lib/xarray.c:297
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff81670010-ffffffff8167008d: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178b740)
Location: lib/xarray.c:300
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff8178b740-ffffffff8178b7db: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820496a0)
Location: lib/xarray.c:300
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff820496a0-ffffffff8204973b: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c8100)
Location: lib/xarray.c:298
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff820c8100-ffffffff820c819b: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a2a80)
Location: lib/xarray.c:298
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff821a2a80-ffffffff821a2b1b: xas_nomem (STB_GLOBAL)
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
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d99f10)
Location: lib/xarray.c:296
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffff800010d99f10-ffff800010d99fa4: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e96a54)
Location: lib/xarray.c:296
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
c0e96a54-c0e96ae0: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee0060)
Location: lib/xarray.c:296
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
c000000000ee0060-c000000000ee0148: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c2a60)
Location: lib/xarray.c:296
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
ffffffe0008c2a60-ffffffe0008c2ace: xas_nomem (STB_GLOBAL)
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
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5d9e0)
Location: lib/xarray.c:296
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff81a5d9e0-ffffffff81a5da47: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1aab0)
Location: lib/xarray.c:296
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff81a1aab0-ffffffff81a1ab17: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac9dd0)
Location: lib/xarray.c:296
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff81ac9dd0-ffffffff81ac9e37: xas_nomem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad6340)
Location: lib/xarray.c:296
Inline: True
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:grab_mapping_entry
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xa_store_range
```
**Symbols:**

```
ffffffff81ad6340-ffffffff81ad63a7: xas_nomem (STB_GLOBAL)
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
