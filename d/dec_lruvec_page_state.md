# Function: <code>dec_lruvec_page_state</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c7eda)
Location: include/linux/memcontrol.h:1027
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dcd1a)
Location: include/linux/memcontrol.h:1039
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fddbf)
Location: include/linux/memcontrol.h:1132
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81210a4f)
Location: include/linux/memcontrol.h:1216
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
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
In mm/page-writeback.c (ffffffff8122019f)
Location: include/linux/memcontrol.h:1227
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff8122dc4f)
Location: include/linux/memcontrol.h:1279
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff81259700)
Location: include/linux/memcontrol.h:1239
Inline: True
Inline callers:
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
Location: include/linux/vmstat.h:551
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/page-writeback.c (ffffffff81263cea)
Location: include/linux/vmstat.h:551
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
```
```
In mm/memory.c (ffffffff8129d071)
Location: include/linux/vmstat.h:551
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812f71f1)
Location: include/linux/vmstat.h:551
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
Location: include/linux/vmstat.h:551
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/vmstat.h:551
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
In arch/x86/mm/pgtable.c (ffffffff8108b391)
Location: include/linux/vmstat.h:539
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/page-writeback.c (ffffffff8126b434)
Location: include/linux/vmstat.h:539
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
```
In mm/memory.c (ffffffff812a2757)
Location: include/linux/vmstat.h:539
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff812fd67c)
Location: include/linux/vmstat.h:539
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813036c3)
Location: include/linux/vmstat.h:539
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/vmstat.h:539
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
In arch/x86/mm/pgtable.c (ffffffff8109a931)
Location: include/linux/vmstat.h:552
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/page-writeback.c (ffffffff812a80f0)
Location: include/linux/vmstat.h:552
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
```
In mm/memory.c (ffffffff812e3ac7)
Location: include/linux/vmstat.h:552
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff813472b1)
Location: include/linux/vmstat.h:552
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8134d42d)
Location: include/linux/vmstat.h:552
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/dax.c (0)
Location: include/linux/vmstat.h:552
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
In arch/x86/mm/pgtable.c (ffffffff810adc04)
Location: include/linux/vmstat.h:636
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff81344e66)
Location: include/linux/vmstat.h:636
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff813bd594)
Location: include/linux/vmstat.h:636
Inline: True
Inline callers:
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
In mm/khugepaged.c (ffffffff813c3bba)
Location: include/linux/vmstat.h:636
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In fs/dax.c (0)
Location: include/linux/vmstat.h:636
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
In arch/x86/mm/pgtable.c (ffffffff810c7e1b)
Location: include/linux/vmstat.h:630
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff813bd096)
Location: include/linux/vmstat.h:630
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff8143fd2c)
Location: include/linux/vmstat.h:630
Inline: True
Inline callers:
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
In mm/khugepaged.c (ffffffff81447399)
Location: include/linux/vmstat.h:630
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In fs/dax.c (0)
Location: include/linux/vmstat.h:630
Inline: True
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
In arch/x86/mm/pgtable.c (ffffffff810cb55b)
Location: include/linux/vmstat.h:636
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/memory.c (ffffffff813f1ddc)
Location: include/linux/vmstat.h:636
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:do_fault
  - mm/memory.c:__pte_alloc
```
```
In mm/huge_memory.c (ffffffff81475554)
Location: include/linux/vmstat.h:636
Inline: True
Inline callers:
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
In mm/khugepaged.c (ffffffff8147ca73)
Location: include/linux/vmstat.h:636
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
```
```
In fs/dax.c (0)
Location: include/linux/vmstat.h:636
Inline: True
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102bcb10)
Location: include/linux/memcontrol.h:1279
Inline: True
Inline callers:
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
In mm/page-writeback.c (c04e9054)
Location: include/linux/memcontrol.h:1279
Inline: True
Inline callers:
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
In mm/page-writeback.c (c000000000375590)
Location: include/linux/memcontrol.h:1279
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffe0001dfa4e)
Location: include/linux/memcontrol.h:1279
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff8122629f)
Location: include/linux/memcontrol.h:1279
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff8121942f)
Location: include/linux/memcontrol.h:1279
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff8122403f)
Location: include/linux/memcontrol.h:1279
Inline: True
Inline callers:
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
In mm/page-writeback.c (ffffffff812332ef)
Location: include/linux/memcontrol.h:1279
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
```
</details>
</li>
</ul>

## Differences
