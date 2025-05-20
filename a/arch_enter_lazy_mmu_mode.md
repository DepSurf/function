# Function: <code>arch_enter_lazy_mmu_mode</code>

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
In arch/x86/kernel/paravirt.c (ffffffff81064dba)
Location: arch/x86/include/asm/paravirt.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
```
```
In mm/memory.c (ffffffff811bd8a8)
Location: arch/x86/include/asm/paravirt.h:668
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811c8816)
Location: arch/x86/include/asm/paravirt.h:668
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c96a4)
Location: arch/x86/include/asm/paravirt.h:668
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
In arch/x86/kernel/paravirt.c (ffffffff81064bfc)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff811dc04f)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811e4ac3)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e5a5f)
Location: arch/x86/include/asm/paravirt.h:641
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff811eeb98)
Location: arch/x86/include/asm/paravirt.h:641
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
In arch/x86/kernel/paravirt.c (ffffffff810680c7)
Location: arch/x86/include/asm/paravirt.h:632
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff811ebb61)
Location: arch/x86/include/asm/paravirt.h:632
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811f4ade)
Location: arch/x86/include/asm/paravirt.h:632
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5c98)
Location: arch/x86/include/asm/paravirt.h:632
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff811ff4d7)
Location: arch/x86/include/asm/paravirt.h:632
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
In arch/x86/kernel/paravirt.c (ffffffff810673e7)
Location: arch/x86/include/asm/paravirt.h:679
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff811f6aa2)
Location: arch/x86/include/asm/paravirt.h:679
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811ff99d)
Location: arch/x86/include/asm/paravirt.h:679
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81200a86)
Location: arch/x86/include/asm/paravirt.h:679
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff8120a18b)
Location: arch/x86/include/asm/paravirt.h:679
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
In arch/x86/kernel/paravirt.c (ffffffff8106b639)
Location: arch/x86/include/asm/paravirt.h:643
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff8120ef62)
Location: arch/x86/include/asm/paravirt.h:643
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812180c5)
Location: arch/x86/include/asm/paravirt.h:643
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812194c4)
Location: arch/x86/include/asm/paravirt.h:643
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff812233f4)
Location: arch/x86/include/asm/paravirt.h:643
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff8124b3e3)
Location: arch/x86/include/asm/paravirt.h:643
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
In arch/x86/kernel/paravirt.c (ffffffff8106e30a)
Location: arch/x86/include/asm/paravirt.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff81230d11)
Location: arch/x86/include/asm/paravirt.h:648
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
```
```
In mm/mprotect.c (ffffffff8123917e)
Location: arch/x86/include/asm/paravirt.h:648
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123ad60)
Location: arch/x86/include/asm/paravirt.h:648
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff81246272)
Location: arch/x86/include/asm/paravirt.h:648
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff8126df92)
Location: arch/x86/include/asm/paravirt.h:648
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
In arch/x86/kernel/paravirt.c (ffffffff810742da)
Location: arch/x86/include/asm/paravirt.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff812430a4)
Location: arch/x86/include/asm/paravirt.h:626
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
```
```
In mm/mprotect.c (ffffffff8124d729)
Location: arch/x86/include/asm/paravirt.h:626
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124ef62)
Location: arch/x86/include/asm/paravirt.h:626
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff8125a692)
Location: arch/x86/include/asm/paravirt.h:626
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/migrate.c (ffffffff81282e02)
Location: arch/x86/include/asm/paravirt.h:626
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
In arch/x86/kernel/paravirt.c (ffffffff81077e2a)
Location: arch/x86/include/asm/paravirt.h:627
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff81254f25)
Location: arch/x86/include/asm/paravirt.h:627
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
```
```
In mm/mprotect.c (ffffffff8125f716)
Location: arch/x86/include/asm/paravirt.h:627
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812612c1)
Location: arch/x86/include/asm/paravirt.h:627
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff8127577a)
Location: arch/x86/include/asm/paravirt.h:627
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
In arch/x86/kernel/paravirt.c (ffffffff81078e9a)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff81263495)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
```
```
In mm/mprotect.c (ffffffff8126df26)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126fa5a)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff8128474a)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812ae89c)
Location: arch/x86/include/asm/paravirt.h:615
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
In arch/x86/kernel/paravirt.c (ffffffff81080185)
Location: arch/x86/include/asm/paravirt.h:629
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff8128e9cf)
Location: arch/x86/include/asm/paravirt.h:629
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff8129e5f4)
Location: arch/x86/include/asm/paravirt.h:629
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812a00c2)
Location: arch/x86/include/asm/paravirt.h:629
Inline: True
```
```
In mm/madvise.c (ffffffff812b68dc)
Location: arch/x86/include/asm/paravirt.h:629
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812e3ef8)
Location: arch/x86/include/asm/paravirt.h:629
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
In arch/x86/kernel/paravirt.c (ffffffff8107fda5)
Location: arch/x86/include/asm/paravirt.h:527
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff812995aa)
Location: arch/x86/include/asm/paravirt.h:527
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812a99b4)
Location: arch/x86/include/asm/paravirt.h:527
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab525)
Location: arch/x86/include/asm/paravirt.h:527
Inline: True
```
```
In mm/madvise.c (ffffffff812c2b2c)
Location: arch/x86/include/asm/paravirt.h:527
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812efc58)
Location: arch/x86/include/asm/paravirt.h:527
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
In arch/x86/kernel/paravirt.c (ffffffff81080e65)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff8129e7a2)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812aee3f)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b0928)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
```
```
In mm/madvise.c (ffffffff812c99a8)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812f55d8)
Location: arch/x86/include/asm/paravirt.h:558
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
In arch/x86/kernel/paravirt.c (ffffffff8108fdd5)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff812df9e2)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812f062f)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f22b8)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
```
```
In mm/madvise.c (ffffffff8130e9c8)
Location: arch/x86/include/asm/paravirt.h:558
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff8133fbda)
Location: arch/x86/include/asm/paravirt.h:558
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
In arch/x86/kernel/paravirt.c (ffffffff810a0cb2)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff8133ff9a)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff81353b6f)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81356054)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
```
```
In mm/madvise.c (ffffffff81376855)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate_device.c (ffffffff813b7058)
Location: arch/x86/include/asm/paravirt.h:564
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
In arch/x86/kernel/paravirt.c (ffffffff810b8a35)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/vmscan.c (ffffffff8138734a)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
```
```
In mm/memory.c (ffffffff813b7efa)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff813ce009)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d0696)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
```
```
In mm/madvise.c (ffffffff813f41c4)
Location: arch/x86/include/asm/paravirt.h:564
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate_device.c (ffffffff81438bab)
Location: arch/x86/include/asm/paravirt.h:564
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
In arch/x86/kernel/paravirt.c (ffffffff810bbc05)
Location: arch/x86/include/asm/paravirt.h:559
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/vmscan.c (ffffffff813b785c)
Location: arch/x86/include/asm/paravirt.h:559
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
```
```
In mm/memory.c (ffffffff813ecc1d)
Location: arch/x86/include/asm/paravirt.h:559
Inline: True
Inline callers:
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff814028ab)
Location: arch/x86/include/asm/paravirt.h:559
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81404b7b)
Location: arch/x86/include/asm/paravirt.h:559
Inline: True
```
```
In mm/madvise.c (ffffffff81427c36)
Location: arch/x86/include/asm/paravirt.h:559
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate_device.c (ffffffff8146f441)
Location: arch/x86/include/asm/paravirt.h:559
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
void arch_enter_lazy_mmu_mode();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81039130)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103d823)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_end_context_switch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f115)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_lazy_mmu
```
```
In arch/x86/kernel/ldt.c (ffffffff8105b122)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff810616f0)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81070bb0)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810993f0)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c2d4d)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In kernel/events/uprobes.c (ffffffff813a9860)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In mm/vmscan.c (ffffffff813e0686)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
```
```
In mm/gup.c (ffffffff8140df90)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In mm/memory.c (ffffffff8141816d)
Location: arch/x86/include/asm/paravirt.h:557
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
In mm/mprotect.c (ffffffff8142f25a)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8143114e)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In mm/rmap.c (ffffffff81437920)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In mm/vmalloc.c (ffffffff8143e2b0)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff8146144e)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81468d60)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In mm/hugetlb.c (ffffffff81474ad0)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480af8)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff81489030)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In mm/ksm.c (ffffffff8148d680)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In mm/migrate.c (ffffffff81497700)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In mm/migrate_device.c (ffffffff8149df3f)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a17e2)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814cfe30)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff815a0635)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_scan_pmd_entry
```
```
In drivers/xen/xlate_mmu.c (ffffffff81ad0130)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
**Symbols:**

