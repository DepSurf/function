# Function: <code>PageHWPoison</code>

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
In mm/filemap.c (ffffffff8118da98)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/page_alloc.c (ffffffff8119280b)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_prepare
  - mm/page_alloc.c:free_pages_prepare
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/memory.c (ffffffff811bc132)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/rmap.c (ffffffff811cb217)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811d1e10)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/hugetlb.c (ffffffff811df0f4)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/sparse.c (ffffffff811e3899)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/memory-failure.c (ffffffff81201b81)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/page_isolation.c (ffffffff81204022)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff811a191d)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/page_alloc.c (ffffffff811acc86)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/memory.c (ffffffff811d6f86)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff811e82e7)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811ef8f1)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/hugetlb.c (ffffffff811fd6e6)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/sparse.c (ffffffff812022df)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/memory-failure.c (ffffffff81227aec)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff81228fd2)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff811b1772)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/page_alloc.c (ffffffff811bd23e)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/memory.c (ffffffff811e9631)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff811f970b)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81200278)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/hugetlb.c (ffffffff8120e1ad)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/sparse.c (ffffffff8121411f)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/memory-failure.c (ffffffff8123a075)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff8123b567)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff811b799a)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/page_alloc.c (ffffffff811c549b)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/memory.c (ffffffff811f47a1)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8120434a)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8120add0)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/hugetlb.c (ffffffff8121891d)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffffffff8121f512)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/memory-failure.c (ffffffff81245c63)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff81247182)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff811cbf22)
Location: include/linux/page-flags.h:362
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/page_alloc.c (ffffffff811da246)
Location: include/linux/page-flags.h:362
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/memory.c (ffffffff8120c58b)
Location: include/linux/page-flags.h:362
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8121d119)
Location: include/linux/page-flags.h:362
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8122413b)
Location: include/linux/page-flags.h:362
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/hugetlb.c (ffffffff81233890)
Location: include/linux/page-flags.h:362
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffffffff8123a74b)
Location: include/linux/page-flags.h:362
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/memory-failure.c (ffffffff81265c85)
Location: include/linux/page-flags.h:362
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812672c5)
Location: include/linux/page-flags.h:362
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff811ecf02)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/page_alloc.c (ffffffff811faaec)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/memory.c (ffffffff8122d24b)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8123f007)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81244e9a)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/hugetlb.c (ffffffff81256860)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffffffff8125dcca)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/memory-failure.c (ffffffff8128a03a)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/page_isolation.c (ffffffff8128bbc1)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff811fd1ad)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/page_alloc.c (ffffffff8120d26c)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/memory.c (ffffffff8123d17a)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8125361b)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812594ed)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/hugetlb.c (ffffffff8126adb1)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffffffff81272600)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/memory_hotplug.c (ffffffff81a21b17)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memory-failure.c (ffffffff8129efac)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/page_isolation.c (ffffffff812a0b21)
Location: include/linux/page-flags.h:381
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff81215611)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/memory.c (ffffffff8124ee1a)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff81265884)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff812736ba)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff8127542e)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/hugetlb.c (ffffffff81285fbe)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffffffff8128dd2f)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory_hotplug.c (ffffffff8129c4d0)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/memory-failure.c (ffffffff812ba686)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/page_isolation.c (ffffffff812bbdb6)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff812228a3)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/memory.c (ffffffff8125d3fa)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff81274199)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff8128252a)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff81284438)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/hugetlb.c (ffffffff81295b9e)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffffffff8129da2f)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory_hotplug.c (ffffffff812abf2f)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/memory-failure.c (ffffffff812cc566)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812cdc96)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff8124ffb7)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/memory.c (ffffffff8128be7a)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff812a541a)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff812b46b2)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff812b5d27)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/madvise.c:madvise_inject_error
```
```
In mm/hugetlb.c (ffffffff812c91eb)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffffffff812d16c4)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory_hotplug.c (ffffffff812e138d)
Location: include/linux/page-flags.h:422
Inline: True
```
```
In mm/memory-failure.c (ffffffff8130288e)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/page_isolation.c (ffffffff81303fd7)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff8125a1e3)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/memory.c (ffffffff81296dfa)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff812b08ae)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff812c0097)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/hugetlb.c (ffffffff812d4e18)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffffffff812dd1e4)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory_hotplug.c (ffffffff812ec079)
Location: include/linux/page-flags.h:430
Inline: True
```
```
In mm/memory-failure.c (ffffffff8130ec6b)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/page_isolation.c (ffffffff8130fea2)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff8125fde3)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
```
```
In mm/memory.c (ffffffff8129ca4a)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff812b5edb)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff812c5807)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memory_hotplug.c (ffffffff812c69ae)
Location: include/linux/page-flags.h:430
Inline: True
```
```
In mm/hugetlb.c (ffffffff812dbc38)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffffffff812e4a3a)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory-failure.c (ffffffff81314ffe)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/page_isolation.c (ffffffff81315f83)
Location: include/linux/page-flags.h:430
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff8129c753)
Location: include/linux/page-flags.h:444
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:next_uptodate_page
```
```
In mm/memory.c (ffffffff812dd81a)
Location: include/linux/page-flags.h:444
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff812f857c)
Location: include/linux/page-flags.h:444
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81309ea4)
Location: include/linux/page-flags.h:444
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memory_hotplug.c (ffffffff8130b451)
Location: include/linux/page-flags.h:444
Inline: True
```
```
In mm/hugetlb.c (ffffffff81322e40)
Location: include/linux/page-flags.h:444
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffffffff8132bcba)
Location: include/linux/page-flags.h:444
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory-failure.c (ffffffff813610a6)
Location: include/linux/page-flags.h:444
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/page_isolation.c (ffffffff81362089)
Location: include/linux/page-flags.h:444
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/proc/kcore.c (ffffffff814353ed)
Location: include/linux/page-flags.h:444
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
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
In mm/filemap.c (ffffffff812f38ca)
Location: include/linux/page-flags.h:597
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/shmem.c (ffffffff81319925)
Location: include/linux/page-flags.h:597
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
```
```
In mm/memory.c (ffffffff813424ea)
Location: include/linux/page-flags.h:597
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8135e607)
Location: include/linux/page-flags.h:597
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81372804)
Location: include/linux/page-flags.h:597
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memory_hotplug.c (ffffffff81373f52)
Location: include/linux/page-flags.h:597
Inline: True
```
```
In mm/hugetlb.c (ffffffff813905dc)
Location: include/linux/page-flags.h:597
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory-failure.c (ffffffff813dd764)
Location: include/linux/page-flags.h:597
Inline: True
Inline callers:
  - mm/memory-failure.c:clear_hwpoisoned_pages
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:ClearPageHWPoisonTakenOff
```
```
In mm/page_isolation.c (ffffffff813deb12)
Location: include/linux/page-flags.h:597
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/userfaultfd.c (ffffffff813e5a1c)
Location: include/linux/page-flags.h:597
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
```
```
In fs/proc/kcore.c (ffffffff814af480)
Location: include/linux/page-flags.h:597
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
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
In mm/filemap.c (ffffffff8135dc28)
Location: include/linux/page-flags.h:576
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/shmem.c (ffffffff8138d91d)
Location: include/linux/page-flags.h:576
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
```
```
In mm/memory.c (ffffffff813ba637)
Location: include/linux/page-flags.h:576
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff813d94d8)
Location: include/linux/page-flags.h:576
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff813eff64)
Location: include/linux/page-flags.h:576
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memory_hotplug.c (ffffffff813f19ee)
Location: include/linux/page-flags.h:576
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140ce89)
Location: include/linux/page-flags.h:576
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory-failure.c (ffffffff81464028)
Location: include/linux/page-flags.h:576
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:ClearPageHWPoisonTakenOff
```
```
In mm/page_isolation.c (ffffffff814657d2)
Location: include/linux/page-flags.h:576
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/userfaultfd.c (ffffffff8146d531)
Location: include/linux/page-flags.h:576
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
```
```
In fs/proc/kcore.c (ffffffff81545d3b)
Location: include/linux/page-flags.h:576
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/hugetlbfs/inode.c (ffffffff815f7b47)
Location: include/linux/page-flags.h:576
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
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
In mm/filemap.c (ffffffff8138fb04)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/shmem.c (ffffffff813c030a)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
```
```
In mm/memory.c (ffffffff813eeff7)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8140dbc9)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81423af8)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/memory_hotplug.c (ffffffff814257b1)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/swapfile.c (ffffffff81430495)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff81457e01)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/memory-failure.c (ffffffff81499ae0)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:ClearPageHWPoisonTakenOff
```
```
In mm/page_isolation.c (ffffffff8149b1c7)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/userfaultfd.c (ffffffff814a1f61)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
```
```
In fs/proc/kcore.c (ffffffff8157d897)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
```
```
In fs/hugetlbfs/inode.c (ffffffff8162fabf)
Location: include/linux/page-flags.h:570
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
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
In mm/filemap.c (ffffffff813b94d0)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
```
```
In mm/shmem.c (ffffffff813eb34f)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/shmem.c:shmem_read_mapping_page_gfp
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_begin
```
```
In mm/memory.c (ffffffff8141af08)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8143a32b)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81450a2e)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/memory_hotplug.c (ffffffff81452797)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/swapfile.c (ffffffff81468e5f)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/ksm.c (ffffffff8149289d)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/memory-failure.c (ffffffff814c92ad)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:is_raw_hwpoison_page_in_hugepage
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:ClearPageHWPoisonTakenOff
```
```
In mm/page_isolation.c (ffffffff814ca8a7)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/userfaultfd.c (ffffffff814d182e)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
```
```
In fs/proc/kcore.c (ffffffff815b62aa)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
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
In mm/filemap.c (ffff8000102afeac)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/memory.c (ffff8000102f48f8)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffff800010309dd8)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffff80001031a46c)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffff80001031e85c)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
```
```
In mm/hugetlb.c (ffff80001033489c)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffff80001033cb78)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory-failure.c (ffff800010370120)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffff8000103720c0)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (0)
Location: include/linux/page-flags.h:419
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/page-flags.h:419
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/page-flags.h:419
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/page-flags.h:419
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/page-flags.h:419
Inline: True
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
In mm/filemap.c (c000000000364e8c)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/memory.c (c0000000003bb610)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (c0000000003d9778)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (c0000000003ee1c0)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (c0000000003f2be8)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/hugetlb.c (c00000000040dc70)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (c000000000417d20)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory_hotplug.c (c00000000042e1c8)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/memory-failure.c (c000000000461c8c)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (c0000000004639ac)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (0)
Location: include/linux/page-flags.h:419
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/page-flags.h:419
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/page-flags.h:419
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/page-flags.h:419
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/page-flags.h:419
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/page-flags.h:419
Inline: True
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
In mm/filemap.c (ffffffff8121aef3)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/memory.c (ffffffff81255a4a)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8126c7e9)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff8127ab7a)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff8127ca88)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/hugetlb.c (ffffffff8128e17e)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffffffff8129600f)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory_hotplug.c (ffffffff812a450f)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/memory-failure.c (ffffffff812c4b46)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812c6276)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff8120e0f3)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/memory.c (ffffffff8124812a)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8125e842)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff8126ca5a)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff8126e938)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/hugetlb.c (ffffffff8127feea)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffffffff81287c1f)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory_hotplug.c (ffffffff81295fdf)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/memory-failure.c (ffffffff812b5b86)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812b72b6)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff81218c93)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/memory.c (ffffffff812537ea)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8126a589)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff8127891a)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff8127a828)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/hugetlb.c (ffffffff8128bf8e)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffffffff81293e1f)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory_hotplug.c (ffffffff812a231f)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/memory-failure.c (ffffffff812c2956)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812c4086)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
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
In mm/filemap.c (ffffffff81227d88)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/memory.c (ffffffff812631b9)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory.c:__do_fault
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff81279f67)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff8128850a)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/madvise.c (ffffffff8128a408)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/hugetlb.c (ffffffff8129bd7a)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/sparse.c (ffffffff812a3c7f)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
```
```
In mm/memory_hotplug.c (ffffffff812b267f)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/memory-failure.c (ffffffff812d33f6)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812d4b26)
Location: include/linux/page-flags.h:414
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
</details>
</li>
</ul>

## Differences
