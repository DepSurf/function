# Function: <code>page_pool_alloc_pages</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818bdc10)
Location: net/core/page_pool.c:159
Inline: False
```
**Symbols:**

```
ffffffff818bdc10-ffffffff818bde26: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818e4ff0)
Location: net/core/page_pool.c:159
Inline: False
```
**Symbols:**

```
ffffffff818e4ff0-ffffffff818e5206: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81934900)
Location: net/core/page_pool.c:179
Inline: False
```
**Symbols:**

```
ffffffff81934900-ffffffff81934b2c: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81967230)
Location: net/core/page_pool.c:175
Inline: False
```
**Symbols:**

```
ffffffff81967230-ffffffff81967497: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3b000)
Location: net/core/page_pool.c:245
Inline: False
```
**Symbols:**

```
ffffffff81a3b000-ffffffff81a3b04b: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3d720)
Location: net/core/page_pool.c:247
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81a3d720-ffffffff81a3d76b: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a247f0)
Location: net/core/page_pool.c:286
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81a247f0-ffffffff81a2483b: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81ad948d)
Location: net/core/page_pool.c:310
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
Direct callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81ad8ee0-ffffffff81ad8f4c: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81c5a72d)
Location: net/core/page_pool.c:430
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
Direct callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81c5a050-ffffffff81c5a0cd: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e1088d)
Location: net/core/page_pool.c:431
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
Direct callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81e10730-ffffffff81e107ad: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e84169)
Location: net/core/page_pool.c:456
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
Direct callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81e83ff0-ffffffff81e84075: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81f44831)
Location: net/core/page_pool.c:512
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_alloc_frag
Direct callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81f446d0-ffffffff81f44755: page_pool_alloc_pages (STB_GLOBAL)
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
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffff800010c0d098)
Location: net/core/page_pool.c:175
Inline: False
```
**Symbols:**

```
ffff800010c0d098-ffff800010c0d304: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c0d24f2c)
Location: net/core/page_pool.c:175
Inline: False
Direct callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_fill_rx_channels
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
**Symbols:**

```
c0d24f2c-c0d25164: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c000000000cf8000)
Location: net/core/page_pool.c:175
Inline: False
```
**Symbols:**

```
c000000000cf8000-c000000000cf8324: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffe000789f98)
Location: net/core/page_pool.c:175
Inline: False
```
**Symbols:**

```
ffffffe000789f98-ffffffe00078a198: page_pool_alloc_pages (STB_GLOBAL)
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
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81907200)
Location: net/core/page_pool.c:175
Inline: False
```
**Symbols:**

```
ffffffff81907200-ffffffff81907467: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818c1010)
Location: net/core/page_pool.c:175
Inline: False
```
**Symbols:**

```
ffffffff818c1010-ffffffff818c1277: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81958230)
Location: net/core/page_pool.c:175
Inline: False
```
**Symbols:**

```
ffffffff81958230-ffffffff81958497: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *page_pool_alloc_pages(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff8197a340)
Location: net/core/page_pool.c:175
Inline: False
```
**Symbols:**

```
ffffffff8197a340-ffffffff8197a5ce: page_pool_alloc_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
