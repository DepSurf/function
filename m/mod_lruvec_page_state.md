# Function: <code>mod_lruvec_page_state</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c764e)
Location: include/linux/memcontrol.h:610
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
```
In mm/workingset.c (ffffffff811ee521)
Location: include/linux/memcontrol.h:610
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/slub.c (ffffffff8122666c)
Location: include/linux/memcontrol.h:610
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
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
In mm/page-writeback.c (ffffffff811dc47d)
Location: include/linux/memcontrol.h:613
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
```
In mm/workingset.c (ffffffff81204871)
Location: include/linux/memcontrol.h:613
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/slub.c (ffffffff812416bc)
Location: include/linux/memcontrol.h:613
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
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
In mm/page-writeback.c (ffffffff811fe72b)
Location: include/linux/memcontrol.h:665
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
```
In mm/workingset.c (ffffffff81225638)
Location: include/linux/memcontrol.h:665
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/slub.c (ffffffff8126527a)
Location: include/linux/memcontrol.h:665
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
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
In mm/page-writeback.c (ffffffff8120f01e)
Location: include/linux/memcontrol.h:705
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
```
In mm/slub.c (ffffffff81279fac)
Location: include/linux/memcontrol.h:705
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121eb9f)
Location: include/linux/memcontrol.h:699
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122c63f)
Location: include/linux/memcontrol.h:736
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81259f4f)
Location: include/linux/memcontrol.h:714
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
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
In arch/x86/mm/pgtable.c (ffffffff8108a73f)
Location: include/linux/vmstat.h:471
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In kernel/fork.c (ffffffff8109fc12)
Location: include/linux/vmstat.h:471
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In mm/page-writeback.c (ffffffff81265700)
Location: include/linux/vmstat.h:471
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
```
In mm/slab_common.c (ffffffff81288cae)
Location: include/linux/vmstat.h:471
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff8129cf15)
Location: include/linux/vmstat.h:471
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/slub.c (ffffffff812e6beb)
Location: include/linux/vmstat.h:471
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
```
```
In mm/huge_memory.c (ffffffff812f71f1)
Location: include/linux/vmstat.h:471
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fc95b)
Location: include/linux/vmstat.h:471
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/vmstat.h:471
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mod_lruvec_page_state(struct page *page, enum node_stat_item idx, int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a710)
Location: include/linux/vmstat.h:477
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In kernel/fork.c (ffffffff810a1462)
Location: include/linux/vmstat.h:477
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In mm/page-writeback.c (ffffffff8126a1fb)
Location: include/linux/vmstat.h:477
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
Direct callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
```
```
In mm/slab_common.c (ffffffff8128e35e)
Location: include/linux/vmstat.h:477
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff812a25f5)
Location: include/linux/vmstat.h:477
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/slub.c (ffffffff812ee392)
Location: include/linux/vmstat.h:477
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
```
```
In mm/huge_memory.c (ffffffff812fd67c)
Location: include/linux/vmstat.h:477
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813036c3)
Location: include/linux/vmstat.h:477
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/vmstat.h:477
Inline: False
```
**Symbols:**

```
ffffffff8108a710-ffffffff8108a74a: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff81269780-ffffffff812697b3: mod_lruvec_page_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mod_lruvec_page_state(struct page *page, enum node_stat_item idx, int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81099c90)
Location: include/linux/vmstat.h:490
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In kernel/fork.c (ffffffff810b287a)
Location: include/linux/vmstat.h:490
Inline: True
```
```
In mm/page-writeback.c (ffffffff812a6e8e)
Location: include/linux/vmstat.h:490
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
Direct callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
```
```
In mm/slab_common.c (ffffffff812ce28a)
Location: include/linux/vmstat.h:490
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff812e3965)
Location: include/linux/vmstat.h:490
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/slub.c (ffffffff813365dc)
Location: include/linux/vmstat.h:490
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:build_detached_freelist
```
```
In mm/huge_memory.c (ffffffff813472b1)
Location: include/linux/vmstat.h:490
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8134d42d)
Location: include/linux/vmstat.h:490
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/vmstat.h:490
Inline: False
```
**Symbols:**

