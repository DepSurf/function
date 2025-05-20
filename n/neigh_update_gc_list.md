# Function: <code>neigh_update_gc_list</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818c76ee)
Location: net/core/neighbour.c:131
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (ffffffff81913dc4)
Location: net/core/neighbour.c:131
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (ffffffff81946434)
Location: net/core/neighbour.c:128
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void neigh_update_gc_list(struct neighbour *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a11040)
Location: net/core/neighbour.c:128
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
**Symbols:**

```
ffffffff81a11040-ffffffff81a11115: neigh_update_gc_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void neigh_update_gc_list(struct neighbour *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a113b0)
Location: net/core/neighbour.c:128
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
```
**Symbols:**

```
ffffffff81a113b0-ffffffff81a11486: neigh_update_gc_list (STB_LOCAL)
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
In net/core/neighbour.c (ffffffff819fd3eb)
Location: net/core/neighbour.c:127
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (ffffffff81aaf761)
Location: net/core/neighbour.c:127
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (ffffffff81c286f5)
Location: net/core/neighbour.c:129
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (ffffffff81ddb30d)
Location: net/core/neighbour.c:129
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (ffffffff81e4bde2)
Location: net/core/neighbour.c:129
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (ffffffff81f0aaf2)
Location: net/core/neighbour.c:129
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (ffff800010be5efc)
Location: net/core/neighbour.c:128
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (c0cfea20)
Location: net/core/neighbour.c:128
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (c000000000cc7ad0)
Location: net/core/neighbour.c:128
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (ffffffe00076af44)
Location: net/core/neighbour.c:128
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (ffffffff818e6404)
Location: net/core/neighbour.c:128
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (ffffffff818a0244)
Location: net/core/neighbour.c:128
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (ffffffff81937434)
Location: net/core/neighbour.c:128
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
In net/core/neighbour.c (ffffffff81958c1b)
Location: net/core/neighbour.c:128
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
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
