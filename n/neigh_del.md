# Function: <code>neigh_del</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817deae8)
Location: net/core/neighbour.c:121
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff81859374)
Location: net/core/neighbour.c:121
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_remove_one
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff818a3770)
Location: net/core/neighbour.c:122
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_create
  - net/core/neighbour.c:neigh_remove_one
```
**Symbols:**

```
ffffffff818a3770-ffffffff818a37e6: neigh_del.constprop.54 (STB_LOCAL)
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
In net/core/neighbour.c (ffffffff818c7b74)
Location: net/core/neighbour.c:180
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff819145c4)
Location: net/core/neighbour.c:180
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff81946c34)
Location: net/core/neighbour.c:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff81a16da4)
Location: net/core/neighbour.c:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff81a17084)
Location: net/core/neighbour.c:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff819fde94)
Location: net/core/neighbour.c:180
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff81aaff91)
Location: net/core/neighbour.c:180
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff81c28f10)
Location: net/core/neighbour.c:208
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff81ddbc20)
Location: net/core/neighbour.c:208
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff81e4c970)
Location: net/core/neighbour.c:208
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff81f0b680)
Location: net/core/neighbour.c:208
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffff800010be7e00)
Location: net/core/neighbour.c:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (c0d0116c)
Location: net/core/neighbour.c:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (c000000000cca318)
Location: net/core/neighbour.c:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffe00076c55c)
Location: net/core/neighbour.c:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff818e6c04)
Location: net/core/neighbour.c:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff818a0a44)
Location: net/core/neighbour.c:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff81937c34)
Location: net/core/neighbour.c:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
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
In net/core/neighbour.c (ffffffff81959406)
Location: net/core/neighbour.c:177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_remove_one
```
</details>
</li>
</ul>

## Differences
