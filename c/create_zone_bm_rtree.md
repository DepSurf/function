# Function: <code>create_zone_bm_rtree</code>

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
In kernel/power/snapshot.c (ffffffff810d0d31)
Location: kernel/power/snapshot.c:428
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
In kernel/power/snapshot.c (ffffffff810d5a49)
Location: kernel/power/snapshot.c:496
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
In kernel/power/snapshot.c (ffffffff810dc5c9)
Location: kernel/power/snapshot.c:496
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
In kernel/power/snapshot.c (ffffffff810db6c5)
Location: kernel/power/snapshot.c:498
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
In kernel/power/snapshot.c (ffffffff810e38e5)
Location: kernel/power/snapshot.c:500
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
In kernel/power/snapshot.c (ffffffff810ebba3)
Location: kernel/power/snapshot.c:500
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
In kernel/power/snapshot.c (ffffffff810f7236)
Location: kernel/power/snapshot.c:500
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
In kernel/power/snapshot.c (ffffffff810ff79f)
Location: kernel/power/snapshot.c:498
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
In kernel/power/snapshot.c (ffffffff8110bbff)
Location: kernel/power/snapshot.c:498
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff8111698c)
Location: kernel/power/snapshot.c:497
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
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
In kernel/power/snapshot.c (ffffffff81112e0c)
Location: kernel/power/snapshot.c:531
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mem_zone_bm_rtree *create_zone_bm_rtree(gfp_t gfp_mask, int safe_needed, struct chain_allocator *ca, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81113600)
Location: kernel/power/snapshot.c:531
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff81113600-ffffffff811139f9: create_zone_bm_rtree (STB_LOCAL)
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
In kernel/power/snapshot.c (ffffffff8113383f)
Location: kernel/power/snapshot.c:531
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
In kernel/power/snapshot.c (ffffffff811556e8)
Location: kernel/power/snapshot.c:535
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
In kernel/power/snapshot.c (ffffffff811856e8)
Location: kernel/power/snapshot.c:535
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
In kernel/power/snapshot.c (ffffffff81196458)
Location: kernel/power/snapshot.c:535
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
In kernel/power/snapshot.c (ffffffff811a4e78)
Location: kernel/power/snapshot.c:536
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
In kernel/power/snapshot.c (c03be460)
Location: kernel/power/snapshot.c:498
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
In kernel/power/snapshot.c (ffffffff81103e1f)
Location: kernel/power/snapshot.c:497
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
In kernel/power/snapshot.c (ffffffff810f50bf)
Location: kernel/power/snapshot.c:498
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
In kernel/power/snapshot.c (ffffffff811020cf)
Location: kernel/power/snapshot.c:498
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
In kernel/power/snapshot.c (ffffffff8110d49f)
Location: kernel/power/snapshot.c:498
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
</ul>
