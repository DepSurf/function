# Function: <code>mmu_notifier_invalidate_range</code>

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
In kernel/events/uprobes.c (ffffffff81187575)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811bbce2)
Location: include/linux/mmu_notifier.h:292
Inline: True
```
```
In mm/hugetlb.c (ffffffff811ddd4c)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff811e553d)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff811f3434)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f6d15)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In kernel/events/uprobes.c (ffffffff81199e5f)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811d7309)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff811fc5aa)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81203fec)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff8121321e)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81215f08)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In kernel/events/uprobes.c (ffffffff811a95bc)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811e6fbe)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff8120d096)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8121621f)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81225586)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81228524)
Location: include/linux/mmu_notifier.h:292
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In kernel/events/uprobes.c (ffffffff811b0abd)
Location: include/linux/mmu_notifier.h:272
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811f2188)
Location: include/linux/mmu_notifier.h:272
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff8120444c)
Location: include/linux/mmu_notifier.h:272
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/hugetlb.c (ffffffff81218e78)
Location: include/linux/mmu_notifier.h:272
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81221753)
Location: include/linux/mmu_notifier.h:272
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81230c56)
Location: include/linux/mmu_notifier.h:272
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81231c62)
Location: include/linux/mmu_notifier.h:272
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In fs/dax.c (ffffffff812aab20)
Location: include/linux/mmu_notifier.h:272
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
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
In kernel/events/uprobes.c (ffffffff811c4623)
Location: include/linux/mmu_notifier.h:282
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff81209022)
Location: include/linux/mmu_notifier.h:282
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff8121d1e1)
Location: include/linux/mmu_notifier.h:282
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812332e5)
Location: include/linux/mmu_notifier.h:282
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff8124e9ba)
Location: include/linux/mmu_notifier.h:282
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812528a6)
Location: include/linux/mmu_notifier.h:282
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In kernel/events/uprobes.c (ffffffff811e4b41)
Location: include/linux/mmu_notifier.h:301
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff81229f5a)
Location: include/linux/mmu_notifier.h:301
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff8123f0cf)
Location: include/linux/mmu_notifier.h:301
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812564f9)
Location: include/linux/mmu_notifier.h:301
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812727e4)
Location: include/linux/mmu_notifier.h:301
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81276ca9)
Location: include/linux/mmu_notifier.h:301
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In kernel/events/uprobes.c (ffffffff811f51fa)
Location: include/linux/mmu_notifier.h:301
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8123d536)
Location: include/linux/mmu_notifier.h:301
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/mmu_gather.c (ffffffff8124cf6e)
Location: include/linux/mmu_notifier.h:301
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mmu_gather.c:tlb_flush_mmu
```
```
In mm/rmap.c (ffffffff812536ef)
Location: include/linux/mmu_notifier.h:301
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8126aa25)
Location: include/linux/mmu_notifier.h:301
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff81283aa1)
Location: include/linux/mmu_notifier.h:301
Inline: True
```
```
In mm/huge_memory.c (ffffffff81288536)
Location: include/linux/mmu_notifier.h:301
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In kernel/events/uprobes.c (ffffffff8120cf01)
Location: include/linux/mmu_notifier.h:343
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8124f1e5)
Location: include/linux/mmu_notifier.h:343
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/mmu_gather.c (ffffffff8125f253)
Location: include/linux/mmu_notifier.h:343
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
```
```
In mm/rmap.c (ffffffff81265952)
Location: include/linux/mmu_notifier.h:343
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81285924)
Location: include/linux/mmu_notifier.h:343
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/huge_memory.c (ffffffff812a3189)
Location: include/linux/mmu_notifier.h:343
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In kernel/events/uprobes.c (ffffffff8121a1ed)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8125d7a9)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/mmu_gather.c (ffffffff8126da63)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
```
```
In mm/rmap.c (ffffffff81274267)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812954f4)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812af51b)
Location: include/linux/mmu_notifier.h:387
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b4689)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In kernel/events/uprobes.c (ffffffff81246b66)
Location: include/linux/mmu_notifier.h:483
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8128d0b5)
Location: include/linux/mmu_notifier.h:483
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff8129df2d)
Location: include/linux/mmu_notifier.h:483
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/rmap.c (ffffffff812a54e8)
Location: include/linux/mmu_notifier.h:483
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812c8c00)
Location: include/linux/mmu_notifier.h:483
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812e53f7)
Location: include/linux/mmu_notifier.h:483
Inline: True
```
```
In mm/huge_memory.c (ffffffff812e9c15)
Location: include/linux/mmu_notifier.h:483
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In kernel/events/uprobes.c (ffffffff812511c9)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff81298079)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812a92ad)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/rmap.c (ffffffff812b0976)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812d478e)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812f07ba)
Location: include/linux/mmu_notifier.h:489
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f4df5)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In kernel/events/uprobes.c (ffffffff812552c9)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8129d6f8)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812ae71d)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/rmap.c (ffffffff812b5fa8)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812db541)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812f6b87)
Location: include/linux/mmu_notifier.h:489
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fb335)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In kernel/events/uprobes.c (ffffffff81290d0b)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff812ddddc)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812efebd)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/rmap.c (ffffffff812f89a6)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81322767)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate.c (ffffffff813411e3)
Location: include/linux/mmu_notifier.h:495
Inline: True
```
```
In mm/huge_memory.c (ffffffff81345167)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
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
In kernel/events/uprobes.c (ffffffff812e600e)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8133de3d)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff813533ab)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff81354d2b)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8135ef99)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81375c98)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff8138fd35)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate_device.c (ffffffff813b7ff1)
Location: include/linux/mmu_notifier.h:495
Inline: True
```
```
In mm/huge_memory.c (ffffffff813baf9f)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
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
In kernel/events/uprobes.c (ffffffff8134fc48)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813b6f38)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff813cd668)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff813cf223)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff813d9e3f)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f2f11)
Location: include/linux/mmu_notifier.h:495
Inline: True
```
```
In mm/hugetlb.c (ffffffff814106b1)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate_device.c (ffffffff81439cf8)
Location: include/linux/mmu_notifier.h:495
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143d59c)
Location: include/linux/mmu_notifier.h:495
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
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
In kernel/events/uprobes.c (ffffffff81380e06)
Location: include/linux/mmu_notifier.h:494
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813eb876)
Location: include/linux/mmu_notifier.h:494
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff81401fc8)
Location: include/linux/mmu_notifier.h:494
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff81403bc7)
Location: include/linux/mmu_notifier.h:494
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8140e565)
Location: include/linux/mmu_notifier.h:494
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81426951)
Location: include/linux/mmu_notifier.h:494
Inline: True
```
```
In mm/hugetlb.c (ffffffff81443a6c)
Location: include/linux/mmu_notifier.h:494
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/migrate_device.c (ffffffff8146e981)
Location: include/linux/mmu_notifier.h:494
Inline: True
```
```
In mm/huge_memory.c (ffffffff81472c0e)
Location: include/linux/mmu_notifier.h:494
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
```
</details>
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
In kernel/events/uprobes.c (ffff8000102a55f4)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffff8000102f4d88)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (ffff800010304880)
Location: include/linux/mmu_notifier.h:387
Inline: True
```
```
In mm/rmap.c (ffff800010309e6c)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffff80001031d9a4)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/madvise.c:tlb_flush_mmu_tlbonly
```
```
In mm/hugetlb.c (ffff8000103341c4)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/huge_memory.c (ffff800010355c78)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In kernel/events/uprobes.c (c04d4a34)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (c0516f1c)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (c05230a4)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/rmap.c (c05266b4)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (c0537420)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/madvise.c:tlb_flush_mmu_tlbonly
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
In kernel/events/uprobes.c (c000000000358338)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (c0000000003bba78)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (c0000000003d1a40)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/rmap.c (c0000000003d9ad8)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (c00000000040cf5c)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (c000000000432b44)
Location: include/linux/mmu_notifier.h:387
Inline: True
```
```
In mm/huge_memory.c (c00000000043bfac)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (ffffffe0002061e6)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (ffffffe000210fe2)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/rmap.c (ffffffe000213df6)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffe000220f50)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffe00023028c)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
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
In kernel/events/uprobes.c (ffffffff8121283d)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff81255df9)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/mmu_gather.c (ffffffff812660b3)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
```
```
In mm/rmap.c (ffffffff8126c8b7)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8128dad4)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812a7afb)
Location: include/linux/mmu_notifier.h:387
Inline: True
```
```
In mm/huge_memory.c (ffffffff812acc69)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In kernel/events/uprobes.c (ffffffff812055bf)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8124848c)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812584d3)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
```
```
In mm/rmap.c (ffffffff8125e909)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8127f860)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812994b5)
Location: include/linux/mmu_notifier.h:387
Inline: True
```
```
In mm/huge_memory.c (ffffffff8129dd46)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In kernel/events/uprobes.c (ffffffff812105dd)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff81253b99)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/mmu_gather.c (ffffffff81263e53)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
```
```
In mm/rmap.c (ffffffff8126a657)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8128b8e4)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812a590b)
Location: include/linux/mmu_notifier.h:387
Inline: True
```
```
In mm/huge_memory.c (ffffffff812aaa79)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In kernel/events/uprobes.c (ffffffff8121f520)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff812635af)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/mmu_gather.c (ffffffff81273813)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
```
```
In mm/rmap.c (ffffffff8127a035)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8129b6e6)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812b5039)
Location: include/linux/mmu_notifier.h:387
Inline: True
```
```
In mm/huge_memory.c (ffffffff812badc9)
Location: include/linux/mmu_notifier.h:387
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
</details>
</li>
</ul>

## Differences
