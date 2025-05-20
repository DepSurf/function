# Function: <code>page_pool_unmap_page</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void page_pool_unmap_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81934290)
Location: net/core/page_pool.c:243
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
```
**Symbols:**

```
ffffffff81934290-ffffffff819342a0: page_pool_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void page_pool_unmap_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81966ec0)
Location: net/core/page_pool.c:234
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
```
**Symbols:**

```
ffffffff81966ec0-ffffffff81966ed0: page_pool_unmap_page (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void page_pool_unmap_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffff800010c0c9c8)
Location: net/core/page_pool.c:234
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
```
**Symbols:**

```
ffff800010c0c9c8-ffff800010c0c9fc: page_pool_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void page_pool_unmap_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c0d24bbc)
Location: net/core/page_pool.c:234
Inline: False
Direct callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - net/core/xdp.c:__xdp_release_frame
```
**Symbols:**

```
c0d24bbc-c0d24bd8: page_pool_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void page_pool_unmap_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c000000000cf7b50)
Location: net/core/page_pool.c:234
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
```
**Symbols:**

```
c000000000cf7b50-c000000000cf7b64: page_pool_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void page_pool_unmap_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffe000789944)
Location: net/core/page_pool.c:234
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
```
**Symbols:**

```
ffffffe000789944-ffffffe000789976: page_pool_unmap_page (STB_GLOBAL)
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
void page_pool_unmap_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81906e90)
Location: net/core/page_pool.c:234
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
```
**Symbols:**

```
ffffffff81906e90-ffffffff81906ea0: page_pool_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void page_pool_unmap_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818c0ca0)
Location: net/core/page_pool.c:234
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
```
**Symbols:**

```
ffffffff818c0ca0-ffffffff818c0cb0: page_pool_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void page_pool_unmap_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81957ec0)
Location: net/core/page_pool.c:234
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
```
**Symbols:**

```
ffffffff81957ec0-ffffffff81957ed0: page_pool_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void page_pool_unmap_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81979fb0)
Location: net/core/page_pool.c:234
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_release_frame
```
**Symbols:**

```
ffffffff81979fb0-ffffffff81979fc0: page_pool_unmap_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
