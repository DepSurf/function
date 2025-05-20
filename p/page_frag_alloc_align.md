# Function: <code>page_frag_alloc_align</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *page_frag_alloc_align(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask, unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c4300)
Location: mm/page_alloc.c:5333
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:__napi_alloc_frag_align
```
**Symbols:**

```
ffffffff812c4300-ffffffff812c449a: page_frag_alloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *page_frag_alloc_align(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask, unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5514
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:__napi_alloc_frag_align
```
**Symbols:**

```
ffffffff81cbda18-ffffffff81cbda33: page_frag_alloc_align.cold (STB_LOCAL)
ffffffff813081a0-ffffffff8130836d: page_frag_alloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *page_frag_alloc_align(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask, unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5569
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:__napi_alloc_frag_align
```
**Symbols:**

```
ffffffff81e6f8d3-ffffffff81e6f8ee: page_frag_alloc_align.cold (STB_LOCAL)
ffffffff81370490-ffffffff813706b9: page_frag_alloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *page_frag_alloc_align(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask, unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5696
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:__napi_alloc_frag_align
```
**Symbols:**

```
ffffffff82065640-ffffffff8206565b: page_frag_alloc_align.cold (STB_LOCAL)
ffffffff813ed3f0-ffffffff813ed6e3: page_frag_alloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *page_frag_alloc_align(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask, unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4624
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:__napi_alloc_frag_align
```
**Symbols:**

```
ffffffff820e4e39-ffffffff820e4e54: page_frag_alloc_align.cold (STB_LOCAL)
ffffffff81422400-ffffffff81422579: page_frag_alloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *page_frag_alloc_align(struct page_frag_cache *nc, unsigned int fragsz, gfp_t gfp_mask, unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:4713
Inline: False
Direct callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:__napi_alloc_frag_align
```
**Symbols:**

```
ffffffff821c1b18-ffffffff821c1b33: page_frag_alloc_align.cold (STB_LOCAL)
ffffffff8144f0c0-ffffffff8144f37a: page_frag_alloc_align (STB_GLOBAL)
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
