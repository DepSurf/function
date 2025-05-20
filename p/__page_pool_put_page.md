# Function: <code>__page_pool_put_page</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __page_pool_put_page(struct page_pool *pool, struct page *page, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818bde30)
Location: net/core/page_pool.c:227
Inline: True
Direct callers:
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffffffff818bde30-ffffffff818be01b: __page_pool_put_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __page_pool_put_page(struct page_pool *pool, struct page *page, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818e5210)
Location: net/core/page_pool.c:227
Inline: True
Direct callers:
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffffffff818e5210-ffffffff818e53fb: __page_pool_put_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __page_pool_put_page(struct page_pool *pool, struct page *page, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81934b30)
Location: net/core/page_pool.c:293
Inline: True
Direct callers:
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffffffff81934b30-ffffffff81934d37: __page_pool_put_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __page_pool_put_page(struct page_pool *pool, struct page *page, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81967890)
Location: net/core/page_pool.c:284
Inline: True
Direct callers:
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffffffff81967890-ffffffff81967aa0: __page_pool_put_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3d2d7)
Location: net/core/page_pool.c:368
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
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
In net/core/page_pool.c (ffffffff81a240f7)
Location: net/core/page_pool.c:399
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
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
In net/core/page_pool.c (ffffffff81ad86c4)
Location: net/core/page_pool.c:425
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
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
In net/core/page_pool.c (ffffffff81c59539)
Location: net/core/page_pool.c:553
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
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
In net/core/page_pool.c (ffffffff81e0f519)
Location: net/core/page_pool.c:554
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
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
In net/core/page_pool.c (ffffffff81e82ce9)
Location: net/core/page_pool.c:579
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
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
In net/core/page_pool.c (ffffffff81f43b5b)
Location: net/core/page_pool.c:640
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_unrefed_page
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
void __page_pool_put_page(struct page_pool *pool, struct page *page, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffff800010c0d308)
Location: net/core/page_pool.c:284
Inline: True
Direct callers:
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffff800010c0d308-ffff800010c0d58c: __page_pool_put_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __page_pool_put_page(struct page_pool *pool, struct page *page, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c0d255a4)
Location: net/core/page_pool.c:284
Inline: True
Direct callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_fill_rx_channels
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
c0d255a4-c0d25760: __page_pool_put_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __page_pool_put_page(struct page_pool *pool, struct page *page, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c000000000cf89e0)
Location: net/core/page_pool.c:284
Inline: True
Direct callers:
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
c000000000cf89e0-c000000000cf8d60: __page_pool_put_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __page_pool_put_page(struct page_pool *pool, struct page *page, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffe00078a198)
Location: net/core/page_pool.c:284
Inline: True
Direct callers:
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffffffe00078a198-ffffffe00078a35c: __page_pool_put_page (STB_GLOBAL)
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
void __page_pool_put_page(struct page_pool *pool, struct page *page, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81907860)
Location: net/core/page_pool.c:284
Inline: True
Direct callers:
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffffffff81907860-ffffffff81907a70: __page_pool_put_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __page_pool_put_page(struct page_pool *pool, struct page *page, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818c1670)
Location: net/core/page_pool.c:284
Inline: True
Direct callers:
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffffffff818c1670-ffffffff818c1880: __page_pool_put_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __page_pool_put_page(struct page_pool *pool, struct page *page, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81958890)
Location: net/core/page_pool.c:284
Inline: True
Direct callers:
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffffffff81958890-ffffffff81958aa0: __page_pool_put_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __page_pool_put_page(struct page_pool *pool, struct page *page, bool allow_direct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff8197a9d0)
Location: net/core/page_pool.c:284
Inline: True
Direct callers:
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffffffff8197a9d0-ffffffff8197abda: __page_pool_put_page (STB_GLOBAL)
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
