# Function: <code>expand_xps_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81717cfe)
Location: net/core/dev.c:1995
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177feef)
Location: net/core/dev.c:2016
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ad632)
Location: net/core/dev.c:2075
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cc1e5)
Location: net/core/dev.c:2109
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818458f4)
Location: net/core/dev.c:2129
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188eedf)
Location: net/core/dev.c:2173
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
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
In net/core/dev.c (ffffffff818b2a2f)
Location: net/core/dev.c:2271
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (ffffffff818ff748)
Location: net/core/dev.c:2281
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (ffffffff81931a68)
Location: net/core/dev.c:2199
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a05838)
Location: net/core/dev.c:2559
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a07038)
Location: net/core/dev.c:2584
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xps_map *expand_xps_map(struct xps_map *map, int attr_index, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e7250)
Location: net/core/dev.c:2629
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff819e7250-ffffffff819e7352: expand_xps_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xps_map *expand_xps_map(struct xps_map *map, int attr_index, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a97c00)
Location: net/core/dev.c:2504
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81a97c00-ffffffff81a97d50: expand_xps_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xps_map *expand_xps_map(struct xps_map *map, int attr_index, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0f190)
Location: net/core/dev.c:2481
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81c0f190-ffffffff81c0f2a1: expand_xps_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xps_map *expand_xps_map(struct xps_map *map, int attr_index, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbeee0)
Location: net/core/dev.c:2466
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81dbeee0-ffffffff81dbeff1: expand_xps_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xps_map *expand_xps_map(struct xps_map *map, int attr_index, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2ebb0)
Location: net/core/dev.c:2492
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81e2ebb0-ffffffff81e2ecc1: expand_xps_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xps_map *expand_xps_map(struct xps_map *map, int attr_index, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eed700)
Location: net/core/dev.c:2495
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff81eed700-ffffffff81eed811: expand_xps_map (STB_LOCAL)
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
In net/core/dev.c (ffff800010bca464)
Location: net/core/dev.c:2199
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (c0cea448)
Location: net/core/dev.c:2199
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (c000000000cad188)
Location: net/core/dev.c:2199
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (ffffffe00075a366)
Location: net/core/dev.c:2199
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (ffffffff818d1a68)
Location: net/core/dev.c:2199
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (ffffffff8188b8f8)
Location: net/core/dev.c:2199
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (ffffffff81922a68)
Location: net/core/dev.c:2199
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
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
In net/core/dev.c (ffffffff81943e98)
Location: net/core/dev.c:2199
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
</details>
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
