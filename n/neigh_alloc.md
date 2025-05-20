# Function: <code>neigh_alloc</code>

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
In net/core/neighbour.c (ffffffff81728daa)
Location: net/core/neighbour.c:266
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
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
In net/core/neighbour.c (ffffffff8179288a)
Location: net/core/neighbour.c:266
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
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
In net/core/neighbour.c (ffffffff817c015a)
Location: net/core/neighbour.c:267
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
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
In net/core/neighbour.c (ffffffff817de7d0)
Location: net/core/neighbour.c:303
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
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
In net/core/neighbour.c (ffffffff81859040)
Location: net/core/neighbour.c:303
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
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
In net/core/neighbour.c (ffffffff818a4640)
Location: net/core/neighbour.c:305
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
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
In net/core/neighbour.c (ffffffff818c7c15)
Location: net/core/neighbour.c:377
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (ffffffff81914675)
Location: net/core/neighbour.c:377
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (ffffffff81946ce5)
Location: net/core/neighbour.c:374
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct neighbour *neigh_alloc(struct neigh_table *tbl, struct net_device *dev, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:374
Inline: False
Direct callers:
  - net/core/neighbour.c:___neigh_create
```
**Symbols:**

```
ffffffff81a16f70-ffffffff81a17162: neigh_alloc (STB_LOCAL)
ffffffff81a180c5-ffffffff81a180da: neigh_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct neighbour *neigh_alloc(struct neigh_table *tbl, struct net_device *dev, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:376
Inline: False
Direct callers:
  - net/core/neighbour.c:___neigh_create
```
**Symbols:**

```
ffffffff81a17260-ffffffff81a17453: neigh_alloc (STB_LOCAL)
ffffffff81c3162d-ffffffff81c31642: neigh_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct neighbour *neigh_alloc(struct neigh_table *tbl, struct net_device *dev, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:380
Inline: False
Direct callers:
  - net/core/neighbour.c:___neigh_create
```
**Symbols:**

```
ffffffff819fdf30-ffffffff819fe26e: neigh_alloc (STB_LOCAL)
ffffffff81c23936-ffffffff81c2394b: neigh_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct neighbour *neigh_alloc(struct neigh_table *tbl, struct net_device *dev, u8 flags, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:380
Inline: False
Direct callers:
  - net/core/neighbour.c:___neigh_create
```
**Symbols:**

```
ffffffff81ab0030-ffffffff81ab0386: neigh_alloc (STB_LOCAL)
ffffffff81d36c52-ffffffff81d36c67: neigh_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct neighbour *neigh_alloc(struct neigh_table *tbl, struct net_device *dev, u32 flags, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:423
Inline: False
Direct callers:
  - net/core/neighbour.c:___neigh_create
```
**Symbols:**

```
ffffffff81c28f80-ffffffff81c2931f: neigh_alloc (STB_LOCAL)
ffffffff81f03553-ffffffff81f03568: neigh_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct neighbour *neigh_alloc(struct neigh_table *tbl, struct net_device *dev, u32 flags, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81ddbca0)
Location: net/core/neighbour.c:461
Inline: False
Direct callers:
  - net/core/neighbour.c:___neigh_create
```
**Symbols:**

```
ffffffff81ddbca0-ffffffff81ddc078: neigh_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct neighbour *neigh_alloc(struct neigh_table *tbl, struct net_device *dev, u32 flags, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81e4c9f0)
Location: net/core/neighbour.c:461
Inline: False
Direct callers:
  - net/core/neighbour.c:___neigh_create
```
**Symbols:**

```
ffffffff81e4c9f0-ffffffff81e4cdc8: neigh_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct neighbour *neigh_alloc(struct neigh_table *tbl, struct net_device *dev, u32 flags, bool exempt_from_gc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81f0b700)
Location: net/core/neighbour.c:469
Inline: False
Direct callers:
  - net/core/neighbour.c:___neigh_create
```
**Symbols:**

```
ffffffff81f0b700-ffffffff81f0bb24: neigh_alloc (STB_LOCAL)
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
In net/core/neighbour.c (ffff800010be7efc)
Location: net/core/neighbour.c:374
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (c0d011f0)
Location: net/core/neighbour.c:374
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (c000000000cca468)
Location: net/core/neighbour.c:374
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (ffffffe00076c610)
Location: net/core/neighbour.c:374
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (ffffffff818e6cb5)
Location: net/core/neighbour.c:374
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (ffffffff818a0af5)
Location: net/core/neighbour.c:374
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (ffffffff81937ce5)
Location: net/core/neighbour.c:374
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (ffffffff819594c5)
Location: net/core/neighbour.c:374
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>tbl, dev, exempt_from_gc</code> ➡️ <code>tbl, dev, flags, exempt_from_gc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 flags</code> ➡️ <code>u32 flags</code>
</li>
</ul>
</details>
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
