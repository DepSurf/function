# Function: <code>page_remove_rmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811cb020)
Location: mm/rmap.c:1254
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff811cb020-ffffffff811cb120: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e7f40)
Location: mm/rmap.c:1391
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/memory.c:unmap_page_range
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff811e7f40-ffffffff811e81b2: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f92c0)
Location: mm/rmap.c:1390
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/memory.c:unmap_page_range
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff811f92c0-ffffffff811f9532: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81203ed0)
Location: mm/rmap.c:1291
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81203ed0-ffffffff8120416b: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121cc40)
Location: mm/rmap.c:1295
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff8121cc40-ffffffff8121cedb: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123ea60)
Location: mm/rmap.c:1297
Inline: True
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8123ea60-ffffffff8123eda8: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81252ff0)
Location: mm/rmap.c:1299
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81252ff0-ffffffff8125333d: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812652f0)
Location: mm/rmap.c:1300
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
**Symbols:**

```
ffffffff812652f0-ffffffff812655a6: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81273bb0)
Location: mm/rmap.c:1302
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
**Symbols:**

```
ffffffff81273bb0-ffffffff81273eb1: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a4fd0)
Location: mm/rmap.c:1326
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_copy
```
**Symbols:**

```
ffffffff812a4fd0-ffffffff812a5137: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b0510)
Location: mm/rmap.c:1332
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
**Symbols:**

```
ffffffff812b0510-ffffffff812b05ff: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b5b20)
Location: mm/rmap.c:1343
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
**Symbols:**

```
ffffffff812b5b20-ffffffff812b5c02: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f77a0)
Location: mm/rmap.c:1346
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
**Symbols:**

```
ffffffff812f77a0-ffffffff812f7882: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void page_remove_rmap(struct page *page, struct vm_area_struct *vma, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135d400)
Location: mm/rmap.c:1429
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:replace_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
**Symbols:**

```
ffffffff8135d400-ffffffff8135d592: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void page_remove_rmap(struct page *page, struct vm_area_struct *vma, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d7f60)
Location: mm/rmap.c:1381
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/mmu_gather.c:tlb_flush_rmaps
  - mm/mmu_gather.c:tlb_flush_rmaps
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:replace_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
**Symbols:**

```
ffffffff813d7f60-ffffffff813d83d9: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void page_remove_rmap(struct page *page, struct vm_area_struct *vma, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140c930)
Location: mm/rmap.c:1370
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/mmu_gather.c:tlb_flush_rmaps
  - mm/mmu_gather.c:tlb_flush_rmaps
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:replace_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
**Symbols:**

```
ffffffff8140c930-ffffffff8140cbb1: page_remove_rmap (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff800010309810)
Location: mm/rmap.c:1302
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:unmap_page_range
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffff800010309810-ffff800010309bdc: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0526284)
Location: mm/rmap.c:1302
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:unmap_page_range
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:replace_page
```
**Symbols:**

```
c0526284-c0526424: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003d8f00)
Location: mm/rmap.c:1302
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
**Symbols:**

```
c0000000003d8f00-c0000000003d94bc: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe000213a4e)
Location: mm/rmap.c:1302
Inline: True
Direct callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:unmap_page_range
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffe000213a4e-ffffffe000213bb6: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126c200)
Location: mm/rmap.c:1302
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
**Symbols:**

```
ffffffff8126c200-ffffffff8126c501: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125e270)
Location: mm/rmap.c:1302
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8125e270-ffffffff8125e571: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81269fa0)
Location: mm/rmap.c:1302
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
**Symbols:**

```
ffffffff81269fa0-ffffffff8126a2a1: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void page_remove_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81279910)
Location: mm/rmap.c:1302
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
**Symbols:**

```
ffffffff81279910-ffffffff81279c11: page_remove_rmap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool compound</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, compound</code> ➡️ <code>page, vma, compound</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
