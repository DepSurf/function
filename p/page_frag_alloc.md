# Function: <code>page_frag_alloc</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bb930)
Location: mm/page_alloc.c:3961
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:napi_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
```
**Symbols:**

```
ffffffff811bb930-ffffffff811bbab4: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c3c10)
Location: mm/page_alloc.c:4248
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:napi_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
```
**Symbols:**

```
ffffffff811c3c10-ffffffff811c3d56: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d89b0)
Location: mm/page_alloc.c:4367
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:napi_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
```
**Symbols:**

```
ffffffff811d89b0-ffffffff811d8af6: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f9b70)
Location: mm/page_alloc.c:4499
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:napi_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
```
**Symbols:**

```
ffffffff811f9b70-ffffffff811f9cbb: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120c210)
Location: mm/page_alloc.c:4670
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:napi_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
```
**Symbols:**

```
ffffffff8120c210-ffffffff8120c363: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81272470)
Location: mm/page_alloc.c:4837
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:napi_alloc_frag
```
**Symbols:**

```
ffffffff81272470-ffffffff812725cd: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812812d0)
Location: mm/page_alloc.c:4855
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:napi_alloc_frag
```
**Symbols:**

```
ffffffff812812d0-ffffffff8128142d: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b37a0)
Location: mm/page_alloc.c:4958
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:napi_alloc_frag
```
**Symbols:**

```
ffffffff812b37a0-ffffffff812b3904: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bf260)
Location: mm/page_alloc.c:5132
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:napi_alloc_frag
```
**Symbols:**

```
ffffffff812bf260-ffffffff812bf3f9: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d027e)
Location: include/linux/gfp.h:609
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a8140c)
Location: include/linux/gfp.h:630
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
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
In net/core/skbuff.c (ffffffff81bf50f7)
Location: include/linux/gfp.h:661
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
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
In net/core/skbuff.c (ffffffff81da44de)
Location: include/linux/gfp.h:311
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e13132)
Location: include/linux/gfp.h:311
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed02f2)
Location: include/linux/gfp.h:319
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
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
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010318f78)
Location: mm/page_alloc.c:4855
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:napi_alloc_frag
```
**Symbols:**

```
ffff800010318f78-ffff80001031910c: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0533a68)
Location: mm/page_alloc.c:4855
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:napi_alloc_frag
```
**Symbols:**

```
c0533a68-c0533bc8: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003eb990)
Location: mm/page_alloc.c:4855
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:napi_alloc_frag
```
**Symbols:**

```
c0000000003eb990-c0000000003ebb40: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021edb4)
Location: mm/page_alloc.c:4855
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:napi_alloc_frag
```
**Symbols:**

```
ffffffe00021edb4-ffffffe00021eec6: page_frag_alloc (STB_GLOBAL)
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
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81279920)
Location: mm/page_alloc.c:4855
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:napi_alloc_frag
```
**Symbols:**

```
ffffffff81279920-ffffffff81279a7d: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126b810)
Location: mm/page_alloc.c:4855
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:napi_alloc_frag
```
**Symbols:**

```
ffffffff8126b810-ffffffff8126b96d: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812776c0)
Location: mm/page_alloc.c:4855
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:napi_alloc_frag
```
**Symbols:**

```
ffffffff812776c0-ffffffff8127781d: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *page_frag_alloc(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812872b0)
Location: mm/page_alloc.c:4855
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:napi_alloc_frag
```
**Symbols:**

```
ffffffff812872b0-ffffffff8128740d: page_frag_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
