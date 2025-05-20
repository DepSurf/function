# Function: <code>arch_leave_lazy_mmu_mode</code>

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
In arch/x86/kernel/paravirt.c (ffffffff81064db3)
Location: arch/x86/include/asm/paravirt.h:673
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
```
```
In mm/memory.c (ffffffff811bda8d)
Location: arch/x86/include/asm/paravirt.h:673
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811c89e4)
Location: arch/x86/include/asm/paravirt.h:673
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c97a0)
Location: arch/x86/include/asm/paravirt.h:673
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
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
In arch/x86/kernel/paravirt.c (ffffffff81064bb2)
Location: arch/x86/include/asm/paravirt.h:646
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff811dc0c2)
Location: arch/x86/include/asm/paravirt.h:646
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811e4cb0)
Location: arch/x86/include/asm/paravirt.h:646
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e5ae7)
Location: arch/x86/include/asm/paravirt.h:646
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff811eedb9)
Location: arch/x86/include/asm/paravirt.h:646
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In arch/x86/kernel/paravirt.c (ffffffff81068082)
Location: arch/x86/include/asm/paravirt.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff811ebbce)
Location: arch/x86/include/asm/paravirt.h:637
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811f4cd9)
Location: arch/x86/include/asm/paravirt.h:637
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5dc4)
Location: arch/x86/include/asm/paravirt.h:637
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff811ff6e8)
Location: arch/x86/include/asm/paravirt.h:637
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In arch/x86/kernel/paravirt.c (ffffffff81067399)
Location: arch/x86/include/asm/paravirt.h:684
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff811f6b0d)
Location: arch/x86/include/asm/paravirt.h:684
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811ffc2a)
Location: arch/x86/include/asm/paravirt.h:684
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81200bc4)
Location: arch/x86/include/asm/paravirt.h:684
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff8120a4dd)
Location: arch/x86/include/asm/paravirt.h:684
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In arch/x86/kernel/paravirt.c (ffffffff8106b5f2)
Location: arch/x86/include/asm/paravirt.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff8120efd8)
Location: arch/x86/include/asm/paravirt.h:648
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812182c1)
Location: arch/x86/include/asm/paravirt.h:648
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81219589)
Location: arch/x86/include/asm/paravirt.h:648
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff8122375d)
Location: arch/x86/include/asm/paravirt.h:648
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff8124b509)
Location: arch/x86/include/asm/paravirt.h:648
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff8106e2c2)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff81230d9b)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
```
```
In mm/mprotect.c (ffffffff81239345)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123aef1)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff81246568)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff8126e22a)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff81074292)
Location: arch/x86/include/asm/paravirt.h:631
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff8124312e)
Location: arch/x86/include/asm/paravirt.h:631
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
```
```
In mm/mprotect.c (ffffffff8124d929)
Location: arch/x86/include/asm/paravirt.h:631
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124f0c1)
Location: arch/x86/include/asm/paravirt.h:631
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff8125a98b)
Location: arch/x86/include/asm/paravirt.h:631
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff8128308e)
Location: arch/x86/include/asm/paravirt.h:631
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff81077de2)
Location: arch/x86/include/asm/paravirt.h:632
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff81254f58)
Location: arch/x86/include/asm/paravirt.h:632
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
```
```
In mm/mprotect.c (ffffffff8125f8e5)
Location: arch/x86/include/asm/paravirt.h:632
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126141a)
Location: arch/x86/include/asm/paravirt.h:632
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff81275966)
Location: arch/x86/include/asm/paravirt.h:632
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In arch/x86/kernel/paravirt.c (ffffffff81078e52)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff812634c8)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
```
```
In mm/mprotect.c (ffffffff8126e0f5)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126fbd4)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff81284936)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812aeae1)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff81080145)
Location: arch/x86/include/asm/paravirt.h:634
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff8128ea1f)
Location: arch/x86/include/asm/paravirt.h:634
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff8129e8da)
Location: arch/x86/include/asm/paravirt.h:634
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812a013a)
Location: arch/x86/include/asm/paravirt.h:634
Inline: True
```
```
In mm/madvise.c (ffffffff812b6af2)
Location: arch/x86/include/asm/paravirt.h:634
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812e427e)
Location: arch/x86/include/asm/paravirt.h:634
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff8107fd65)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff81299601)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812a9c90)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab593)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
```
```
In mm/madvise.c (ffffffff812c2d42)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812efdc1)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff81080e25)
Location: arch/x86/include/asm/paravirt.h:563
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff8129e7f9)
Location: arch/x86/include/asm/paravirt.h:563
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812af11b)
Location: arch/x86/include/asm/paravirt.h:563
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b0996)
Location: arch/x86/include/asm/paravirt.h:563
Inline: True
```
```
In mm/madvise.c (ffffffff812c9bbb)
Location: arch/x86/include/asm/paravirt.h:563
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812f5710)
Location: arch/x86/include/asm/paravirt.h:563
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff8108fd95)
Location: arch/x86/include/asm/paravirt.h:563
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff812dfa39)
Location: arch/x86/include/asm/paravirt.h:563
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812f092a)
Location: arch/x86/include/asm/paravirt.h:563
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f2326)
Location: arch/x86/include/asm/paravirt.h:563
Inline: True
```
```
In mm/madvise.c (ffffffff8130ebdb)
Location: arch/x86/include/asm/paravirt.h:563
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff8133fd0c)
Location: arch/x86/include/asm/paravirt.h:563
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff810a0c3d)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff8133fff2)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff81353eee)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813560c3)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
```
```
In mm/madvise.c (ffffffff81376a63)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate_device.c (ffffffff813b70fc)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff810b89ad)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/vmscan.c (ffffffff81387472)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
```
```
In mm/memory.c (ffffffff813b7f52)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff813ce2b9)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d0705)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
```
```
In mm/madvise.c (ffffffff813f4343)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate_device.c (ffffffff81438cd7)
Location: arch/x86/include/asm/paravirt.h:569
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff810bbb7d)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/vmscan.c (ffffffff813b799d)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
```
```
In mm/memory.c (ffffffff813ecc7e)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff81402b5c)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81404be6)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
```
```
In mm/madvise.c (ffffffff81427b4f)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate_device.c (ffffffff8146f586)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void arch_leave_lazy_mmu_mode();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8103914f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103d039)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_context_switch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f10f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_lazy_mmu
```
```
In arch/x86/kernel/ldt.c (ffffffff8105b134)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff8106170f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81070bcf)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109940f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c2d5f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In kernel/events/uprobes.c (ffffffff813a987f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In mm/vmscan.c (ffffffff813e07d8)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
```
```
In mm/gup.c (ffffffff8140dfaf)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In mm/memory.c (ffffffff814181ce)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:copy_pte_range
Direct callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff8142f26c)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81431189)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In mm/rmap.c (ffffffff8143793f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In mm/vmalloc.c (ffffffff8143e2c2)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff8146135f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81468d7f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In mm/hugetlb.c (ffffffff81474aef)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480b0a)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff8148904f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In mm/ksm.c (ffffffff8148d69f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In mm/migrate.c (ffffffff8149771f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In mm/migrate_device.c (ffffffff8149e088)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a17f4)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814cfe4f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff815a0659)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_scan_pmd_entry
  - fs/proc/task_mmu.c:pagemap_scan_pmd_entry
  - fs/proc/task_mmu.c:pagemap_scan_pmd_entry
