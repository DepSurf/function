# Function: <code>filemap_alloc_folio</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct folio *filemap_alloc_folio(gfp_t gfp, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812ef580)
Location: mm/filemap.c:981
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:__filemap_get_folio
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
**Symbols:**

```
ffffffff812ef580-ffffffff812ef623: filemap_alloc_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct folio *filemap_alloc_folio(gfp_t gfp, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8135a080)
Location: mm/filemap.c:957
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:__filemap_get_folio
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
**Symbols:**

```
ffffffff8135a080-ffffffff8135a16e: filemap_alloc_folio.part.0 (STB_LOCAL)
ffffffff8135a180-ffffffff8135a1bb: filemap_alloc_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct folio *filemap_alloc_folio(gfp_t gfp, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138bad0)
Location: mm/filemap.c:964
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:__filemap_get_folio
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
**Symbols:**

```
ffffffff8138bad0-ffffffff8138bbcb: filemap_alloc_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct folio *filemap_alloc_folio(gfp_t gfp, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b5640)
Location: mm/filemap.c:960
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:__filemap_get_folio
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_order
  - mm/readahead.c:page_cache_ra_unbounded
```
**Symbols:**

```
ffffffff813b5640-ffffffff813b573b: filemap_alloc_folio (STB_GLOBAL)
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
