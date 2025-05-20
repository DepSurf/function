# Function: <code>split_huge_page_to_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f7090)
Location: mm/huge_memory.c:1957
Inline: False
Direct callers:
  - mm/swap_state.c:add_to_swap
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff811f7090-ffffffff811f7827: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81217840)
Location: mm/huge_memory.c:1978
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/swap_state.c:add_to_swap
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81217840-ffffffff81217f3b: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81229df0)
Location: mm/huge_memory.c:2109
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/swap_state.c:add_to_swap
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81229df0-ffffffff8122a4df: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81235a10)
Location: mm/huge_memory.c:2448
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81235a10-ffffffff81236138: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81254760)
Location: mm/huge_memory.c:2600
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81254760-ffffffff81254f76: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812785c0)
Location: mm/huge_memory.c:2592
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812785c0-ffffffff81278dc8: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128cc20)
Location: mm/huge_memory.c:2611
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8128cc20-ffffffff8128d479: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a7930)
Location: mm/huge_memory.c:2672
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
**Symbols:**

```
ffffffff812a7930-ffffffff812a7e0d: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b8dd0)
Location: mm/huge_memory.c:2695
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812b8dd0-ffffffff812b92f4: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ed980)
Location: mm/huge_memory.c:2605
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812ed980-ffffffff812ede57: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f9050)
Location: mm/huge_memory.c:2662
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
**Symbols:**

```
ffffffff812f9050-ffffffff812f94c6: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ff650)
Location: mm/huge_memory.c:2673
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
**Symbols:**

```
ffffffff812ff650-ffffffff812ffa9e: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81349260)
Location: mm/huge_memory.c:2612
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
**Symbols:**

```
ffffffff81349260-ffffffff813496e5: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813bf550)
Location: mm/huge_memory.c:2567
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
**Symbols:**

```
ffffffff813bf550-ffffffff813bfe38: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81441ab0)
Location: mm/huge_memory.c:2652
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81441ab0-ffffffff81442111: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81477480)
Location: mm/huge_memory.c:2645
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:try_to_split_thp_page
```
**Symbols:**

```
ffffffff81477480-ffffffff81477a2e: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a6bf0)
Location: mm/huge_memory.c:2978
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:try_to_split_thp_page
  - mm/userfaultfd.c:move_pages_pte
```
**Symbols:**

```
ffffffff814a6bf0-ffffffff814a71a8: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff8000103594c0)
Location: mm/huge_memory.c:2695
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
**Symbols:**

```
ffff8000103594c0-ffff800010359a5c: split_huge_page_to_list (STB_GLOBAL)
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
In mm/vmscan.c (0)
Location: include/linux/huge_mm.h:324
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/huge_mm.h:324
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c0000000004429f0)
Location: mm/huge_memory.c:2695
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
c0000000004429f0-c0000000004431a4: split_huge_page_to_list (STB_GLOBAL)
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
In mm/vmscan.c (0)
Location: include/linux/huge_mm.h:324
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/huge_mm.h:324
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b13b0)
Location: mm/huge_memory.c:2695
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812b13b0-ffffffff812b18d4: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a2780)
Location: mm/huge_memory.c:2695
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812a2780-ffffffff812a2ca4: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812af1c0)
Location: mm/huge_memory.c:2695
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812af1c0-ffffffff812af6e4: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int split_huge_page_to_list(struct page *page, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bf510)
Location: mm/huge_memory.c:2695
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/gup.c:follow_page_pte
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812bf510-ffffffff812bfa30: split_huge_page_to_list (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
