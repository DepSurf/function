# Function: <code>put_swap_device</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff8125766c)
Location: include/linux/swap.h:475
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff8127754a)
Location: include/linux/swap.h:475
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff8127d81a)
Location: include/linux/swap.h:475
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff81265bbc)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff8128702a)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff8128d2ba)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff81295efd)
Location: include/linux/swap.h:484
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff812b95b7)
Location: include/linux/swap.h:484
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff812bfd5a)
Location: include/linux/swap.h:484
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812c502e)
Location: include/linux/swap.h:487
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff812cb90a)
Location: include/linux/swap.h:487
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812cbce3)
Location: include/linux/swap.h:512
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff812d2413)
Location: include/linux/swap.h:512
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e22d2)
Location: include/linux/swap.h:519
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff81310e5a)
Location: include/linux/swap.h:519
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81317ce3)
Location: include/linux/swap.h:519
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81343f4b)
Location: include/linux/swap.h:505
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff8137bce9)
Location: include/linux/swap.h:505
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8138337d)
Location: include/linux/swap.h:505
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bbd8c)
Location: include/linux/swap.h:511
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff813f9629)
Location: include/linux/swap.h:511
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/swapfile.c (ffffffff81400d7d)
Location: include/linux/swap.h:511
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813beb2d)
Location: include/linux/swap.h:506
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff813f07aa)
Location: include/linux/swap.h:506
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff8142c3a4)
Location: include/linux/swap.h:506
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In mm/swapfile.c (ffffffff81433c5d)
Location: include/linux/swap.h:506
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e9b32)
Location: include/linux/swap.h:497
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff81420494)
Location: include/linux/swap.h:497
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff81465add)
Location: include/linux/swap.h:497
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
```
```
In mm/swapfile.c (ffffffff8146d09f)
Location: include/linux/swap.h:497
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffff8000102fcdb0)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffff800010321b1c)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffff800010328a70)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (c051c4b4)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (c053a244)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (c053fedc)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (c0000000003c7d80)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (c0000000003f72e0)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (c0000000003ffee0)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffe00020b9ca)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffe000222c7c)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffe00022886a)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff8125e20c)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff8127f67a)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff8128589a)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff8125069c)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff8127149a)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff8127770a)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff8125bfac)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff8127d41a)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff812836aa)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mincore.c (ffffffff8126b99c)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/swap_state.c (ffffffff8128cfea)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff81293384)
Location: include/linux/swap.h:477
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
</details>
</li>
</ul>

## Differences
