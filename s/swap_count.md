# Function: <code>swap_count</code>

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
In mm/swapfile.c (ffffffff811d3bda)
Location: mm/swapfile.c:95
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff811f19fa)
Location: mm/swapfile.c:95
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff812023ea)
Location: mm/swapfile.c:95
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff8120d7a0)
Location: mm/swapfile.c:99
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff81227771)
Location: mm/swapfile.c:101
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff81249cbe)
Location: mm/swapfile.c:101
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff8125e315)
Location: mm/swapfile.c:101
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff8127948b)
Location: mm/swapfile.c:111
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff81288f6b)
Location: mm/swapfile.c:111
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff812bbecb)
Location: mm/swapfile.c:110
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff812cb847)
Location: mm/swapfile.c:110
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff812d23e6)
Location: mm/swapfile.c:109
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff81317cb6)
Location: mm/swapfile.c:109
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff81383354)
Location: mm/swapfile.c:111
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_free_swap
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
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
In mm/swapfile.c (ffffffff81400d54)
Location: mm/swapfile.c:115
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:folio_free_swap
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
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
In mm/swapfile.c (ffffffff81433c34)
Location: mm/swapfile.c:116
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swap_swapcount
  - mm/swapfile.c:__swap_count
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
In mm/swapfile.c (ffffffff8146d074)
Location: mm/swapfile.c:118
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swap_swapcount
  - mm/swapfile.c:__swap_count
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
In mm/swapfile.c (ffff800010324070)
Location: mm/swapfile.c:111
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (c053be40)
Location: mm/swapfile.c:111
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (c0000000003f9e24)
Location: mm/swapfile.c:111
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffe00022480a)
Location: mm/swapfile.c:111
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff8128154b)
Location: mm/swapfile.c:111
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff812733bb)
Location: mm/swapfile.c:111
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff8127f35b)
Location: mm/swapfile.c:111
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
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
In mm/swapfile.c (ffffffff8128f02c)
Location: mm/swapfile.c:111
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:page_swapcount
```
</details>
</li>
</ul>

## Differences
