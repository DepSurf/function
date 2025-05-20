# Function: <code>xp_init_dma_info</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xp_init_dma_info(struct xsk_buff_pool *pool, struct xsk_dma_map *dma_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9100)
Location: net/xdp/xsk_buff_pool.c:364
Inline: False
```
**Symbols:**

```
ffffffff81bb9100-ffffffff81bb9171: xp_init_dma_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xp_init_dma_info(struct xsk_buff_pool *pool, struct xsk_dma_map *dma_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8110)
Location: net/xdp/xsk_buff_pool.c:358
Inline: False
```
**Symbols:**

```
ffffffff81ba8110-ffffffff81ba8181: xp_init_dma_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xp_init_dma_info(struct xsk_buff_pool *pool, struct xsk_dma_map *dma_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:358
Inline: False
```
**Symbols:**

```
ffffffff81c75d60-ffffffff81c75de4: xp_init_dma_info (STB_LOCAL)
ffffffff81d4311e-ffffffff81d43143: xp_init_dma_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xp_init_dma_info(struct xsk_buff_pool *pool, struct xsk_dma_map *dma_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:380
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_dma_map
```
**Symbols:**

```
ffffffff81e1a190-ffffffff81e1a21e: xp_init_dma_info (STB_LOCAL)
ffffffff81f0fb00-ffffffff81f0fb25: xp_init_dma_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xp_init_dma_info(struct xsk_buff_pool *pool, struct xsk_dma_map *dma_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:381
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_dma_map
```
**Symbols:**

```
ffffffff81ff1600-ffffffff81ff1706: xp_init_dma_info (STB_LOCAL)
ffffffff820b5eab-ffffffff820b5ee2: xp_init_dma_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xp_init_dma_info(struct xsk_buff_pool *pool, struct xsk_dma_map *dma_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:385
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_dma_map
```
**Symbols:**

```
ffffffff8206d820-ffffffff8206d920: xp_init_dma_info (STB_LOCAL)
ffffffff821373f4-ffffffff8213742b: xp_init_dma_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xp_init_dma_info(struct xsk_buff_pool *pool, struct xsk_dma_map *dma_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:409
Inline: False
Direct callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_dma_map
```
**Symbols:**

```
ffffffff82141720-ffffffff82141827: xp_init_dma_info (STB_LOCAL)
ffffffff82219285-ffffffff822192bc: xp_init_dma_info.cold (STB_LOCAL)
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
