# Function: <code>xp_alloc</code>

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
struct xdp_buff *xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba96e0)
Location: net/xdp/xsk_buff_pool.c:219
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81ba96e0-ffffffff81ba979d: xp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xdp_buff *xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9330)
Location: net/xdp/xsk_buff_pool.c:489
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81bb9330-ffffffff81bb93ce: xp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xdp_buff *xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8330)
Location: net/xdp/xsk_buff_pool.c:483
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81ba8330-ffffffff81ba83ce: xp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct xdp_buff *xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:483
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81d43182-ffffffff81d43197: xp_alloc.cold (STB_LOCAL)
ffffffff81c760c0-ffffffff81c76173: xp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct xdp_buff *xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:508
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_rcv
  - net/xdp/xsk_buff_pool.c:xp_alloc_batch
```
**Symbols:**

```
ffffffff81f0fb73-ffffffff81f0fb88: xp_alloc.cold (STB_LOCAL)
ffffffff81e1a420-ffffffff81e1a4dd: xp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct xdp_buff *xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:513
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_rcv
  - net/xdp/xsk_buff_pool.c:xp_alloc_batch
```
**Symbols:**

```
ffffffff820b5f30-ffffffff820b5f45: xp_alloc.cold (STB_LOCAL)
ffffffff81ff1930-ffffffff81ff19ed: xp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct xdp_buff *xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:517
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_rcv
  - net/xdp/xsk_buff_pool.c:xp_alloc_batch
```
**Symbols:**

```
ffffffff82137479-ffffffff8213748e: xp_alloc.cold (STB_LOCAL)
ffffffff8206db30-ffffffff8206dbed: xp_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct xdp_buff *xp_alloc(struct xsk_buff_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk_buff_pool.c (0)
Location: net/xdp/xsk_buff_pool.c:541
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_rcv
  - net/xdp/xsk.c:__xsk_rcv
  - net/xdp/xsk_buff_pool.c:xp_alloc_batch
```
**Symbols:**

```
ffffffff82219334-ffffffff82219349: xp_alloc.cold (STB_LOCAL)
ffffffff82141b70-ffffffff82141c36: xp_alloc (STB_GLOBAL)
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
