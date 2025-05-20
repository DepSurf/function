# Function: <code>zone_spans_pfn</code>

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
In mm/page_alloc.c (ffffffff81192a7e)
Location: include/linux/mmzone.h:554
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:is_pageblock_removable_nolock
```
```
In mm/hugetlb.c (ffffffff811dbd17)
Location: include/linux/mmzone.h:554
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
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
In mm/page_alloc.c (ffffffff811ac53a)
Location: include/linux/mmzone.h:542
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff811fa025)
Location: include/linux/mmzone.h:542
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
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
In mm/page_alloc.c (ffffffff811bcb1a)
Location: include/linux/mmzone.h:516
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff8120aad0)
Location: include/linux/mmzone.h:516
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
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
In mm/page_alloc.c (ffffffff811c4cea)
Location: include/linux/mmzone.h:520
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff81215e20)
Location: include/linux/mmzone.h:520
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
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
In mm/page_alloc.c (ffffffff811d9ace)
Location: include/linux/mmzone.h:529
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff81230a0d)
Location: include/linux/mmzone.h:529
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
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
In mm/page_alloc.c (ffffffff811f6420)
Location: include/linux/mmzone.h:530
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff812525b5)
Location: include/linux/mmzone.h:530
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff8126c4f5)
Location: include/linux/mmzone.h:530
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/page_alloc.c (ffffffff8120870b)
Location: include/linux/mmzone.h:539
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff81266815)
Location: include/linux/mmzone.h:539
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81280eac)
Location: include/linux/mmzone.h:539
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/page_alloc.c (ffffffff8126eb6b)
Location: include/linux/mmzone.h:595
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff81281aed)
Location: include/linux/mmzone.h:595
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff8129d323)
Location: include/linux/mmzone.h:595
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/page_alloc.c (ffffffff8127d9ab)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff81291503)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812acaf3)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/page_alloc.c (ffffffff812b41ff)
Location: include/linux/mmzone.h:561
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff812e1af5)
Location: include/linux/mmzone.h:561
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
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
In mm/page_alloc.c (ffffffff812bfc7f)
Location: include/linux/mmzone.h:612
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff812eca55)
Location: include/linux/mmzone.h:612
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
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
In mm/page_alloc.c (ffffffff812c53da)
Location: include/linux/mmzone.h:661
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff812c75db)
Location: include/linux/mmzone.h:661
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
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
In mm/page_alloc.c (ffffffff8130993a)
Location: include/linux/mmzone.h:697
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/memory_hotplug.c (ffffffff8130c359)
Location: include/linux/mmzone.h:697
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
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
In mm/page_alloc.c (ffffffff813721a6)
Location: include/linux/mmzone.h:718
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (ffffffff813ef9d6)
Location: include/linux/mmzone.h:912
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (ffffffff8142354b)
Location: include/linux/mmzone.h:1023
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (ffffffff8145047b)
Location: include/linux/mmzone.h:1033
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (ffff8000103152a0)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffff80001032e668)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
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
In mm/page_alloc.c (c052fb6c)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
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
In mm/page_alloc.c (c0000000003e70cc)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (c000000000407684)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (c00000000042efe0)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/page_alloc.c (ffffffe00021bd16)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffe00022c61e)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
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
In mm/page_alloc.c (ffffffff81275ffb)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff81289ae3)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812a50d3)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/page_alloc.c (ffffffff81267f4b)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff8127b913)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff81296ba3)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/page_alloc.c (ffffffff81273d9b)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff812878f3)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812a2ee3)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
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
In mm/page_alloc.c (ffffffff8128389b)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff81297e90)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/memory_hotplug.c (ffffffff812b3173)
Location: include/linux/mmzone.h:596
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:is_mem_section_removable
```
</details>
</li>
</ul>

## Differences
