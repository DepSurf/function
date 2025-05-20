# Function: <code>page_pool_put_page</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818baa25)
Location: include/net/page_pool.h:118
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818e197a)
Location: include/net/page_pool.h:118
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff819303ca)
Location: include/net/page_pool.h:156
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff8196261a)
Location: include/net/page_pool.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void page_pool_put_page(struct page_pool *pool, struct page *page, unsigned int dma_sync_size, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3b050)
Location: net/core/page_pool.c:365
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffffffff81a3b050-ffffffff81a3b287: page_pool_put_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_pool_put_page(struct page_pool *pool, struct page *page, unsigned int dma_sync_size, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3d770)
Location: net/core/page_pool.c:412
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffffffff81a3d770-ffffffff81a3d9c4: page_pool_put_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_pool_put_page(struct page_pool *pool, struct page *page, unsigned int dma_sync_size, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a24840)
Location: net/core/page_pool.c:445
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffffffff81a24840-ffffffff81a24a95: page_pool_put_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void page_pool_put_page(struct page_pool *pool, struct page *page, unsigned int dma_sync_size, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81ad90e0)
Location: net/core/page_pool.c:476
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_return
  - net/core/page_pool.c:page_pool_return_skb_page
```
**Symbols:**

```
ffffffff81ad90e0-ffffffff81ad937e: page_pool_put_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c51948)
Location: include/net/page_pool.h:314
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81c5a5d1)
Location: include/net/page_pool.h:314
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
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
In net/core/xdp.c (ffffffff81e06d6e)
Location: include/net/page_pool.h:314
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81e100b1)
Location: include/net/page_pool.h:314
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
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
In net/core/xdp.c (ffffffff81e796ce)
Location: include/net/page_pool.h:330
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81e83936)
Location: include/net/page_pool.h:330
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_return_skb_page
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
In net/core/skbuff.c (ffffffff81ed12e7)
Location: include/net/page_pool/helpers.h:304
Inline: True
Inline callers:
  - net/core/skbuff.c:napi_pp_put_page
```
```
In net/core/xdp.c (ffffffff81f39784)
Location: include/net/page_pool/helpers.h:304
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c06f34)
Location: include/net/page_pool.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d201bc)
Location: include/net/page_pool.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000cf1728)
Location: include/net/page_pool.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe00078531c)
Location: include/net/page_pool.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff819025ea)
Location: include/net/page_pool.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bc41a)
Location: include/net/page_pool.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff8195361a)
Location: include/net/page_pool.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff8197513b)
Location: include/net/page_pool.h:155
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