```
ffffffff81414140-ffffffff81414166: arch_enter_lazy_mmu_mode (STB_LOCAL)
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
In arch/powerpc/mm/book3s64/hash_tlb.c (c000000000091e70)
Location: arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:29
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_tlb.c:flush_tlb_pmd_range
  - arch/powerpc/mm/book3s64/hash_tlb.c:flush_tlb_pmd_range
  - arch/powerpc/mm/book3s64/hash_tlb.c:__flush_hash_table_range
  - arch/powerpc/mm/book3s64/hash_tlb.c:__flush_hash_table_range
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009f994)
Location: arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:29
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range
```
```
In mm/memory.c (c0000000003c58bc)
Location: arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:29
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
In mm/mprotect.c (c0000000003d21d0)
Location: arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:29
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3698)
Location: arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:29
Inline: True
```
```
In mm/madvise.c (c0000000003f309c)
Location: arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:29
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (c000000000434470)
Location: arch/powerpc/include/asm/book3s/64/tlbflush-hash.h:29
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
In arch/x86/kernel/paravirt.c (ffffffff81077e9a)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff8125bae5)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
```
```
In mm/mprotect.c (ffffffff81266576)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812680aa)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff8127cd9a)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812a6e7c)
Location: arch/x86/include/asm/paravirt.h:615
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
In arch/x86/kernel/paravirt.c (ffffffff81077e4a)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff81259885)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
```
```
In mm/mprotect.c (ffffffff81264316)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81265e4a)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff8127ab3a)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812a4c8c)
Location: arch/x86/include/asm/paravirt.h:615
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
In arch/x86/kernel/paravirt.c (ffffffff81079f38)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_end_context_switch
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In mm/memory.c (ffffffff81269283)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
```
```
In mm/mprotect.c (ffffffff81273cd6)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812757ec)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff8128a71a)
Location: arch/x86/include/asm/paravirt.h:615
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/migrate.c (ffffffff812b57e8)
Location: arch/x86/include/asm/paravirt.h:615
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
