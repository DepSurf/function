# Function: <code>wait_on_page_locked</code>

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
In mm/filemap.c (ffffffff8118cbd9)
Location: include/linux/pagemap.h:518
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_read
  - mm/filemap.c:filemap_fault
```
```
In mm/swapfile.c (ffffffff811d55df)
Location: include/linux/pagemap.h:518
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff811dee53)
Location: include/linux/pagemap.h:518
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff811f14a6)
Location: include/linux/pagemap.h:518
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff811f65d7)
Location: include/linux/pagemap.h:518
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/filemap.c (ffffffff811a13d6)
Location: include/linux/pagemap.h:495
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
```
```
In mm/swapfile.c (ffffffff811f35da)
Location: include/linux/pagemap.h:495
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff811fd344)
Location: include/linux/pagemap.h:495
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff81211895)
Location: include/linux/pagemap.h:495
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812154b4)
Location: include/linux/pagemap.h:495
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/filemap.c (ffffffff811b0f90)
Location: include/linux/pagemap.h:506
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
```
```
In mm/swapfile.c (ffffffff81204092)
Location: include/linux/pagemap.h:506
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8120de13)
Location: include/linux/pagemap.h:506
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff81223a51)
Location: include/linux/pagemap.h:506
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81227aa7)
Location: include/linux/pagemap.h:506
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/filemap.c (ffffffff811b83e2)
Location: include/linux/pagemap.h:514
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
```
```
In mm/swapfile.c (ffffffff8120f735)
Location: include/linux/pagemap.h:514
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81219c30)
Location: include/linux/pagemap.h:514
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff8122f3aa)
Location: include/linux/pagemap.h:514
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81233d15)
Location: include/linux/pagemap.h:514
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/filemap.c (ffffffff811ccb80)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
```
```
In mm/swapfile.c (ffffffff8122afa3)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81234c8f)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff8124cf91)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8125166b)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/filemap.c (ffffffff811edcd7)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
```
```
In mm/swapfile.c (ffffffff8124c229)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81257bc2)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff81270a99)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812759e0)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/filemap.c (ffffffff811ff290)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/swapfile.c (ffffffff8126072c)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8126c27b)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/filemap.c (ffffffff812162f2)
Location: include/linux/pagemap.h:514
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/hugetlb.c (ffffffff81287639)
Location: include/linux/pagemap.h:514
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/filemap.c (ffffffff81223c02)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/hugetlb.c (ffffffff81297249)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/filemap.c (ffffffff81252bd3)
Location: include/linux/pagemap.h:565
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/hugetlb.c (ffffffff812ca84f)
Location: include/linux/pagemap.h:565
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/filemap.c (ffffffff8125d7a3)
Location: include/linux/pagemap.h:670
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/hugetlb.c (ffffffff812d647f)
Location: include/linux/pagemap.h:670
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/filemap.c (ffffffff81260566)
Location: include/linux/pagemap.h:686
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/hugetlb.c (ffffffff812dd629)
Location: include/linux/pagemap.h:686
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/filemap.c (ffffffff8129cf56)
Location: include/linux/pagemap.h:685
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/hugetlb.c (ffffffff813247cd)
Location: include/linux/pagemap.h:685
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/hugetlb.c (ffffffff81392c9a)
Location: include/linux/pagemap.h:1038
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/zsmalloc.c (ffffffff813e28b3)
Location: include/linux/pagemap.h:1038
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
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
In mm/hugetlb.c (ffffffff814116eb)
Location: include/linux/pagemap.h:1031
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/zsmalloc.c (ffffffff81469e13)
Location: include/linux/pagemap.h:1031
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
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
In mm/zsmalloc.c (ffffffff8149f013)
Location: include/linux/pagemap.h:1042
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
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
In mm/zsmalloc.c (ffffffff814ce773)
Location: include/linux/pagemap.h:1133
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
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
In mm/filemap.c (ffff8000102b1610)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/hugetlb.c (ffff80001033508c)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/filemap.c (c04ddfa0)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
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
In mm/filemap.c (c000000000366e50)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/hugetlb.c (c00000000040e768)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/filemap.c (ffffffe0001d6cdc)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/hugetlb.c (ffffffe000231860)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/filemap.c (ffffffff8121c252)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/hugetlb.c (ffffffff8128f829)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/filemap.c (ffffffff8120f442)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/hugetlb.c (ffffffff812814f2)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/filemap.c (ffffffff81219ff2)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/hugetlb.c (ffffffff8128d639)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/filemap.c (ffffffff812290e2)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/hugetlb.c (ffffffff8129d3cf)
Location: include/linux/pagemap.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
</details>
</li>
</ul>

## Differences