```
```
In drivers/xen/xlate_mmu.c (ffffffff81ad014f)
Location: arch/x86/include/asm/paravirt.h:562
Inline: True
```
**Symbols:**

```
ffffffff81414180-ffffffff814141a6: arch_leave_lazy_mmu_mode (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/hash_tlb.c (c000000000091f3c)
Location: arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:39
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_tlb.c:flush_tlb_pmd_range
  - arch/powerpc/mm/book3s64/hash_tlb.c:flush_tlb_pmd_range
  - arch/powerpc/mm/book3s64/hash_tlb.c:__flush_hash_table_range
  - arch/powerpc/mm/book3s64/hash_tlb.c:__flush_hash_table_range
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009f9f0)
Location: arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:39
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range
```
```
In mm/memory.c (c0000000003c5908)
Location: arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:39
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (c0000000003d2258)
Location: arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:39
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d37bc)
Location: arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:39
Inline: True
```
```
In mm/madvise.c (c0000000003f3170)
Location: arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:39
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (c000000000434680)
Location: arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:39
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/kernel/paravirt.c (ffffffff81077e52)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff8125bb18)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
```
```
In mm/mprotect.c (ffffffff81266745)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81268224)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff8127cf86)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812a70c1)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077e02)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff812598b8)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
```
```
In mm/mprotect.c (ffffffff812644e5)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81265fc4)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff8127ad26)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812a4ed1)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
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
In arch/x86/kernel/paravirt.c (ffffffff81079ee0)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_start_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff812692b6)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
```
```
In mm/mprotect.c (ffffffff81273ea5)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81275959)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff8128a905)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812b5a2d)
Location: arch/x86/include/asm/paravirt.h:620
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
