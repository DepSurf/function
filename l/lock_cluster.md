# Function: <code>lock_cluster</code>

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
In mm/swapfile.c (ffffffff8121164c)
Location: mm/swapfile.c:268
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff8122bfa3)
Location: mm/swapfile.c:280
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff8124e473)
Location: mm/swapfile.c:280
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff81262830)
Location: mm/swapfile.c:303
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff8127d72c)
Location: mm/swapfile.c:338
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff8128d1cc)
Location: mm/swapfile.c:338
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff812bfc6c)
Location: mm/swapfile.c:337
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:swap_alloc_cluster
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff812cb81c)
Location: mm/swapfile.c:350
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:swap_alloc_cluster
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff812d23c3)
Location: mm/swapfile.c:349
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff81317c93)
Location: mm/swapfile.c:349
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff8138332c)
Location: mm/swapfile.c:351
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_free_swap
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff81400d2c)
Location: mm/swapfile.c:355
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:folio_free_swap
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff81433c0c)
Location: mm/swapfile.c:356
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swap_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff8146d04c)
Location: mm/swapfile.c:358
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swapcache_clear
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:swap_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:swap_free_cluster
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffff80001032896c)
Location: mm/swapfile.c:338
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (c053fdd4)
Location: mm/swapfile.c:338
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (c0000000003ffca0)
Location: mm/swapfile.c:338
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffe00022872a)
Location: mm/swapfile.c:338
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff812857ac)
Location: mm/swapfile.c:338
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff8127761c)
Location: mm/swapfile.c:338
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff812835bc)
Location: mm/swapfile.c:338
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
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
In mm/swapfile.c (ffffffff8129329c)
Location: mm/swapfile.c:338
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:swap_page_trans_huge_swapped
  - mm/swapfile.c:swp_swapcount
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:page_swapcount
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:split_swap_cluster
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_try_ssd_cluster
  - mm/swapfile.c:swap_do_scheduled_discard
```
</details>
</li>
</ul>

## Differences
