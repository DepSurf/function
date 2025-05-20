# Function: <code>xp_dma_map</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xp_dma_map(struct xsk_buff_pool *pool, struct device *dev, long unsigned int attrs, struct page **pages, u32 nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba98e0)
Location: net/xdp/xsk_buff_pool.c:124
Inline: True
```
**Symbols:**

```
ffffffff81ba98e0-ffffffff81ba9a28: xp_dma_map.part.0 (STB_LOCAL)
ffffffff81ba9a30-ffffffff81ba9aa4: xp_dma_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xp_dma_map(struct xsk_buff_pool *pool, struct device *dev, long unsigned int attrs, struct page **pages, u32 nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9420)
Location: net/xdp/xsk_buff_pool.c:379
Inline: True
```
**Symbols:**

```
ffffffff81bb9420-ffffffff81bb9628: xp_dma_map.part.0 (STB_LOCAL)
ffffffff81bb96e0-ffffffff81bb9787: xp_dma_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xp_dma_map(struct xsk_buff_pool *pool, struct device *dev, long unsigned int attrs, struct page **pages, u32 nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8420)
Location: net/xdp/xsk_buff_pool.c:373
Inline: True
```
**Symbols:**

```
ffffffff81ba8420-ffffffff81ba8603: xp_dma_map.part.0 (STB_LOCAL)
ffffffff81ba86c0-ffffffff81ba8767: xp_dma_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xp_dma_map(struct xsk_buff_pool *pool, struct device *dev, long unsigned int attrs, struct page **pages, u32 nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81c76410)
Location: net/xdp/xsk_buff_pool.c:373
Inline: True
```
**Symbols:**

```
ffffffff81c76180-ffffffff81c76357: xp_dma_map.part.0 (STB_LOCAL)
ffffffff81d43197-ffffffff81d431ab: xp_dma_map.part.0.cold (STB_LOCAL)
ffffffff81c76410-ffffffff81c764b7: xp_dma_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xp_dma_map(struct xsk_buff_pool *pool, struct device *dev, long unsigned int attrs, struct page **pages, u32 nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:395
Inline: False
```
**Symbols:**

```
ffffffff81f0fb88-ffffffff81f0fb9c: xp_dma_map.cold (STB_LOCAL)
ffffffff81e1a4e0-ffffffff81e1a7df: xp_dma_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xp_dma_map(struct xsk_buff_pool *pool, struct device *dev, long unsigned int attrs, struct page **pages, u32 nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:406
Inline: False
```
**Symbols:**

```
ffffffff820b5f45-ffffffff820b5f59: xp_dma_map.cold (STB_LOCAL)
ffffffff81ff1a00-ffffffff81ff1c97: xp_dma_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xp_dma_map(struct xsk_buff_pool *pool, struct device *dev, long unsigned int attrs, struct page **pages, u32 nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:410
Inline: False
```
**Symbols:**

```
ffffffff8213748e-ffffffff821374a2: xp_dma_map.cold (STB_LOCAL)
ffffffff8206dc00-ffffffff8206dea4: xp_dma_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xp_dma_map(struct xsk_buff_pool *pool, struct device *dev, long unsigned int attrs, struct page **pages, u32 nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:434
Inline: False
```
**Symbols:**

```
ffffffff82219349-ffffffff8221935d: xp_dma_map.cold (STB_LOCAL)
ffffffff82141c50-ffffffff82141f23: xp_dma_map (STB_GLOBAL)
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
