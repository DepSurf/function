# Function: <code>set_ptes</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81039130)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_unmap
  - arch/x86/xen/grant-table.c:arch_gnttab_map_status
  - arch/x86/xen/grant-table.c:arch_gnttab_map_shared
```
```
In arch/x86/kernel/ldt.c (ffffffff8105b122)
Location: include/linux/pgtable.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff810616f0)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81070bb0)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810993f0)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young_cb
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c2d4d)
Location: include/linux/pgtable.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:__ptep_modify_prot_commit
```
```
In kernel/events/uprobes.c (ffffffff813a9860)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff8140df90)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8141e549)
Location: include/linux/pgtable.h:238
Inline: True
Inline callers:
  - mm/memory.c:remap_pfn_range_notrack
Direct callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff8142f25a)
Location: include/linux/pgtable.h:238
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81431177)
Location: include/linux/pgtable.h:238
Inline: True
```
```
In mm/rmap.c (ffffffff81437920)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8143e2b0)
Location: include/linux/pgtable.h:238
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
Direct callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/madvise.c (ffffffff8146111d)
Location: include/linux/pgtable.h:238
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff81468d60)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81474ad0)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480af8)
Location: include/linux/pgtable.h:238
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
Direct callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
```
```
In mm/sparse-vmemmap.c (ffffffff81489030)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8148d680)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81497700)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149cb90)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a17e2)
Location: include/linux/pgtable.h:238
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814cfe30)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/proc/task_mmu.c (ffffffff8159cb50)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - fs/proc/task_mmu.c:make_uffd_wp_pte
  - fs/proc/task_mmu.c:make_uffd_wp_pte
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/xen/xlate_mmu.c (ffffffff81ad0130)
Location: include/linux/pgtable.h:238
Inline: True
Direct callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
**Symbols:**

```
ffffffff81039130-ffffffff81039174: set_ptes.constprop.0 (STB_LOCAL)
ffffffff810616f0-ffffffff81061734: set_ptes.constprop.0 (STB_LOCAL)
ffffffff81070bb0-ffffffff81070bf4: set_ptes.constprop.0 (STB_LOCAL)
ffffffff810993f0-ffffffff81099434: set_ptes.constprop.0 (STB_LOCAL)
ffffffff813a9860-ffffffff813a98a4: set_ptes.constprop.0 (STB_LOCAL)
ffffffff8140df90-ffffffff8140dfd4: set_ptes.constprop.0 (STB_LOCAL)
ffffffff81415ff0-ffffffff81416091: set_ptes.isra.0 (STB_LOCAL)
ffffffff81437920-ffffffff81437964: set_ptes.constprop.0 (STB_LOCAL)
ffffffff8143ee10-ffffffff8143ee54: set_ptes.constprop.0 (STB_LOCAL)
ffffffff81468d60-ffffffff81468da4: set_ptes.constprop.0 (STB_LOCAL)
ffffffff81474ad0-ffffffff81474b14: set_ptes.constprop.0 (STB_LOCAL)
ffffffff81480fc0-ffffffff81481004: set_ptes.constprop.0 (STB_LOCAL)
ffffffff81489030-ffffffff81489074: set_ptes.constprop.0 (STB_LOCAL)
ffffffff8148d680-ffffffff8148d6c4: set_ptes.constprop.0 (STB_LOCAL)
ffffffff81497700-ffffffff81497744: set_ptes.constprop.0 (STB_LOCAL)
ffffffff8149cb90-ffffffff8149cbd4: set_ptes.constprop.0 (STB_LOCAL)
ffffffff814cfe30-ffffffff814cfe74: set_ptes.constprop.0 (STB_LOCAL)
ffffffff8159cb50-ffffffff8159cb94: set_ptes.constprop.0 (STB_LOCAL)
ffffffff81ad0130-ffffffff81ad0174: set_ptes.constprop.0 (STB_LOCAL)
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
