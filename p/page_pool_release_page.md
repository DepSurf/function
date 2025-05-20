# Function: <code>page_pool_release_page</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff819300db)
Location: include/net/page_pool.h:197
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
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
In net/core/xdp.c (ffffffff8196233b)
Location: include/net/page_pool.h:178
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void page_pool_release_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3a850)
Location: net/core/page_pool.c:284
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
**Symbols:**

```
ffffffff81a3a850-ffffffff81a3a947: page_pool_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_pool_release_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3ccf0)
Location: net/core/page_pool.c:286
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
**Symbols:**

```
ffffffff81a3ccf0-ffffffff81a3cd86: page_pool_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_pool_release_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a23a30)
Location: net/core/page_pool.c:325
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
**Symbols:**

```
ffffffff81a23a30-ffffffff81a23ac6: page_pool_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void page_pool_release_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:349
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
**Symbols:**

```
ffffffff81d3781f-ffffffff81d3783d: page_pool_release_page.cold (STB_LOCAL)
ffffffff81ad8060-ffffffff81ad8128: page_pool_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void page_pool_release_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:469
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
**Symbols:**

```
ffffffff81f041db-ffffffff81f041f9: page_pool_release_page.cold (STB_LOCAL)
ffffffff81c58e20-ffffffff81c58f00: page_pool_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void page_pool_release_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:470
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
**Symbols:**

```
ffffffff820ac873-ffffffff820ac891: page_pool_release_page.cold (STB_LOCAL)
ffffffff81e0ed60-ffffffff81e0ee40: page_pool_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void page_pool_release_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:495
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_alloc_frag
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
  - net/core/page_pool.c:page_pool_refill_alloc_cache
```
**Symbols:**

```
ffffffff8212df6a-ffffffff8212df88: page_pool_release_page.cold (STB_LOCAL)
ffffffff81e82520-ffffffff81e82600: page_pool_release_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/core/xdp.c (ffff800010c065e4)
Location: include/net/page_pool.h:178
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
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
In drivers/net/ethernet/ti/cpsw.c (c0ad2f0c)
Location: include/net/page_pool.h:178
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
```
In net/core/xdp.c (c0d1f6b8)
Location: include/net/page_pool.h:178
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
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
In net/core/xdp.c (c000000000cf0ac0)
Location: include/net/page_pool.h:178
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
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
In net/core/xdp.c (ffffffe000784b7a)
Location: include/net/page_pool.h:178
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
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
In net/core/xdp.c (ffffffff8190230b)
Location: include/net/page_pool.h:178
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
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
In net/core/xdp.c (ffffffff818bc13b)
Location: include/net/page_pool.h:178
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
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
In net/core/xdp.c (ffffffff8195333b)
Location: include/net/page_pool.h:178
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
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
In net/core/xdp.c (ffffffff81974e43)
Location: include/net/page_pool.h:178
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
