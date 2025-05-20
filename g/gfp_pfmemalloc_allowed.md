# Function: <code>gfp_pfmemalloc_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81193010)
Location: mm/page_alloc.c:2959
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81193010-ffffffff811930f4: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811aa520)
Location: mm/page_alloc.c:3291
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff811aa520-ffffffff811aa59d: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811baa70)
Location: mm/page_alloc.c:3396
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff811baa70-ffffffff811baae0: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c2af0)
Location: mm/page_alloc.c:3629
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff811c2af0-ffffffff811c2b5e: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d7add)
Location: mm/page_alloc.c:3769
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff811d8b00-ffffffff811d8b77: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f8cb7)
Location: mm/page_alloc.c:3903
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff811f9cc0-ffffffff811f9d36: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120b278)
Location: mm/page_alloc.c:4076
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8120c370-ffffffff8120c3e6: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812714f7)
Location: mm/page_alloc.c:4243
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812725d0-ffffffff81272646: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81280337)
Location: mm/page_alloc.c:4237
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81281430-ffffffff812814a6: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b2b2c)
Location: mm/page_alloc.c:4355
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff812b3910-ffffffff812b3986: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812be697)
Location: mm/page_alloc.c:4509
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff812bf400-ffffffff812bf476: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c3728)
Location: mm/page_alloc.c:4558
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
```
**Symbols:**

```
ffffffff812c4a80-ffffffff812c4af6: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813075a8)
Location: mm/page_alloc.c:4734
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
```
**Symbols:**

```
ffffffff81308a80-ffffffff81308af6: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136f8c7)
Location: mm/page_alloc.c:4785
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
```
**Symbols:**

```
ffffffff81370f10-ffffffff81370f96: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ebeef)
Location: mm/page_alloc.c:4894
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
```
**Symbols:**

```
ffffffff813ed700-ffffffff813ed786: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81420eec)
Location: mm/page_alloc.c:3829
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - net/core/skbuff.c:kmalloc_reserve
  - net/core/skbuff.c:kmalloc_reserve
```
**Symbols:**

```
ffffffff81422590-ffffffff81422616: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144dcc2)
Location: mm/page_alloc.c:3919
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - net/core/skbuff.c:kmalloc_reserve
  - net/core/skbuff.c:kmalloc_reserve
```
**Symbols:**

```
ffffffff8144f390-ffffffff8144f416: gfp_pfmemalloc_allowed (STB_GLOBAL)
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010318254)
Location: mm/page_alloc.c:4237
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffff800010319110-ffff800010319194: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c05327f8)
Location: mm/page_alloc.c:4237
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
c0533bc8-c0533c78: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ea94c)
Location: mm/page_alloc.c:4237
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
c0000000003ebb40-c0000000003ebbb8: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021e08c)
Location: mm/page_alloc.c:4237
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffe00021eec6-ffffffe00021ef48: gfp_pfmemalloc_allowed (STB_GLOBAL)
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81278987)
Location: mm/page_alloc.c:4237
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81279a80-ffffffff81279af6: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126a877)
Location: mm/page_alloc.c:4237
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8126b970-ffffffff8126b9e6: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81276727)
Location: mm/page_alloc.c:4237
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81277820-ffffffff81277896: gfp_pfmemalloc_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812862e7)
Location: mm/page_alloc.c:4237
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81287410-ffffffff81287486: gfp_pfmemalloc_allowed (STB_GLOBAL)
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
