# Function: <code>neigh_hash_grow</code>

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
In net/core/neighbour.c (ffffffff817291d3)
Location: net/core/neighbour.c:359
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
In net/core/neighbour.c (ffffffff81792cad)
Location: net/core/neighbour.c:359
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
In net/core/neighbour.c (ffffffff817c057d)
Location: net/core/neighbour.c:360
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
In net/core/neighbour.c (ffffffff817debe4)
Location: net/core/neighbour.c:395
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
In net/core/neighbour.c (ffffffff81859470)
Location: net/core/neighbour.c:395
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
In net/core/neighbour.c (ffffffff818a4a54)
Location: net/core/neighbour.c:397
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
In net/core/neighbour.c (ffffffff818c814c)
Location: net/core/neighbour.c:483
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
In net/core/neighbour.c (ffffffff81914c2e)
Location: net/core/neighbour.c:483
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
In net/core/neighbour.c (ffffffff8194729e)
Location: net/core/neighbour.c:480
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct neigh_hash_table *neigh_hash_grow(struct neigh_table *tbl, long unsigned int new_shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a11480)
Location: net/core/neighbour.c:480
Inline: False
Direct callers:
  - net/core/neighbour.c:___neigh_create
```
**Symbols:**

```
ffffffff81a11480-ffffffff81a1158b: neigh_hash_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct neigh_hash_table *neigh_hash_grow(struct neigh_table *tbl, long unsigned int new_shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a117e0)
Location: net/core/neighbour.c:482
Inline: False
Direct callers:
  - net/core/neighbour.c:___neigh_create
```
**Symbols:**

```
ffffffff81a117e0-ffffffff81a118eb: neigh_hash_grow (STB_LOCAL)
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
In net/core/neighbour.c (ffffffff819fe5b1)
Location: net/core/neighbour.c:486
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (ffffffff81ab06f6)
Location: net/core/neighbour.c:487
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (ffffffff81c2971b)
Location: net/core/neighbour.c:531
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (ffffffff81ddc441)
Location: net/core/neighbour.c:569
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (ffffffff81e4d1a3)
Location: net/core/neighbour.c:569
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (ffffffff81f0bf00)
Location: net/core/neighbour.c:577
Inline: True
Inline callers:
  - net/core/neighbour.c:___neigh_create
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
In net/core/neighbour.c (ffff800010be84f8)
Location: net/core/neighbour.c:480
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
In net/core/neighbour.c (c0d017a0)
Location: net/core/neighbour.c:480
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
In net/core/neighbour.c (c000000000ccab80)
Location: net/core/neighbour.c:480
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
In net/core/neighbour.c (ffffffe00076ca58)
Location: net/core/neighbour.c:480
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
In net/core/neighbour.c (ffffffff818e726e)
Location: net/core/neighbour.c:480
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
In net/core/neighbour.c (ffffffff818a10ae)
Location: net/core/neighbour.c:480
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
In net/core/neighbour.c (ffffffff8193829e)
Location: net/core/neighbour.c:480
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
In net/core/neighbour.c (ffffffff81959aad)
Location: net/core/neighbour.c:480
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
</ul>
