# Function: <code>__ClearPageLocked</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a1075)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/vmscan.c (ffffffff811b9964)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swap_state.c (ffffffff811f0960)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff811fb43f)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b0c75)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/vmscan.c (ffffffff811c9fd3)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swap_state.c (ffffffff81201362)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8120bf3f)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b81a5)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/vmscan.c (ffffffff811d2aaa)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swap_state.c (ffffffff8120c20d)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812175ef)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cc895)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/vmscan.c (ffffffff811e82bc)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swap_state.c (ffffffff812258d1)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8123229f)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ed676)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/vmscan.c (ffffffff8120969b)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/swap_state.c (ffffffff81247e73)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812552f0)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fec2c)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap_state.c (ffffffff8125c459)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812696d8)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81215f28)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap_state.c (ffffffff81277644)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81284856)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
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
In mm/filemap.c (ffffffff81223828)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap_state.c (ffffffff8128712b)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812943f6)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
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
In mm/filemap.c (ffffffff81250ef8)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/hugetlb.c (ffffffff812c77e6)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
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
In mm/filemap.c (ffffffff8125b238)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/hugetlb.c (ffffffff812d3356)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
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
In mm/filemap.c (ffffffff8125eec8)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/hugetlb.c (ffffffff812da096)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
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
In mm/filemap.c (ffffffff8129c2d8)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/hugetlb.c (ffffffff81320e53)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
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
In mm/hugetlb.c (ffffffff8138dbbe)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/filemap.c (ffff8000102b122c)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap_state.c (ffff800010321c44)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffff800010332ca8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
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
In mm/filemap.c (c04ddb08)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap_state.c (c053a33c)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
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
In mm/filemap.c (c000000000366830)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap_state.c (c0000000003f7470)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (c00000000040d7f0)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
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
In mm/filemap.c (ffffffe0001d6a2e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap_state.c (ffffffe000222d58)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffe00022f38a)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
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
In mm/filemap.c (ffffffff8121be78)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap_state.c (ffffffff8127f77b)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8128c9d6)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
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
In mm/filemap.c (ffffffff8120f068)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap_state.c (ffffffff8127159b)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8127e7f6)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
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
In mm/filemap.c (ffffffff81219c18)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap_state.c (ffffffff8127d51b)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8128a7e6)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
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
In mm/filemap.c (ffffffff81228d18)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap_state.c (ffffffff8128d0da)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8129a5d4)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
</details>
</li>
</ul>

## Differences