```
ffffffff81099c90-ffffffff81099cca: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff812a63e0-ffffffff812a6413: mod_lruvec_page_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mod_lruvec_page_state(struct page *page, enum node_stat_item idx, int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810acca0)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In kernel/fork.c (ffffffff810c7ec0)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:exit_task_stack_account
```
```
In mm/page-writeback.c (ffffffff812fc590)
Location: include/linux/vmstat.h:562
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
```
```
In mm/slab_common.c (ffffffff8132b9a0)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffff8133cec0)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/slub.c (ffffffff813a47f0)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:build_detached_freelist
```
```
In mm/huge_memory.c (ffffffff813b9360)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c3750)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In fs/dax.c (0)
Location: include/linux/vmstat.h:562
Inline: False
```
**Symbols:**

```
ffffffff810acca0-ffffffff810accdd: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff810c7ec0-ffffffff810c7efd: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff812fc590-ffffffff812fc5c6: mod_lruvec_page_state (STB_LOCAL)
ffffffff8132b9a0-ffffffff8132b9dd: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff8133cec0-ffffffff8133cefd: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff813a47f0-ffffffff813a482d: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff813b9360-ffffffff813b93a0: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff813c3750-ffffffff813c3790: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mod_lruvec_page_state(struct page *page, enum node_stat_item idx, int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c6d80)
Location: include/linux/vmstat.h:556
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In kernel/fork.c (ffffffff810e5080)
Location: include/linux/vmstat.h:556
Inline: True
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:exit_task_stack_account
```
```
In mm/page-writeback.c (ffffffff81366870)
Location: include/linux/vmstat.h:556
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
```
```
In mm/slab_common.c (ffffffff813a0cf0)
Location: include/linux/vmstat.h:556
Inline: True
Direct callers:
  - mm/slab_common.c:__kmalloc_large_node
  - mm/slab_common.c:free_large_kmalloc
```
```
In mm/memory.c (ffffffff813b4af0)
Location: include/linux/vmstat.h:556
Inline: True
Direct callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff8143b630)
Location: include/linux/vmstat.h:556
Inline: True
Direct callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81446150)
Location: include/linux/vmstat.h:556
Inline: True
Direct callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In fs/dax.c (0)
Location: include/linux/vmstat.h:556
Inline: False
```
**Symbols:**

```
ffffffff810c6d80-ffffffff810c6dcf: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff810e5080-ffffffff810e50cf: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff81366870-ffffffff813668c3: mod_lruvec_page_state (STB_LOCAL)
ffffffff813a0cf0-ffffffff813a0d3f: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff813b4af0-ffffffff813b4b3f: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff8143b630-ffffffff8143b67b: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff81446150-ffffffff8144619b: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mod_lruvec_page_state(struct page *page, enum node_stat_item idx, int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ca4d0)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In kernel/fork.c (ffffffff810f0720)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:exit_task_stack_account
```
```
In mm/page-writeback.c (ffffffff81398ee0)
Location: include/linux/vmstat.h:562
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
```
```
In mm/slab_common.c (ffffffff813d3f70)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - mm/slab_common.c:__kmalloc_large_node
  - mm/slab_common.c:free_large_kmalloc
```
```
In mm/memory.c (ffffffff813e9750)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81470fa0)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147b830)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In fs/dax.c (0)
Location: include/linux/vmstat.h:562
Inline: False
```
**Symbols:**

```
ffffffff810ca4d0-ffffffff810ca51f: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff810f0720-ffffffff810f076f: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff81398ee0-ffffffff81398f33: mod_lruvec_page_state (STB_LOCAL)
ffffffff813d3f70-ffffffff813d3fbf: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff813e9750-ffffffff813e979f: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff81470fa0-ffffffff81470feb: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
ffffffff8147b830-ffffffff8147b87b: mod_lruvec_page_state.constprop.0 (STB_LOCAL)
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
In kernel/fork.c (ffffffff810f9b07)
Location: include/linux/vmstat.h:572
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102bbf54)
Location: include/linux/memcontrol.h:736
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
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
In mm/page-writeback.c (c04e6f90)
Location: include/linux/memcontrol.h:736
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c00000000037385c)
Location: include/linux/memcontrol.h:736
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001de1b2)
Location: include/linux/memcontrol.h:736
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81224c8f)
Location: include/linux/memcontrol.h:736
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81217e3f)
Location: include/linux/memcontrol.h:736
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81222a2f)
Location: include/linux/memcontrol.h:736
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81231c0f)
Location: include/linux/memcontrol.h:736
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
