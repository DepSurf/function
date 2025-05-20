# Function: <code>copy_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - fs/dax.c:__dax_fault
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
```
**Symbols:**

```
ffffffff813f5ed0-ffffffff813f5edb: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - fs/dax.c:dax_fault
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8143ca30-ffffffff8143ca3b: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_iomap_fault
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81459a10-ffffffff81459a1b: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - fs/dax.c:dax_iomap_fault
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff818fb570-ffffffff818fb57b: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_iomap_fault
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff819823c0-ffffffff819823cb: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff819de8d0-ffffffff819de8db: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81a19800-ffffffff81a1980b: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_shmem
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81a89510-ffffffff81a8951b: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_file
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81ac07b0-ffffffff81ac07bb: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_cow_fault
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:__copy_gigantic_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_copy
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff815fcaa0-ffffffff815fcaab: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:do_cow_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:__copy_gigantic_page
  - mm/khugepaged.c:collapse_file
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81621820-ffffffff8162182b: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_iomap_pte_fault
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81605120-ffffffff8160512b: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_replace_page
  - mm/util.c:copy_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_pte_range
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_fault_cow_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81673a10-ffffffff81673a1b: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void copy_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_page_64.S (ffffffff8178e060)
Location: arch/x86/lib/copy_page_64.S
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_replace_page
  - mm/util.c:folio_copy
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_fault_cow_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8178e060-ffffffff8178e06f: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void copy_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_page_64.S (ffffffff8204b8c0)
Location: arch/x86/lib/copy_page_64.S
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/util.c:folio_copy
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:do_fault
  - mm/memory.c:copy_present_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_fault_cow_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8204b8c0-ffffffff8204b8cf: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void copy_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_page_64.S (ffffffff820ca1b0)
Location: arch/x86/lib/copy_page_64.S
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/util.c:folio_copy
  - mm/memory.c:do_cow_fault
  - mm/memory.c:copy_present_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/migrate_device.c:migrate_device_coherent_page
  - fs/dax.c:dax_fault_cow_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff820ca1b0-ffffffff820ca1bf: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void copy_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_page_64.S (ffffffff821a4b10)
Location: arch/x86/lib/copy_page_64.S
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/util.c:folio_copy
  - mm/memory.c:do_fault
  - mm/memory.c:copy_present_pte
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/zsmalloc.c:zs_page_migrate
  - fs/dax.c:dax_fault_cow_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff821a4b10-ffffffff821a4b1f: copy_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm64/mm/copypage.c:__cpu_copy_user_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_swapin_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/khugepaged.c:collapse_file
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffff800010d82498-ffff800010d82544: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm/kernel/hibernate.c:arch_restore_image
  - arch/arm/mm/copypage-v6.c:v6_copy_user_highpage_nonaliasing
  - kernel/power/snapshot.c:restore_highmem
  - kernel/power/snapshot.c:restore_highmem
  - kernel/power/snapshot.c:restore_highmem
  - kernel/power/snapshot.c:copy_last_highmem_page
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_swapin_page
  - mm/migrate.c:__buffer_migrate_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
c0e7c460-c0e7c510: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/powerpc/kernel/machine_kexec_64.c:kexec_copy_flush
  - arch/powerpc/mm/mem.c:copy_user_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_swapin_page
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/khugepaged.c:collapse_file
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
c0000000000b326c-c0000000000b326c: copy_page (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_file
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81a5f600-ffffffff81a5f60b: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81a1c6d0-ffffffff81a1c6db: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_file
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81acb9f0-ffffffff81acb9fb: copy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - kernel/power/swap.c:write_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_file
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81ad7f40-ffffffff81ad7f4b: copy_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
