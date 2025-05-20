# Function: <code>early_section</code>

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
In arch/x86/mm/init_64.c (ffffffff8107dead)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81080964)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff8108528c)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087484)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81100696)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81180ab0)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81211c21)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff81244f1c)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff81257183)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff812734bb)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81281bca)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81a97385)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffffffff81a92250)
Location: include/linux/mmzone.h:1284
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
In mm/migrate.c (ffffffff8129e204)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a8554)
Location: include/linux/mmzone.h:1284
Inline: True
```
```
In mm/memory-failure.c (ffffffff812ba356)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/cma.c (ffffffff812bfacf)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812c1611)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812c1de0)
Location: include/linux/mmzone.h:1284
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81367cfe)
Location: include/linux/mmzone.h:1284
Inline: True
```
```
In fs/proc/page.c (ffffffff81369a89)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff81622a09)
Location: include/linux/mmzone.h:1284
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81650fc8)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff816f86cb)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/edac/edac_mc.c (ffffffff81885af9)
Location: include/linux/mmzone.h:1284
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818d051c)
Location: include/linux/mmzone.h:1284
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
In arch/x86/mm/init_64.c (ffffffff8107ef3d)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81081634)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81085f7c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81088174)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8110caf6)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8118c920)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8121f411)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff812533dc)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff81265713)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8128232b)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81290b9c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81acec67)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffffffff81ac99e0)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812adab4)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b9a34)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In mm/memory-failure.c (ffffffff812cba86)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812d1a1f)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812d3541)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812d3d10)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8137ff7e)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff816444d9)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81673568)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff8171cab1)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3128)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818b7a99)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8190290c)
Location: include/linux/mmzone.h:1291
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
In arch/x86/mm/init_64.c (ffffffff8108586a)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8108858d)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810896e3)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a61a)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81117d88)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:mark_nosave_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811a12f3)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8124b686)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff8128231e)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff81295844)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/page_alloc.c (ffffffff812b4449)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff812c3d29)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
```
In mm/sparse.c (ffffffff81bc7598)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffffffff812e0dba)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812e2586)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/huge_memory.c (ffffffff812ee588)
Location: include/linux/mmzone.h:1268
Inline: True
```
```
In mm/memory-failure.c (ffffffff81302844)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/frame_vector.c (ffffffff813097ee)
Location: include/linux/mmzone.h:1268
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813ca6fe)
Location: include/linux/mmzone.h:1268
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0f97)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817237fb)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e04f)
Location: include/linux/mmzone.h:1268
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81987d2b)
Location: include/linux/mmzone.h:1268
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff819d9882)
Location: include/linux/mmzone.h:1268
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
In arch/x86/mm/init_64.c (ffffffff8108691a)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810887cd)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810898c3)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a8ba)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff811141c8)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:mark_nosave_pages
```
```
In kernel/dma/mapping.c (ffffffff81137659)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_map_resource
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e443)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81255a76)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff8128c465)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff812a0c29)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
```
```
In mm/vmalloc.c (ffffffff812b223f)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/page_alloc.c (ffffffff812bccfe)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff812cf3db)
Location: include/linux/mmzone.h:1306
Inline: True
```
```
In mm/sparse.c (ffffffff81c402c4)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffffffff812ebbba)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812ed9b6)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/huge_memory.c (ffffffff812f9bfb)
Location: include/linux/mmzone.h:1306
Inline: True
```
```
In mm/memory-failure.c (ffffffff8130eb2f)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/frame_vector.c (ffffffff813155fe)
Location: include/linux/mmzone.h:1306
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813dc3be)
Location: include/linux/mmzone.h:1306
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e177)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8174053b)
Location: include/linux/mmzone.h:1306
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ace8f)
Location: include/linux/mmzone.h:1306
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8198bc5b)
Location: include/linux/mmzone.h:1306
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff819d8be0)
Location: include/linux/mmzone.h:1306
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
In arch/x86/mm/init_64.c (ffffffff81086798)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810893d8)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:pfn_valid
```
```
In arch/x86/mm/mmap.c (ffffffff8108a0d8)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_valid
```
```
In arch/x86/mm/physaddr.c (ffffffff8108b4a8)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:pfn_valid
```
```
In kernel/power/snapshot.c (ffffffff81112b68)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - kernel/power/snapshot.c:pfn_valid
```
```
In kernel/dma/mapping.c (ffffffff811383c8)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - kernel/dma/mapping.c:pfn_valid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119f018)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:pfn_valid
```
```
In kernel/iomem.c (ffffffff8125a018)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - kernel/iomem.c:pfn_valid
```
```
In mm/compaction.c (ffffffff81291320)
Location: include/linux/mmzone.h:1371
Inline: True
```
```
In mm/memory.c (ffffffff8129c4d8)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - mm/memory.c:pfn_valid
```
```
In mm/vmalloc.c (ffffffff812b78b8)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - mm/vmalloc.c:pfn_valid
```
```
In mm/page_alloc.c (ffffffff812bf2d8)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - mm/page_alloc.c:pfn_valid
```
```
In mm/memory_hotplug.c (ffffffff812c6358)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - mm/memory_hotplug.c:pfn_valid
```
```
In mm/hugetlb.c (ffffffff812d606b)
Location: include/linux/mmzone.h:1371
Inline: True
```
```
In mm/sparse.c (ffffffff81c32437)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/migrate.c (ffffffff812f2e38)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - mm/migrate.c:pfn_valid
```
```
In mm/huge_memory.c (ffffffff8130037f)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff81312988)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - mm/memory-failure.c:pfn_valid
```
```
In fs/proc/kcore.c (ffffffff813e2cc8)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - fs/proc/kcore.c:pfn_valid
```
```
In drivers/acpi/apei/ghes.c (ffffffff816ef898)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:pfn_valid
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723cf8)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:pfn_valid
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8188f978)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:pfn_valid
```
```
In drivers/edac/edac_mc.c (ffffffff81970358)
Location: include/linux/mmzone.h:1371
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:pfn_valid
```
```
In drivers/ras/cec.c (ffffffff819be988)
Location: include/linux/mmzone.h:1371
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
In arch/x86/mm/init_64.c (ffffffff81095a7e)
Location: include/linux/mmzone.h:1408
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81098867)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:pfn_valid
```
```
In arch/x86/mm/mmap.c (ffffffff81099617)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_valid
```
```
In arch/x86/mm/physaddr.c (ffffffff8109aa55)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:pfn_valid
```
```
In kernel/power/snapshot.c (ffffffff81132d9e)
Location: include/linux/mmzone.h:1408
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff8115b225)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - kernel/dma/mapping.c:pfn_valid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c8ea5)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:pfn_valid
```
```
In kernel/iomem.c (ffffffff81295de5)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - kernel/iomem.c:pfn_valid
```
```
In mm/compaction.c (ffffffff812d0f27)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - mm/compaction.c:pfn_valid
```
```
In mm/memory.c (ffffffff812dd1ee)
Location: include/linux/mmzone.h:1408
Inline: True
```
```
In mm/vmalloc.c (ffffffff812f9fe7)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - mm/vmalloc.c:pfn_valid
```
```
In mm/page_alloc.c (ffffffff81301c1e)
Location: include/linux/mmzone.h:1408
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8130bddf)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - mm/memory_hotplug.c:adjust_present_page_count
```
```
In mm/hugetlb.c (ffffffff8131bb37)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - mm/hugetlb.c:pfn_valid
```
```
In mm/sparse.c (ffffffff81d50e33)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/huge_memory.c (ffffffff81349fe7)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff8135e5be)
Location: include/linux/mmzone.h:1408
Inline: True
```
```
In mm/bootmem_info.c (ffffffff832de811)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff814347f7)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - fs/proc/kcore.c:pfn_valid
```
```
In drivers/acpi/apei/ghes.c (ffffffff81769905)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:pfn_valid
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2c7e)
Location: include/linux/mmzone.h:1408
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923297)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:pfn_valid
```
```
In drivers/edac/edac_mc.c (ffffffff81a18c77)
Location: include/linux/mmzone.h:1408
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:pfn_valid
```
```
In drivers/ras/cec.c (ffffffff81a6df25)
Location: include/linux/mmzone.h:1408
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
In arch/x86/mm/init_64.c (ffffffff810a93a3)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810ab541)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810acabc)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810addcb)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81156e25)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fcabf)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812ebb62)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff8132fd78)
Location: include/linux/mmzone.h:1454
Inline: True
```
```
In mm/memory.c (ffffffff81348c2c)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
```
```
In mm/vmalloc.c (ffffffff8136034a)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff8136d59b)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory_hotplug.c (ffffffff81f1ba9d)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:adjust_present_page_count
```
```
In mm/hugetlb.c (ffffffff8138820d)
Location: include/linux/mmzone.h:1454
Inline: True
```
```
In mm/sparse.c (ffffffff81f21049)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/huge_memory.c (ffffffff813c0a27)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff813dd1e0)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff834940f4)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff814aedde)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e5de)
Location: include/linux/mmzone.h:1454
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd133)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79504)
Location: include/linux/mmzone.h:1454
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81b81fcb)
Location: include/linux/mmzone.h:1454
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81bdf190)
Location: include/linux/mmzone.h:1454
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
In arch/x86/mm/ioremap.c (ffffffff810c5979)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810c6bdb)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810c8016)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81187afb)
Location: include/linux/mmzone.h:1786
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
In kernel/debug/kdb/kdb_support.c (ffffffff812441e7)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81355da9)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813782d7)
Location: include/linux/mmzone.h:1786
Inline: True
```
```
In mm/compaction.c (ffffffff813a6921)
Location: include/linux/mmzone.h:1786
Inline: True
```
```
In mm/memory.c (ffffffff813bd994)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/vmalloc.c (ffffffff813dc349)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff83ebe7d5)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory_hotplug.c (ffffffff820c3a84)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:adjust_present_page_count
```
```
In mm/sparse.c (ffffffff820cac67)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff81463f91)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff83ec864c)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff81545495)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7ae9)
Location: include/linux/mmzone.h:1786
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30612)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/edac/edac_mc.c (ffffffff81d207ee)
Location: include/linux/mmzone.h:1786
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81d8a792)
Location: include/linux/mmzone.h:1786
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
In arch/x86/mm/ioremap.c (ffffffff810c90fc)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810ca317)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810cb74a)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81198c8b)
Location: include/linux/mmzone.h:1911
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
In kernel/debug/kdb/kdb_support.c (ffffffff8125b2c7)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81387439)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813abb27)
Location: include/linux/mmzone.h:1911
Inline: True
```
```
In mm/mm_init.c (ffffffff836e0545)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff813da173)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff813f2694)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/vmalloc.c (ffffffff81410c68)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff8141c7a7)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory_hotplug.c (ffffffff821477fe)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:adjust_present_page_count
```
```
In mm/sparse.c (ffffffff8214eef7)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff81499a4d)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff836ed6ab)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff8157d075)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a301f9)
Location: include/linux/mmzone.h:1911
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79e27)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/edac/edac_mc.c (ffffffff81d899ce)
Location: include/linux/mmzone.h:1911
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81df8d92)
Location: include/linux/mmzone.h:1911
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
In arch/x86/mm/ioremap.c (ffffffff810d0ddb)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810d2789)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810d3dad)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff811a7aee)
Location: include/linux/mmzone.h:1922
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
In kernel/debug/kdb/kdb_support.c (ffffffff812751b9)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff813b0dca)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813d6251)
Location: include/linux/mmzone.h:1922
Inline: True
```
```
In mm/mm_init.c (ffffffff83912d9b)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff81403e8e)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8141d38a)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/vmalloc.c (ffffffff8143ef9d)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff814492a1)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory_hotplug.c (ffffffff8222a0a8)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:adjust_present_page_count
```
```
In mm/sparse.c (ffffffff82231d71)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff814c925d)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff839206c9)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff815b59e3)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b363)
Location: include/linux/mmzone.h:1922
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc28f)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/edac/edac_mc.c (ffffffff81e41158)
Location: include/linux/mmzone.h:1922
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81eaf441)
Location: include/linux/mmzone.h:1922
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
In mm/sparse.c (ffff800010da0884)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
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
In arch/powerpc/kernel/stacktrace.c (c000000000069180)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/powerpc/kernel/stacktrace.c:pfn_valid
```
```
In arch/powerpc/mm/pgtable.c (c000000000087898)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:maybe_pte_to_page
```
```
In arch/powerpc/mm/init_64.c (c000000000eeb16c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/powerpc/mm/init_64.c:vmemmap_populated
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008cf84)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_do_lazy_icache
```
```
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fae28)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock
```
```
In kernel/debug/kdb/kdb_support.c (c00000000027e474)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/events/core.c (c000000000350a98)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/iomem.c (c00000000035fb18)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (c0000000003ad93c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (c0000000003c78cc)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (c0000000003edef4)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (c000000000406c88)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (c000000000eed4d4)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (c0000000004309a8)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (c0000000004324fc)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (c000000000443bdc)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In mm/memory-failure.c (c00000000046096c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (c000000000469a8c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (c00000000046bfa8)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c00000000046cfac)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In mm/usercopy.c (c00000000046d434)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In fs/proc/kcore.c (c000000000565544)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In drivers/base/memory.c (c0000000009b1648)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/spi/spi.c (c000000000a89f4c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/edac/edac_mc.c (c000000000c0337c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5b628)
Location: include/linux/mmzone.h:1291
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
In kernel/events/core.c (ffffffe0001ceffe)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/iomem.c (ffffffe0001d366c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffe0001f4590)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffe0001ff110)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffe00020b6f8)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/page_alloc.c (ffffffe00021bbba)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffe00022c7f8)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffe00023e92c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/page_isolation.c (ffffffe00024b326)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffe00024f4e0)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffe00025092a)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffe000250f80)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In mm/usercopy.c (ffffffe000251262)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In fs/proc/kcore.c (ffffffe0002e2540)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In fs/proc/page.c (ffffffe0002e30d0)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/spi/spi.c (ffffffe000618b64)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/edac/edac_mc.c (ffffffe0006fcf50)
Location: include/linux/mmzone.h:1291
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
In arch/x86/mm/init_64.c (ffffffff8107df3d)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81080634)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81084f7c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087174)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81104d16)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81184f40)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81217a61)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff8124ba2c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8125dd63)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8127a97b)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff8128917c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81a6dad7)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffffffff81a68850)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a6094)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b2014)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c4066)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812c9fff)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812cbb21)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812cc2f0)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8137855e)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81639258)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff816e2de1)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/edac/edac_mc.c (ffffffff8185d919)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818a1d3c)
Location: include/linux/mmzone.h:1291
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
In arch/x86/mm/init_64.c (ffffffff8106d1d9)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106f584)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81073c4c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81075d44)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810f5fb6)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81178080)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8120ac71)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff8123e9cc)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff812501b3)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8126c85b)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff8127b01c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81a2a01e)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffffffff81a25310)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81297b44)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a33a4)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In mm/memory-failure.c (ffffffff812b50a6)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812bb03f)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812bc9a1)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812bd160)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8136902e)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In drivers/base/memory.c (ffffffff816bd421)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d1d8)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81824ee9)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8185d4ac)
Location: include/linux/mmzone.h:1291
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
In arch/x86/mm/init_64.c (ffffffff8107deed)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810805e4)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81084f2c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087124)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81102fc6)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81182d10)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81215801)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff812497cc)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8125bb03)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8127871b)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81286f8c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81ad9ee7)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffffffff81ad4c60)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a3ea4)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812afe24)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c1e76)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812c7e0f)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812c9931)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812ca100)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8137602e)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff81638319)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816673a8)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff8170ff71)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c7fa8)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818acf49)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818f332c)
Location: include/linux/mmzone.h:1291
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
In arch/x86/mm/init_64.c (ffffffff8107ffdd)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81082704)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff8108707c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81089254)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8110e3b6)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81190638)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81224801)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff8125904c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8126b4ea)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8128830b)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff8129765c)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81ae639d)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffffffff81ae113b)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812b4774)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812c0164)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In mm/memory-failure.c (ffffffff812d2916)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812d8b1f)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812da631)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812dae00)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81389ade)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652659)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81681968)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff8172b0d1)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2248)
Location: include/linux/mmzone.h:1291
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818c9199)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff819143cc)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
</ul>

## Differences
