# Function: <code>__page_cache_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118d5d0)
Location: mm/filemap.c:708
Inline: True
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:filemap_fault
  - mm/readahead.c:__do_page_cache_readahead
  - fs/splice.c:__generic_file_splice_read
```
**Symbols:**

```
ffffffff8118d5d0-ffffffff8118d686: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a01b0)
Location: mm/filemap.c:748
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
  - fs/splice.c:__generic_file_splice_read
```
**Symbols:**

```
ffffffff811a01b0-ffffffff811a0283: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811af5f0)
Location: mm/filemap.c:712
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff811af5f0-ffffffff811af6c3: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b64f0)
Location: mm/filemap.c:830
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff811b64f0-ffffffff811b657f: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ca860)
Location: mm/filemap.c:931
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff811ca860-ffffffff811ca8f7: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eb8b0)
Location: mm/filemap.c:931
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff811eb8b0-ffffffff811eb944: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fc430)
Location: mm/filemap.c:909
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff811fc430-ffffffff811fc4c4: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81213af0)
Location: mm/filemap.c:957
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff81213af0-ffffffff81213b7d: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812212c0)
Location: mm/filemap.c:966
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff812212c0-ffffffff8122134d: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff81252cdd)
Location: mm/filemap.c:941
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:page_cache_readahead_unbounded
```
**Symbols:**

```
ffffffff8124e310-ffffffff8124e372: __page_cache_alloc.part.0 (STB_LOCAL)
ffffffff8124e380-ffffffff8124e3ad: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8125d8aa)
Location: mm/filemap.c:966
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:pagecache_get_page
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read_get_pages
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:page_cache_ra_unbounded
```
**Symbols:**

```
ffffffff81258720-ffffffff81258791: __page_cache_alloc.part.0 (STB_LOCAL)
ffffffff812587a0-ffffffff812587cd: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125cda0)
Location: mm/filemap.c:990
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
```
**Symbols:**

```
ffffffff8125cda0-ffffffff8125ce27: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81298d20)
Location: mm/filemap.c:1007
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:page_cache_ra_unbounded
```
**Symbols:**

```
ffffffff81298d20-ffffffff81298da1: __page_cache_alloc (STB_GLOBAL)
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
In mm/readahead.c (ffffffff81301961)
Location: include/linux/pagemap.h:480
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
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
In mm/readahead.c (ffffffff8136c035)
Location: include/linux/pagemap.h:478
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
  - mm/readahead.c:readahead_expand
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102adf80)
Location: mm/filemap.c:966
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffff8000102adf80-ffff8000102ae038: __page_cache_alloc (STB_GLOBAL)
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
In mm/filemap.c (c04de244)
Location: include/linux/pagemap.h:213
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
```
```
In mm/readahead.c (c04eaff8)
Location: include/linux/pagemap.h:213
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000363050)
Location: mm/filemap.c:966
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
c000000000363050-c000000000363170: __page_cache_alloc (STB_GLOBAL)
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
In mm/filemap.c (ffffffe0001d6f7c)
Location: include/linux/pagemap.h:213
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
```
```
In mm/readahead.c (ffffffe0001e16e4)
Location: include/linux/pagemap.h:213
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
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
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219910)
Location: mm/filemap.c:966
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff81219910-ffffffff8121999d: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120cb20)
Location: mm/filemap.c:966
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff8120cb20-ffffffff8120cbad: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812176b0)
Location: mm/filemap.c:966
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff812176b0-ffffffff8121773d: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct page *__page_cache_alloc(gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226760)
Location: mm/filemap.c:966
Inline: True
Direct callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/readahead.c:__do_page_cache_readahead
```
**Symbols:**

```
ffffffff81226760-ffffffff812267ed: __page_cache_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
