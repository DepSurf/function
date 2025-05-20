# Function: <code>lruvec_stat_mod_folio</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812ff096)
Location: include/linux/vmstat.h:642
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
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
In mm/page-writeback.c (ffffffff8136971e)
Location: include/linux/vmstat.h:636
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
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
In mm/page-writeback.c (ffffffff8139b8bb)
Location: include/linux/vmstat.h:642
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void lruvec_stat_mod_folio(struct folio *folio, enum node_stat_item idx, int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d2840)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In kernel/fork.c (ffffffff810f9a80)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - kernel/fork.c:account_kernel_stack
```
```
In mm/page-writeback.c (ffffffff813c2ce0)
Location: include/linux/vmstat.h:562
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_account_cleaned
```
```
In mm/memory.c (ffffffff814146d0)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/pgtable-generic.c (ffffffff814357b0)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - mm/pgtable-generic.c:pte_free_now
```
```
In mm/slub.c (ffffffff81454c20)
Location: include/linux/vmstat.h:562
Inline: True
Direct callers:
  - mm/slub.c:free_large_kmalloc
  - mm/slub.c:__kmalloc_large_node
```
```
In mm/huge_memory.c (ffffffff814a0660)
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
In fs/dax.c (0)
Location: include/linux/vmstat.h:562
Inline: False
```
**Symbols:**

```
ffffffff810d2840-ffffffff810d288f: lruvec_stat_mod_folio.constprop.0 (STB_LOCAL)
ffffffff810f9a80-ffffffff810f9acf: lruvec_stat_mod_folio.constprop.0 (STB_LOCAL)
ffffffff813c2ce0-ffffffff813c2d33: lruvec_stat_mod_folio (STB_LOCAL)
ffffffff814146d0-ffffffff8141471f: lruvec_stat_mod_folio.constprop.0 (STB_LOCAL)
ffffffff814357b0-ffffffff814357ff: lruvec_stat_mod_folio.constprop.0 (STB_LOCAL)
ffffffff81454c20-ffffffff81454c6f: lruvec_stat_mod_folio.constprop.0 (STB_LOCAL)
ffffffff814a0660-ffffffff814a06af: lruvec_stat_mod_folio.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
