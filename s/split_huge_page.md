# Function: <code>split_huge_page</code>

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
In mm/ksm.c (ffffffff811e53c1)
Location: include/linux/huge_mm.h:99
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff811f2779)
Location: include/linux/huge_mm.h:99
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff811f82c2)
Location: include/linux/huge_mm.h:99
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff81202546)
Location: include/linux/huge_mm.h:99
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:soft_offline_page
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
In mm/shmem.c (ffffffff811bfe12)
Location: include/linux/huge_mm.h:94
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff811d51a6)
Location: include/linux/huge_mm.h:94
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffffffff811eeced)
Location: include/linux/huge_mm.h:94
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/mempolicy.c (ffffffff811fefbc)
Location: include/linux/huge_mm.h:94
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81203ef0)
Location: include/linux/huge_mm.h:94
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff81212468)
Location: include/linux/huge_mm.h:94
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812180d2)
Location: include/linux/huge_mm.h:94
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81227eea)
Location: include/linux/huge_mm.h:94
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
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
In mm/shmem.c (ffffffff811d0688)
Location: include/linux/huge_mm.h:98
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff811e51c1)
Location: include/linux/huge_mm.h:98
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffffffff811ff61d)
Location: include/linux/huge_mm.h:98
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/mempolicy.c (ffffffff81210801)
Location: include/linux/huge_mm.h:98
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81215edf)
Location: include/linux/huge_mm.h:98
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81224657)
Location: include/linux/huge_mm.h:98
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff8122a672)
Location: include/linux/huge_mm.h:98
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8123a494)
Location: include/linux/huge_mm.h:98
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
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
In mm/shmem.c (ffffffff811d8b22)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff811ef087)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffffffff8120a425)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/mempolicy.c (ffffffff8121c11f)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812215ef)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8122fe36)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812362ad)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81245f25)
Location: include/linux/huge_mm.h:138
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
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
In mm/shmem.c (ffffffff811ef1c8)
Location: include/linux/huge_mm.h:139
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8120697e)
Location: include/linux/huge_mm.h:139
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffffffff81223693)
Location: include/linux/huge_mm.h:139
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/mempolicy.c (0)
Location: include/linux/huge_mm.h:139
Inline: True
```
```
In mm/ksm.c (ffffffff8123c8ff)
Location: include/linux/huge_mm.h:139
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8124b24b)
Location: include/linux/huge_mm.h:139
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812550e9)
Location: include/linux/huge_mm.h:139
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81265f5d)
Location: include/linux/huge_mm.h:139
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
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
In mm/shmem.c (ffffffff8120f036)
Location: include/linux/huge_mm.h:140
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8122646b)
Location: include/linux/huge_mm.h:140
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffffffff8124648f)
Location: include/linux/huge_mm.h:140
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff8126205d)
Location: include/linux/huge_mm.h:140
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8126de66)
Location: include/linux/huge_mm.h:140
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81278f46)
Location: include/linux/huge_mm.h:140
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8128a3ce)
Location: include/linux/huge_mm.h:140
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/shmem.c (ffffffff812221d6)
Location: include/linux/huge_mm.h:146
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8123a7c9)
Location: include/linux/huge_mm.h:146
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffffffff8125a8b5)
Location: include/linux/huge_mm.h:146
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff812768de)
Location: include/linux/huge_mm.h:146
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81282cd6)
Location: include/linux/huge_mm.h:146
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8128d5f6)
Location: include/linux/huge_mm.h:146
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8129f376)
Location: include/linux/huge_mm.h:146
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
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
In mm/shmem.c (ffffffff81231851)
Location: include/linux/huge_mm.h:161
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8124badc)
Location: include/linux/huge_mm.h:161
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffffffff81275891)
Location: include/linux/huge_mm.h:161
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff81291a18)
Location: include/linux/huge_mm.h:161
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff812a7f7d)
Location: include/linux/huge_mm.h:161
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812b98fe)
Location: include/linux/huge_mm.h:161
Inline: True
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
In mm/shmem.c (ffffffff8123f911)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81259fcc)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffffffff81284861)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/ksm.c (ffffffff812a1798)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812ae775)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812b9471)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812cc1a6)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/shmem.c (ffffffff8126d82f)
Location: include/linux/huge_mm.h:202
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff812884ec)
Location: include/linux/huge_mm.h:202
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffffffff812b6a0c)
Location: include/linux/huge_mm.h:202
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/ksm.c (ffffffff812d64a9)
Location: include/linux/huge_mm.h:202
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812e3dd2)
Location: include/linux/huge_mm.h:202
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812edfd6)
Location: include/linux/huge_mm.h:202
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8130229e)
Location: include/linux/huge_mm.h:202
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/shmem.c (ffffffff81277f23)
Location: include/linux/huge_mm.h:185
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff812921d5)
Location: include/linux/huge_mm.h:185
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffffffff812c2c58)
Location: include/linux/huge_mm.h:185
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/ksm.c (ffffffff812e1fbb)
Location: include/linux/huge_mm.h:185
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812efb31)
Location: include/linux/huge_mm.h:185
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812f9646)
Location: include/linux/huge_mm.h:185
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8130d058)
Location: include/linux/huge_mm.h:185
Inline: True
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
In mm/shmem.c (ffffffff8128050d)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/madvise.c (ffffffff812c9ad4)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/ksm.c (ffffffff812e974b)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812f54b4)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81300171)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81312f38)
Location: include/linux/huge_mm.h:190
Inline: True
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
In mm/shmem.c (ffffffff812bc1e1)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/madvise.c (ffffffff8130eaf4)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/ksm.c (ffffffff81331684)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8133fab4)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81349dc1)
Location: include/linux/huge_mm.h:190
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8135eac8)
Location: include/linux/huge_mm.h:190
Inline: True
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
In mm/truncate.c (ffffffff81308270)
Location: include/linux/huge_mm.h:204
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_partial_folio
```
```
In mm/shmem.c (ffffffff8131b95b)
Location: include/linux/huge_mm.h:204
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/madvise.c (ffffffff81376ae0)
Location: include/linux/huge_mm.h:204
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/ksm.c (ffffffff813a2625)
Location: include/linux/huge_mm.h:204
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate_device.c (ffffffff813b6f32)
Location: include/linux/huge_mm.h:204
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c07d1)
Location: include/linux/huge_mm.h:204
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff813d9ef4)
Location: include/linux/huge_mm.h:204
Inline: True
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
In mm/shmem.c (ffffffff8138f792)
Location: include/linux/huge_mm.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/madvise.c (ffffffff813f498c)
Location: include/linux/huge_mm.h:186
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/ksm.c (ffffffff814222b5)
Location: include/linux/huge_mm.h:186
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate_device.c (ffffffff81438a7b)
Location: include/linux/huge_mm.h:186
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81442ec4)
Location: include/linux/huge_mm.h:186
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81461a01)
Location: include/linux/huge_mm.h:186
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
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
In mm/shmem.c (ffffffff813bf63c)
Location: include/linux/huge_mm.h:148
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/ksm.c (ffffffff81456f9e)
Location: include/linux/huge_mm.h:148
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate_device.c (ffffffff8146f1ea)
Location: include/linux/huge_mm.h:148
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81478794)
Location: include/linux/huge_mm.h:148
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff8149626f)
Location: include/linux/huge_mm.h:148
Inline: True
Inline callers:
  - mm/memory-failure.c:try_to_split_thp_page
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
In mm/shmem.c (ffffffff813ea674)
Location: include/linux/huge_mm.h:269
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/ksm.c (ffffffff81491a9c)
Location: include/linux/huge_mm.h:269
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate_device.c (ffffffff8149dceb)
Location: include/linux/huge_mm.h:269
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/memory-failure.c (ffffffff814c626b)
Location: include/linux/huge_mm.h:269
Inline: True
Inline callers:
  - mm/memory-failure.c:try_to_split_thp_page
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
In mm/shmem.c (ffff8000102d1c2c)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffff8000102f2160)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffff80001031ee10)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/ksm.c (ffff800010341064)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffff800010359bf8)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffff8000103704fc)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca078)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
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
In mm/gup.c (0)
Location: include/linux/huge_mm.h:328
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/huge_mm.h:328
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/huge_mm.h:328
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
In mm/shmem.c (c000000000391448)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (c0000000003b8130)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (c0000000003f351c)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/ksm.c (c00000000041e9c8)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (c0000000004349b0)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (c00000000044336c)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (c000000000461444)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/gup.c (0)
Location: include/linux/huge_mm.h:328
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/huge_mm.h:328
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/huge_mm.h:328
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
In mm/shmem.c (ffffffff81237f61)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8125261c)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffffffff8127ceb1)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/ksm.c (ffffffff81299d78)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812a6d55)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812b1a51)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812c4786)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/shmem.c (ffffffff8122afa1)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff81245b3a)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffffffff8126ed65)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/ksm.c (ffffffff8128b938)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812987fe)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812a2e21)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812b57c6)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/shmem.c (ffffffff81235d01)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff812503bc)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffffffff8127ac51)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/ksm.c (ffffffff81297b88)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812a4b65)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812af861)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812c2596)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/shmem.c (ffffffff81245fdf)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/gup.c (ffffffff8125fd40)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/madvise.c (ffffffff8128a82c)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/ksm.c (ffffffff812a797e)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812b56c1)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812bfba1)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/memory-failure.c (ffffffff812d3030)
Location: include/linux/huge_mm.h:166
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
</details>
</li>
</ul>

## Differences
