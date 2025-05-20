# Function: <code>xp_raw_get_dma</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
dma_addr_t xp_raw_get_dma(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba9530)
Location: net/xdp/xsk_buff_pool.c:268
Inline: False
```
**Symbols:**

```
ffffffff81ba9530-ffffffff81ba9571: xp_raw_get_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
dma_addr_t xp_raw_get_dma(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81bb8d30)
Location: net/xdp/xsk_buff_pool.c:538
Inline: False
```
**Symbols:**

```
ffffffff81bb8d30-ffffffff81bb8d77: xp_raw_get_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
dma_addr_t xp_raw_get_dma(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba7f40)
Location: net/xdp/xsk_buff_pool.c:532
Inline: False
```
**Symbols:**

```
ffffffff81ba7f40-ffffffff81ba7f87: xp_raw_get_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
dma_addr_t xp_raw_get_dma(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:532
Inline: False
```
**Symbols:**

```
ffffffff81d43109-ffffffff81d4311e: xp_raw_get_dma.cold (STB_LOCAL)
ffffffff81c75cf0-ffffffff81c75d57: xp_raw_get_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
dma_addr_t xp_raw_get_dma(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:654
Inline: False
```
**Symbols:**

```
ffffffff81f0fac1-ffffffff81f0fad6: xp_raw_get_dma.cold (STB_LOCAL)
ffffffff81e19ff0-ffffffff81e1a061: xp_raw_get_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
dma_addr_t xp_raw_get_dma(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:659
Inline: False
```
**Symbols:**

```
ffffffff820b5e6c-ffffffff820b5e81: xp_raw_get_dma.cold (STB_LOCAL)
ffffffff81ff1440-ffffffff81ff14b1: xp_raw_get_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
dma_addr_t xp_raw_get_dma(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:663
Inline: False
```
**Symbols:**

```
ffffffff821373b5-ffffffff821373ca: xp_raw_get_dma.cold (STB_LOCAL)
ffffffff8206d660-ffffffff8206d6d1: xp_raw_get_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
dma_addr_t xp_raw_get_dma(struct xsk_buff_pool *pool, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:688
Inline: False
```
**Symbols:**

```
ffffffff8221924b-ffffffff82219260: xp_raw_get_dma.cold (STB_LOCAL)
ffffffff82141500-ffffffff82141571: xp_raw_get_dma (STB_GLOBAL)
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
