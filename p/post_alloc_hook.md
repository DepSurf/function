# Function: <code>post_alloc_hook</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a992e)
Location: mm/page_alloc.c:1719
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
Direct callers:
  - mm/compaction.c:map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811a8290-ffffffff811a82a5: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b9e87)
Location: mm/page_alloc.c:1738
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
Direct callers:
  - mm/compaction.c:map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811b8660-ffffffff811b8675: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c23ea)
Location: mm/page_alloc.c:1751
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
Direct callers:
  - mm/compaction.c:map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811c04c0-ffffffff811c04d5: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d6d98)
Location: mm/page_alloc.c:1789
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
Direct callers:
  - mm/compaction.c:map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811d4fa0-ffffffff811d4fb5: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f80d6)
Location: mm/page_alloc.c:1896
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
Direct callers:
  - mm/compaction.c:map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811f63c0-ffffffff811f63ea: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120a88c)
Location: mm/page_alloc.c:1940
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
Direct callers:
  - mm/compaction.c:map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff812086a0-ffffffff812086ca: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126d3d5)
Location: mm/page_alloc.c:2136
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff8126eb00-ffffffff8126eb2a: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127bf15)
Location: mm/page_alloc.c:2127
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff8127d940-ffffffff8127d96a: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812af745)
Location: mm/page_alloc.c:2199
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
ffffffff812afa60-ffffffff812afa8a: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bdff5)
Location: mm/page_alloc.c:2278
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
Direct callers:
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
ffffffff812bb6d0-ffffffff812bb72f: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c47b3)
Location: mm/page_alloc.c:2314
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
Direct callers:
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
ffffffff812c0720-ffffffff812c077f: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff8130862b)
Location: mm/page_alloc.c:2388
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
ffffffff81cbd489-ffffffff81cbd4d1: post_alloc_hook.cold (STB_LOCAL)
ffffffff813035a0-ffffffff8130362c: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff813709c6)
Location: mm/page_alloc.c:2390
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/compaction.c:split_map_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81e6f46d-ffffffff81e6f4cf: post_alloc_hook.cold (STB_LOCAL)
ffffffff8136b480-ffffffff8136b594: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff813ece48)
Location: mm/page_alloc.c:2466
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/compaction.c:split_map_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8206520f-ffffffff8206528a: post_alloc_hook.cold (STB_LOCAL)
ffffffff813e77b0-ffffffff813e78c1: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81421d92)
Location: mm/page_alloc.c:1514
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/compaction.c:split_map_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff820e49ee-ffffffff820e4a69: post_alloc_hook.cold (STB_LOCAL)
ffffffff8141c890-ffffffff8141c9a2: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff8144ebc4)
Location: mm/page_alloc.c:1477
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/compaction.c:split_map_pages
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff821c1689-ffffffff821c1704: post_alloc_hook.cold (STB_LOCAL)
ffffffff81449390-ffffffff814494a2: post_alloc_hook (STB_GLOBAL)
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
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff8000103134c0)
Location: mm/page_alloc.c:2127
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffff800010315218-ffff80001031523c: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052e2c8)
Location: mm/page_alloc.c:2127
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
c052fad0-c052faf8: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e50f0)
Location: mm/page_alloc.c:2127
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
c0000000003e7010-c0000000003e7058: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021a7f0)
Location: mm/page_alloc.c:2127
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffe00021bcba-ffffffe00021bce0: post_alloc_hook (STB_GLOBAL)
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
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81274565)
Location: mm/page_alloc.c:2127
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81275f90-ffffffff81275fba: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812664d5)
Location: mm/page_alloc.c:2127
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81267ee0-ffffffff81267f0a: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81272305)
Location: mm/page_alloc.c:2127
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81273d30-ffffffff81273d5a: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void post_alloc_hook(struct page *page, unsigned int order, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81282135)
Location: mm/page_alloc.c:2127
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
Direct callers:
  - mm/compaction.c:split_map_pages
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81283830-ffffffff8128385a: post_alloc_hook (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
