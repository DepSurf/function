# Function: <code>lock_cluster_or_swap_info</code>

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
In mm/swapfile.c (ffffffff8120d776)
Location: mm/swapfile.c:287
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:__swap_entry_free
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
In mm/swapfile.c (ffffffff81227734)
Location: mm/swapfile.c:299
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:__swap_entry_free
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
In mm/swapfile.c (ffffffff81249c8f)
Location: mm/swapfile.c:299
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:__swap_entry_free
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
In mm/swapfile.c (ffffffff8125e2ec)
Location: mm/swapfile.c:326
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff8127945e)
Location: mm/swapfile.c:361
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff81288f3e)
Location: mm/swapfile.c:361
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff812bbe9e)
Location: mm/swapfile.c:360
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
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
In mm/swapfile.c (ffffffff812c79be)
Location: mm/swapfile.c:373
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
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
In mm/swapfile.c (ffffffff812ce32a)
Location: mm/swapfile.c:372
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
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
In mm/swapfile.c (ffffffff8131387a)
Location: mm/swapfile.c:372
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
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
In mm/swapfile.c (ffffffff8137eeaa)
Location: mm/swapfile.c:374
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_free_swap
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
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
In mm/swapfile.c (ffffffff813fd9fa)
Location: mm/swapfile.c:378
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:folio_free_swap
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
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
In mm/swapfile.c (ffffffff8142f4df)
Location: mm/swapfile.c:379
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swap_swapcount
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
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
In mm/swapfile.c (ffffffff8146cef7)
Location: mm/swapfile.c:381
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_clear
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swap_swapcount
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
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
In mm/swapfile.c (ffff800010324034)
Location: mm/swapfile.c:361
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (c053be18)
Location: mm/swapfile.c:361
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (c0000000003f9df0)
Location: mm/swapfile.c:361
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffe0002247d8)
Location: mm/swapfile.c:361
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff8128151e)
Location: mm/swapfile.c:361
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff8127338e)
Location: mm/swapfile.c:361
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff8127f32e)
Location: mm/swapfile.c:361
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffff8128effe)
Location: mm/swapfile.c:361
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
```
</details>
</li>
</ul>

## Differences
