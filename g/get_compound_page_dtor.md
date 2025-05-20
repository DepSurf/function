# Function: <code>get_compound_page_dtor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119ca8e)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffffffff811a2354)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/hugetlb.c (ffffffff811dc5d1)
Location: include/linux/mm.h:547
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b299e)
Location: include/linux/mm.h:594
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffffffff811b7e66)
Location: include/linux/mm.h:594
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/hugetlb.c (ffffffff811fa831)
Location: include/linux/mm.h:594
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
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
In mm/swap.c (ffffffff811c302e)
Location: include/linux/mm.h:581
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffffffff811c84c8)
Location: include/linux/mm.h:581
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/hugetlb.c (ffffffff8120b261)
Location: include/linux/mm.h:581
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
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
In mm/swap.c (ffffffff811cb48e)
Location: include/linux/mm.h:637
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffffffff811d0e77)
Location: include/linux/mm.h:637
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/hugetlb.c (ffffffff812167c1)
Location: include/linux/mm.h:637
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
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
In mm/swap.c (ffffffff811e03ce)
Location: include/linux/mm.h:654
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffffffff811e6367)
Location: include/linux/mm.h:654
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/hugetlb.c (ffffffff81231471)
Location: include/linux/mm.h:654
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
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
In mm/swap.c (ffffffff81201346)
Location: include/linux/mm.h:696
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffffffff812078d9)
Location: include/linux/mm.h:696
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/hugetlb.c (ffffffff81254371)
Location: include/linux/mm.h:696
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
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
In mm/swap.c (ffffffff812145f6)
Location: include/linux/mm.h:724
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffffffff8121a45d)
Location: include/linux/mm.h:724
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/hugetlb.c (ffffffff81268756)
Location: include/linux/mm.h:724
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
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
In mm/swap.c (ffffffff81223ca7)
Location: include/linux/mm.h:790
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffffffff8122c7e9)
Location: include/linux/mm.h:790
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/hugetlb.c (ffffffff81283836)
Location: include/linux/mm.h:790
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
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
In mm/swap.c (ffffffff81231a37)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffffffff8123aa01)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/hugetlb.c (ffffffff812933d6)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
In mm/swap.c (ffff8000102c0bf4)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffff8000102cb93c)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/hugetlb.c (ffff8000103313e0)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
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
In mm/swap.c (c04ecd00)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (c04f57ac)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
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
In mm/swap.c (c00000000037b3c8)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (c000000000388ad4)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/hugetlb.c (c00000000040a130)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
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
In mm/swap.c (ffffffe0001e2c0c)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffffffe0001ea5f6)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/hugetlb.c (ffffffe00022e4ea)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
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
In mm/swap.c (ffffffff8122a087)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffffffff81233051)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/hugetlb.c (ffffffff8128b9b6)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
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
In mm/swap.c (ffffffff8121d1a7)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffffffff812260eb)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/hugetlb.c (ffffffff8127d7e6)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
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
In mm/swap.c (ffffffff81227e27)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffffffff81230df1)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/hugetlb.c (ffffffff812897c6)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
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
In mm/swap.c (ffffffff81237167)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/swap.c:__put_compound_page
```
```
In mm/vmscan.c (ffffffff8124023b)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/hugetlb.c (ffffffff812995a6)
Location: include/linux/mm.h:785
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHeadHuge
```
</details>
</li>
</ul>

## Differences
