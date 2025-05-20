# Function: <code>add_rtree_block</code>

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
In kernel/power/snapshot.c (ffffffff810d0dab)
Location: kernel/power/snapshot.c:357
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff810d5ac1)
Location: kernel/power/snapshot.c:426
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff810dc641)
Location: kernel/power/snapshot.c:426
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff810db73d)
Location: kernel/power/snapshot.c:428
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff810e395d)
Location: kernel/power/snapshot.c:430
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff810ebc11)
Location: kernel/power/snapshot.c:430
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff810f729a)
Location: kernel/power/snapshot.c:430
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff810ff806)
Location: kernel/power/snapshot.c:428
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff8110bc66)
Location: kernel/power/snapshot.c:428
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_rtree_block(struct mem_zone_bm_rtree *zone, gfp_t gfp_mask, int safe_needed, struct chain_allocator *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81116730)
Location: kernel/power/snapshot.c:427
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff81116730-ffffffff811168fd: add_rtree_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_rtree_block(struct mem_zone_bm_rtree *zone, gfp_t gfp_mask, int safe_needed, struct chain_allocator *ca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81112bb0)
Location: kernel/power/snapshot.c:461
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff81112bb0-ffffffff81112d7d: add_rtree_block (STB_LOCAL)
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
In kernel/power/snapshot.c (ffffffff811136a2)
Location: kernel/power/snapshot.c:461
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_zone_bm_rtree
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
In kernel/power/snapshot.c (ffffffff811338b1)
Location: kernel/power/snapshot.c:461
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff8115575d)
Location: kernel/power/snapshot.c:465
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff8118575d)
Location: kernel/power/snapshot.c:465
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff811964cd)
Location: kernel/power/snapshot.c:465
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff811a4eed)
Location: kernel/power/snapshot.c:466
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03be4c8)
Location: kernel/power/snapshot.c:428
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81103e86)
Location: kernel/power/snapshot.c:427
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff810f5126)
Location: kernel/power/snapshot.c:428
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff81102136)
Location: kernel/power/snapshot.c:428
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff8110d506)
Location: kernel/power/snapshot.c:428
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
