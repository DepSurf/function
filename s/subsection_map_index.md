# Function: <code>subsection_map_index</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107deb6)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81080969)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81085297)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087494)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8110069b)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81180ab5)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81211c2a)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff81244f21)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8125718d)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff812734c0)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81281bce)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff828d8e8d)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/memory_hotplug.c (ffffffff81a92255)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
```
```
In mm/migrate.c (ffffffff8129e209)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a8559)
Location: include/linux/mmzone.h:1318
Inline: True
```
```
In mm/memory-failure.c (ffffffff812ba35b)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/cma.c (ffffffff812bfad9)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812c1616)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812c1de5)
Location: include/linux/mmzone.h:1318
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81367d00)
Location: include/linux/mmzone.h:1318
Inline: True
```
```
In fs/proc/page.c (ffffffff81369a8e)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff81622b35)
Location: include/linux/mmzone.h:1318
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81650fcd)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff816f86d0)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
```
```
In drivers/edac/edac_mc.c (ffffffff81885afe)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818d0525)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In arch/x86/mm/init_64.c (ffffffff8107ef46)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81081639)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81085f87)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81088184)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8110cafb)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8118c925)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8121f41a)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff812533e1)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8126571d)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff81282330)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81290ba2)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff828e12e0)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/memory_hotplug.c (ffffffff81ac99e5)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812adab9)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b9a39)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In mm/memory-failure.c (ffffffff812cba8b)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812d1a29)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812d3546)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812d3d15)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8137ff80)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff81644605)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8167356d)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff8171cab7)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d312d)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818b7a9e)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff81902915)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In arch/x86/mm/init_64.c (ffffffff81085928)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81088592)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff81089726)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a625)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81117d8d)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:mark_nosave_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811a13c8)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8124b6c7)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff81282323)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff81295849)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/page_alloc.c (ffffffff812b444e)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff812c3d2f)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
```
In mm/sparse.c (ffffffff82cfe92a)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/memory_hotplug.c (ffffffff812e0dbf)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812e258f)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/huge_memory.c (ffffffff812ee58d)
Location: include/linux/mmzone.h:1302
Inline: True
```
```
In mm/memory-failure.c (ffffffff81302932)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/frame_vector.c (ffffffff813097f3)
Location: include/linux/mmzone.h:1302
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813ca728)
Location: include/linux/mmzone.h:1302
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0f9d)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723989)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e083)
Location: include/linux/mmzone.h:1302
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81987da5)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff819d988b)
Location: include/linux/mmzone.h:1302
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In arch/x86/mm/init_64.c (ffffffff810869d8)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810887d2)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff81089906)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a8c5)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff811141cd)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:mark_nosave_pages
```
```
In kernel/dma/mapping.c (ffffffff8113765f)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_map_resource
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e518)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81255ab7)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff8128c46a)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff812a0c2e)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
```
```
In mm/vmalloc.c (ffffffff812b2248)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/page_alloc.c (ffffffff812bcd03)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff812cf3e0)
Location: include/linux/mmzone.h:1340
Inline: True
```
```
In mm/sparse.c (ffffffff82feb406)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/memory_hotplug.c (ffffffff812ebbbf)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812ed9bf)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/huge_memory.c (ffffffff812f9c00)
Location: include/linux/mmzone.h:1340
Inline: True
```
```
In mm/memory-failure.c (ffffffff8130ed4e)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/frame_vector.c (ffffffff81315603)
Location: include/linux/mmzone.h:1340
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813dc3e8)
Location: include/linux/mmzone.h:1340
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e17d)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817406d0)
Location: include/linux/mmzone.h:1340
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818acec3)
Location: include/linux/mmzone.h:1340
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8198bcd5)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff819d8be9)
Location: include/linux/mmzone.h:1340
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In arch/x86/mm/init_64.c (ffffffff810867b4)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810893f4)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:pfn_valid
```
```
In arch/x86/mm/mmap.c (ffffffff8108a0f4)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_valid
```
```
In arch/x86/mm/physaddr.c (ffffffff8108b4c4)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:pfn_valid
```
```
In kernel/power/snapshot.c (ffffffff81112b84)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - kernel/power/snapshot.c:pfn_valid
```
```
In kernel/dma/mapping.c (ffffffff811383e4)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - kernel/dma/mapping.c:pfn_valid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119f034)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:pfn_valid
```
```
In kernel/iomem.c (ffffffff8125a034)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - kernel/iomem.c:pfn_valid
```
```
In mm/compaction.c (ffffffff81291324)
Location: include/linux/mmzone.h:1410
Inline: True
```
```
In mm/memory.c (ffffffff8129c4f4)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - mm/memory.c:pfn_valid
```
```
In mm/vmalloc.c (ffffffff812b78d4)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - mm/vmalloc.c:pfn_valid
```
```
In mm/page_alloc.c (ffffffff812bf2f4)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - mm/page_alloc.c:pfn_valid
```
```
In mm/memory_hotplug.c (ffffffff812c63d8)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
  - mm/memory_hotplug.c:pfn_valid
```
```
In mm/hugetlb.c (ffffffff812d6070)
Location: include/linux/mmzone.h:1410
Inline: True
```
```
In mm/sparse.c (ffffffff831f5d6d)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/migrate.c (ffffffff812f2e54)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - mm/migrate.c:pfn_valid
```
```
In mm/huge_memory.c (ffffffff81300383)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff813129a4)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - mm/memory-failure.c:pfn_valid
```
```
In fs/proc/kcore.c (ffffffff813e2ce4)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - fs/proc/kcore.c:pfn_valid
```
```
In drivers/acpi/apei/ghes.c (ffffffff816ef8b4)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:pfn_valid
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723d14)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:pfn_valid
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8188f994)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:pfn_valid
```
```
In drivers/edac/edac_mc.c (ffffffff81970374)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:pfn_valid
```
```
In drivers/ras/cec.c (ffffffff819be9a4)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - drivers/ras/cec.c:pfn_valid
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
In arch/x86/mm/init_64.c (ffffffff81095a9a)
Location: include/linux/mmzone.h:1447
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81098872)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:pfn_valid
```
```
In arch/x86/mm/mmap.c (ffffffff81099622)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_valid
```
```
In arch/x86/mm/physaddr.c (ffffffff8109aa5f)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:pfn_valid
```
```
In kernel/power/snapshot.c (ffffffff81132dba)
Location: include/linux/mmzone.h:1447
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff8115b22f)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - kernel/dma/mapping.c:pfn_valid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c8eaf)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:pfn_valid
```
```
In kernel/iomem.c (ffffffff81295def)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - kernel/iomem.c:pfn_valid
```
```
In mm/compaction.c (ffffffff812d0f32)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - mm/compaction.c:pfn_valid
```
```
In mm/memory.c (ffffffff812dd20a)
Location: include/linux/mmzone.h:1447
Inline: True
```
```
In mm/vmalloc.c (ffffffff812f9ff2)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - mm/vmalloc.c:pfn_valid
```
```
In mm/page_alloc.c (ffffffff81301c3a)
Location: include/linux/mmzone.h:1447
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8130aec8)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/hugetlb.c (ffffffff8131bb42)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - mm/hugetlb.c:pfn_valid
```
```
In mm/sparse.c (ffffffff832dc443)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/huge_memory.c (ffffffff81349feb)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff8135e5da)
Location: include/linux/mmzone.h:1447
Inline: True
```
```
In mm/bootmem_info.c (ffffffff832de825)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff81434802)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - fs/proc/kcore.c:pfn_valid
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176990f)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:pfn_valid
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2c9a)
Location: include/linux/mmzone.h:1447
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819232a2)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:pfn_valid
```
```
In drivers/edac/edac_mc.c (ffffffff81a18c82)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:pfn_valid
```
```
In drivers/ras/cec.c (ffffffff81a6df2f)
Location: include/linux/mmzone.h:1447
Inline: True
Inline callers:
  - drivers/ras/cec.c:pfn_valid
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
In arch/x86/mm/init_64.c (ffffffff810a93ac)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810ab5a5)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810acac0)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810addd9)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81156e29)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fcac3)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812ebb66)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff8132fd7c)
Location: include/linux/mmzone.h:1493
Inline: True
```
```
In mm/memory.c (ffffffff81348c31)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
```
```
In mm/vmalloc.c (ffffffff81360350)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff8136d59f)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory_hotplug.c (ffffffff81f1baa1)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/hugetlb.c (ffffffff81388212)
Location: include/linux/mmzone.h:1493
Inline: True
```
```
In mm/sparse.c (ffffffff83491c41)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/huge_memory.c (ffffffff813c0a2b)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff813dd1e5)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff83494108)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff814aede3)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e5e2)
Location: include/linux/mmzone.h:1493
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd138)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79509)
Location: include/linux/mmzone.h:1493
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81b81fd0)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81bdf199)
Location: include/linux/mmzone.h:1493
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In arch/x86/mm/ioremap.c (ffffffff810c59dd)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810c6bdf)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810c8024)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81187aff)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff812441eb)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81355dad)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813782e0)
Location: include/linux/mmzone.h:1832
Inline: True
```
```
In mm/compaction.c (ffffffff813a6925)
Location: include/linux/mmzone.h:1832
Inline: True
```
```
In mm/memory.c (ffffffff813bd998)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/vmalloc.c (ffffffff813dc353)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff83ebe870)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory_hotplug.c (ffffffff820c3a88)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/sparse.c (ffffffff83ec549d)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/memory-failure.c (ffffffff81463f95)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff83ec8754)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff8154549a)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7af1)
Location: include/linux/mmzone.h:1832
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30617)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/edac/edac_mc.c (ffffffff81d207f3)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81d8a797)
Location: include/linux/mmzone.h:1832
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In arch/x86/mm/ioremap.c (ffffffff810c9158)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810ca31b)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810cb758)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81198c8f)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125b2cb)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8138743d)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813abb30)
Location: include/linux/mmzone.h:1957
Inline: True
```
```
In mm/mm_init.c (ffffffff836e05e0)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff813da177)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff813f2698)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/vmalloc.c (ffffffff81410c71)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff8141c7ab)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory_hotplug.c (ffffffff82147806)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/sparse.c (ffffffff836ea55d)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/memory-failure.c (ffffffff81499a51)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff836ed7bf)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff8157d07a)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a30201)
Location: include/linux/mmzone.h:1957
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79e2c)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/edac/edac_mc.c (ffffffff81d899d3)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81df8d97)
Location: include/linux/mmzone.h:1957
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In arch/x86/mm/ioremap.c (ffffffff810d0e5b)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810d278d)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810d3db7)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff811a7af3)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff812751bd)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff813b0dce)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813d6292)
Location: include/linux/mmzone.h:1968
Inline: True
```
```
In mm/mm_init.c (ffffffff83912e77)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff81403e93)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8141d3be)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/vmalloc.c (ffffffff8143efc7)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff814492a5)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory_hotplug.c (ffffffff8222a0ac)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/sparse.c (ffffffff8391d921)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/memory-failure.c (ffffffff814c9261)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff83920801)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff815b59e8)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b367)
Location: include/linux/mmzone.h:1968
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc294)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/edac/edac_mc.c (ffffffff81e4115d)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81eaf446)
Location: include/linux/mmzone.h:1968
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In mm/sparse.c (ffff80001145a464)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
</details>
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
In arch/powerpc/kernel/stacktrace.c (c000000000069190)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/powerpc/kernel/stacktrace.c:pfn_valid
```
```
In arch/powerpc/mm/pgtable.c (c0000000000878a4)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:maybe_pte_to_page
```
```
In arch/powerpc/mm/init_64.c (c000000000eeb178)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/powerpc/mm/init_64.c:vmemmap_populated
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008cf94)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_do_lazy_icache
```
```
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fae3c)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock
```
```
In kernel/debug/kdb/kdb_support.c (c00000000027e480)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/events/core.c (c000000000350aa4)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/iomem.c (c00000000035fb24)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (c0000000003ad948)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (c0000000003c78d8)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (c0000000003ee154)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (c000000000406c94)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (c000000001384444)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/memory_hotplug.c (c0000000004309b4)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (c000000000432508)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (c000000000443be8)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In mm/memory-failure.c (c000000000460988)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (c000000000469a9c)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (c00000000046bfc0)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c00000000046cfd4)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In mm/usercopy.c (c00000000046d440)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In fs/proc/kcore.c (c000000000565574)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In drivers/base/memory.c (c0000000009b1654)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
```
```
In drivers/spi/spi.c (c000000000a8a0ec)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/edac/edac_mc.c (c000000000c03388)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5b634)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
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
In kernel/events/core.c (ffffffe0001cf004)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/iomem.c (ffffffe0001d3672)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffe0001f4596)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffe0001ff116)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffe00020b700)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/page_alloc.c (ffffffe00021bbbe)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffe00022c804)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffe000018542)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/migrate.c (ffffffe00023e932)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/page_isolation.c (ffffffe00024b336)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffe00024f4e8)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffe000250930)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffe000250f8c)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In mm/usercopy.c (ffffffe000251268)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In fs/proc/kcore.c (ffffffe0002e2546)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In fs/proc/page.c (ffffffe0002e30d8)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/spi/spi.c (ffffffe000618b88)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/edac/edac_mc.c (ffffffe0006fcf56)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
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
In arch/x86/mm/init_64.c (ffffffff8107df46)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81080639)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81084f87)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087184)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81104d1b)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81184f45)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81217a6a)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff8124ba31)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8125dd6d)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8127a980)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81289182)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff828ca194)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/memory_hotplug.c (ffffffff81a68855)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a6099)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b2019)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c406b)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812ca009)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812cbb26)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812cc2f5)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81378560)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8163925d)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff816e2de7)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
```
```
In drivers/edac/edac_mc.c (ffffffff8185d91e)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818a1d45)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In arch/x86/mm/init_64.c (ffffffff8106d1e3)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106f589)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81073c57)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81075d54)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810f5fbb)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81178085)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8120ac7a)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff8123e9d1)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff812501bd)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8126c860)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff8127b022)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff828c28b9)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/memory_hotplug.c (ffffffff81a25315)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81297b49)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a33a9)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In mm/memory-failure.c (ffffffff812b50ab)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812bb049)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812bc9a6)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812bd165)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81369030)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In drivers/base/memory.c (ffffffff816bd427)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d1dd)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81824eee)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8185d4b5)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In arch/x86/mm/init_64.c (ffffffff8107def6)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810805e9)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81084f37)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087134)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81102fcb)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81182d15)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8121580a)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff812497d1)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8125bb0d)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff81278720)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81286f92)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff828dcf14)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/memory_hotplug.c (ffffffff81ad4c65)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a3ea9)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812afe29)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c1e7b)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812c7e19)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812c9936)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812ca105)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81376030)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff81638445)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816673ad)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff8170ff77)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c7fad)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818acf4e)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818f3335)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In arch/x86/mm/init_64.c (ffffffff8107ffe6)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81082709)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81087087)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81089264)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8110e3bb)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119063d)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8122480a)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff81259051)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8126b4ef)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff81288310)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81297662)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff828e232b)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_mask_set
  - mm/sparse.c:subsection_mask_set
```
```
In mm/memory_hotplug.c (ffffffff81ae1140)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812b477a)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812c0169)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In mm/memory-failure.c (ffffffff812d291b)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812d8b29)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812da636)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812dae05)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81389ae0)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652785)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8168196d)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff8172b0d7)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e224d)
Location: include/linux/mmzone.h:1325
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818c919e)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff819143d5)
Location: include/linux/mmzone.h:1325
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
</ul>

## Differences
