# Function: <code>__nr_to_section</code>

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
In arch/x86/mm/init_64.c (ffffffff81069adf)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106b914)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/physaddr.c (ffffffff8107144e)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810d06f8)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811379c2)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In mm/page_alloc.c (ffffffff8181ce42)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:get_pfnblock_flags_mask
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/vmstat.c (ffffffff811acfd8)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811b4bd3)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - mm/compaction.c:pageblock_pfn_to_page
  - mm/compaction.c:pageblock_pfn_to_page
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff811c1c78)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_pfn
  - mm/memory.c:clear_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
```
```
In mm/hugetlb.c (ffffffff811daa3a)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/sparse.c (ffffffff81f8c550)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:__section_nr
  - mm/sparse.c:node_memmap_size_bytes
  - mm/sparse.c:memory_present
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/sparse-vmemmap.c (ffffffff81f8caba)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff811ef19d)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:walk_memory_range
```
```
In mm/migrate.c (ffffffff811f1f68)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff811f5c27)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/memory-failure.c (ffffffff81201b3b)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff81f8e328)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff812080f8)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812089a7)
Location: include/linux/mmzone.h:1074
Inline: True
```
```
In fs/proc/page.c (ffffffff81287e8d)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpageflags_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b6055)
Location: include/linux/mmzone.h:1074
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d4872)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff81560a52)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/base/memory.c (ffffffff81560f4e)
Location: include/linux/mmzone.h:1074
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:show_mem_removable
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
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
In arch/x86/mm/init_64.c (ffffffff81069860)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106b7f4)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/physaddr.c (ffffffff8107133f)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810d6eae)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8113fe8a)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/memremap.c (ffffffff8119e45b)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
```
```
In mm/page_alloc.c (ffffffff811acab7)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/vmstat.c (ffffffff811c626e)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811cee52)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff811ddf61)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff811fa0d1)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81899523)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_init
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:memory_present
  - mm/sparse.c:__section_nr
  - mm/sparse.c:node_memmap_size_bytes
```
```
In mm/sparse-vmemmap.c (ffffffff81fb682b)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff8120ee73)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812109ef)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8121859d)
Location: include/linux/mmzone.h:1146
Inline: True
```
```
In mm/memory-failure.c (ffffffff812276db)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff81fb891c)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff8122db21)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8122e39f)
Location: include/linux/mmzone.h:1146
Inline: True
```
```
In fs/proc/page.c (ffffffff812b51dd)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff815059d8)
Location: include/linux/mmzone.h:1146
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81525832)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff815b5429)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/base/memory.c (ffffffff81fd9d3b)
Location: include/linux/mmzone.h:1146
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:show_mem_removable
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
In arch/x86/mm/init_64.c (ffffffff8106d440)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106f40e)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/physaddr.c (ffffffff81074ebf)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810dda2f)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81149c5e)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/memremap.c (ffffffff811ade8b)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
```
```
In mm/page_alloc.c (ffffffff811bd080)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/vmstat.c (ffffffff811d63a7)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811def69)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff811edd76)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff8120ab99)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff818cdbdb)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_init
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:memory_present
  - mm/sparse.c:__section_nr
  - mm/sparse.c:node_memmap_size_bytes
```
```
In mm/sparse-vmemmap.c (ffffffff81ff31f4)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff81220f6d)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81222b3d)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8122ab28)
Location: include/linux/mmzone.h:1124
Inline: True
```
```
In mm/memory-failure.c (ffffffff81239c6b)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff81ff5283)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff81240063)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812408cf)
Location: include/linux/mmzone.h:1124
Inline: True
```
```
In fs/proc/page.c (ffffffff812caa60)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff81529bd5)
Location: include/linux/mmzone.h:1124
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81551cf2)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff815e4705)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/base/memory.c (ffffffff8201798f)
Location: include/linux/mmzone.h:1124
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:show_mem_removable
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
In arch/x86/mm/init_64.c (ffffffff8106c9da)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106eb5a)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/physaddr.c (ffffffff8107446f)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810dcb23)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114ba62)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/memremap.c (ffffffff811b52a4)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
```
```
In mm/page_alloc.c (ffffffff811c52cf)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/vmstat.c (ffffffff811df0d7)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811e8bf9)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff811f8c54)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff81215e55)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff8121f4a9)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:memory_present
  - mm/sparse.c:next_present_section_nr
  - mm/sparse.c:section_mark_present
  - mm/sparse.c:node_memmap_size_bytes
```
```
In mm/sparse-vmemmap.c (ffffffff820d5929)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff8122c828)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8122e50f)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812366e9)
Location: include/linux/mmzone.h:1145
Inline: True
```
```
In mm/memory-failure.c (ffffffff81245933)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff81247014)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff820d7a1a)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff8124bf23)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8124c669)
Location: include/linux/mmzone.h:1145
Inline: True
```
```
In fs/proc/page.c (ffffffff812d7ee3)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153ccb4)
Location: include/linux/mmzone.h:1145
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81566474)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff815f9206)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - drivers/base/node.c:link_mem_sections
```
```
In drivers/base/memory.c (ffffffff820f9756)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:show_mem_removable
```
```
In drivers/edac/edac_mc.c (ffffffff8175c593)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff817a4fa2)
Location: include/linux/mmzone.h:1145
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In arch/x86/mm/init_64.c (ffffffff81071637)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81073c38)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In arch/x86/mm/physaddr.c (ffffffff8107a00f)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810e4d42)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8115831e)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/memremap.c (ffffffff811c8a67)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
```
```
In mm/page_alloc.c (ffffffff811da071)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/vmstat.c (ffffffff811f4d47)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811fefe5)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff81210fac)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff81230a3e)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff8198f038)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:memory_present
  - mm/sparse.c:__section_nr
  - mm/sparse.c:node_memmap_size_bytes
  - mm/sparse.c:present_section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff826de54e)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff8124804a)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8124a761)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812556b4)
Location: include/linux/mmzone.h:1154
Inline: True
```
```
In mm/memory-failure.c (ffffffff812658f9)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff81267185)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff8126ad81)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff8126c2d1)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8126caeb)
Location: include/linux/mmzone.h:1154
Inline: True
```
```
In fs/proc/page.c (ffffffff812fc754)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159f7f6)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_do_proc
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815ca611)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff816612d9)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - drivers/base/node.c:link_mem_sections
```
```
In drivers/base/memory.c (ffffffff82702f63)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:show_mem_removable
```
```
In drivers/edac/edac_mc.c (ffffffff817ce7d6)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8181c143)
Location: include/linux/mmzone.h:1154
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In arch/x86/mm/init_64.c (ffffffff810742ef)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81076688)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In arch/x86/mm/mmap.c (ffffffff8107aca2)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8107cdcf)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810ec9bf)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81166f3e)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff811e8fa2)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/page_alloc.c (ffffffff811fa90e)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/vmstat.c (ffffffff81215ff1)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff812203e1)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff812319b3)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff81252692)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff819eb8f6)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:sparse_early_usemaps_alloc_node
  - mm/sparse.c:memory_present
  - mm/sparse.c:__section_nr
  - mm/sparse.c:present_section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff82708a64)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff8126b99c)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8126dab7)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81279512)
Location: include/linux/mmzone.h:1153
Inline: True
```
```
In mm/memory-failure.c (ffffffff81289cd9)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/page_isolation.c (ffffffff8128ba5c)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff8128f75d)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff81290e71)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8129169f)
Location: include/linux/mmzone.h:1153
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81328b8b)
Location: include/linux/mmzone.h:1153
Inline: True
```
```
In fs/proc/page.c (ffffffff8132a359)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d744b)
Location: include/linux/mmzone.h:1153
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81602e1c)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff8169cab3)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - drivers/base/node.c:link_mem_sections
```
```
In drivers/base/memory.c (ffffffff8272ccee)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:show_mem_removable
```
```
In drivers/edac/edac_mc.c (ffffffff81817449)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8186635c)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In arch/x86/mm/init_64.c (ffffffff8107a1df)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8107ccd8)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In arch/x86/mm/mmap.c (ffffffff810815e2)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810837df)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810f805f)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81173c9e)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff811f9cb2)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/page_alloc.c (ffffffff8120d08e)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/vmstat.c (ffffffff81228ef1)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81233361)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff81245193)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff812668f2)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81a26b8c)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:__section_nr
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff81280fdc)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812820bd)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8128db95)
Location: include/linux/mmzone.h:1161
Inline: True
```
```
In mm/memory-failure.c (ffffffff8129ec49)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/page_isolation.c (ffffffff812a09bc)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff812a467d)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812a5e91)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812a66bf)
Location: include/linux/mmzone.h:1161
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8133f9cb)
Location: include/linux/mmzone.h:1161
Inline: True
```
```
In fs/proc/page.c (ffffffff81341669)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f0bcb)
Location: include/linux/mmzone.h:1161
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161df4c)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff816bc74c)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff828e5670)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:removable_show
```
```
In drivers/edac/edac_mc.c (ffffffff81842ce9)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff81885f2c)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In arch/x86/mm/init_64.c (ffffffff8107de6d)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81080934)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff8108525c)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087454)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81100656)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81180a78)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81211bf1)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffff81238bcd)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81244edb)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff8125713f)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8127347b)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/shuffle.c (ffffffff81a957ee)
Location: include/linux/mmzone.h:1228
Inline: True
```
```
In mm/hugetlb.c (ffffffff81281b9b)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81a9730a)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:__section_nr
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff81a92210)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8129e1c3)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a8524)
Location: include/linux/mmzone.h:1228
Inline: True
```
```
In mm/memory-failure.c (ffffffff812ba313)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/page_isolation.c (ffffffff812bbc4d)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff812bfa9d)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812c15d1)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812c1db0)
Location: include/linux/mmzone.h:1228
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81367cb8)
Location: include/linux/mmzone.h:1228
Inline: True
```
```
In fs/proc/page.c (ffffffff81369a59)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff816229c8)
Location: include/linux/mmzone.h:1228
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81650f88)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff816f6f97)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816f867c)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:removable_show
```
```
In drivers/edac/edac_mc.c (ffffffff81885ab9)
Location: include/linux/mmzone.h:1228
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818d04dc)
Location: include/linux/mmzone.h:1228
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
In arch/x86/mm/init_64.c (ffffffff8107eefd)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81081604)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81085f4c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81088144)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8110cab6)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8118c8e8)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8121f3e1)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffff81246ebd)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8125339b)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff812656cf)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff812822eb)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/shuffle.c (ffffffff81acd0d1)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/hugetlb.c (ffffffff812915c6)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81acebec)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:__section_nr
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff81ac99a0)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812ada73)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b9a04)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/memory-failure.c (ffffffff812cba43)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812cdb2d)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff812d19ed)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812d3501)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812d3ce0)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8137ff38)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In fs/proc/page.c (ffffffff81381cc1)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff81644498)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81673528)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff8171b3a3)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff8171cadc)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d30f8)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818b7a59)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff819028cc)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct mem_section *__nr_to_section(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8108582a)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8108855d)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810896b3)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a5ea)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81117d48)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:mark_nosave_pages
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811a12b3)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8124b656)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmstat.c (ffffffff81274727)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff812822dd)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff81295814)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/page_alloc.c (ffffffff812b4409)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/shuffle.c (ffffffff81bc5a9f)
Location: include/linux/mmzone.h:1212
Inline: True
```
```
In mm/hugetlb.c (ffffffff812c3cf8)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
```
In mm/sparse.c (ffffffff812d137d)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:clear_subsection_map
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:__section_nr
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_activate
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:next_present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff812e08f9)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:scan_movable_pages
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
Direct callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_section
```
```
In mm/migrate.c (ffffffff812e2553)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/huge_memory.c (ffffffff812ee548)
Location: include/linux/mmzone.h:1212
Inline: True
```
```
In mm/memory-failure.c (ffffffff81302851)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff81303dc4)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/page_idle.c (ffffffff813091eb)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff813097be)
Location: include/linux/mmzone.h:1212
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813ca6ce)
Location: include/linux/mmzone.h:1212
Inline: True
```
```
In fs/proc/page.c (ffffffff813cc2b1)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0f66)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817237c3)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff817d7462)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff817d956f)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - drivers/base/memory.c:add_memory_block
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e01f)
Location: include/linux/mmzone.h:1212
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81987cf6)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff819d9842)
Location: include/linux/mmzone.h:1212
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff8111811a-ffffffff81118142: __nr_to_section (STB_LOCAL)
ffffffff812d1230-ffffffff812d1258: __nr_to_section (STB_LOCAL)
ffffffff812e0260-ffffffff812e0288: __nr_to_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct mem_section *__nr_to_section(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810868da)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8108879d)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff81089893)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a88a)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81114188)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:mark_nosave_pages
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/dma/mapping.c (ffffffff81137628)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_map_resource
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e403)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81255a46)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmstat.c (ffffffff8127ef7a)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8128c424)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff812a0bf9)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
```
```
In mm/vmalloc.c (ffffffff812b220e)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/page_alloc.c (ffffffff812c0272)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/shuffle.c (ffffffff81c3ea85)
Location: include/linux/mmzone.h:1250
Inline: True
```
```
In mm/hugetlb.c (ffffffff812cf3ab)
Location: include/linux/mmzone.h:1250
Inline: True
```
```
In mm/sparse.c (ffffffff812dce9d)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:clear_subsection_map
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:__section_nr
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_activate
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:next_present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff812eb973)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:scan_movable_pages
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
Direct callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_section
```
```
In mm/migrate.c (ffffffff812ed983)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/huge_memory.c (ffffffff812f9bbb)
Location: include/linux/mmzone.h:1250
Inline: True
```
```
In mm/memory-failure.c (ffffffff8130eaef)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff8130fc94)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/page_idle.c (ffffffff8131504f)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff813155ce)
Location: include/linux/mmzone.h:1250
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813dc38e)
Location: include/linux/mmzone.h:1250
Inline: True
```
```
In fs/proc/page.c (ffffffff813ddeee)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e146)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81740503)
Location: include/linux/mmzone.h:1250
Inline: True
```
```
In drivers/base/node.c (ffffffff817ebed9)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff8300d30a)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ace5f)
Location: include/linux/mmzone.h:1250
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8198bc26)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff819d8ba0)
Location: include/linux/mmzone.h:1250
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81bdf553-ffffffff81bdf57b: __nr_to_section (STB_LOCAL)
ffffffff812dcd50-ffffffff812dcd78: __nr_to_section (STB_LOCAL)
ffffffff812eb200-ffffffff812eb228: __nr_to_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct mem_section *__nr_to_section(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086769)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810893a9)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:pfn_valid
```
```
In arch/x86/mm/mmap.c (ffffffff8108a0a9)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_valid
```
```
In arch/x86/mm/physaddr.c (ffffffff8108b479)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:pfn_valid
```
```
In kernel/power/snapshot.c (ffffffff81112b39)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - kernel/power/snapshot.c:pfn_valid
```
```
In kernel/dma/mapping.c (ffffffff81138399)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - kernel/dma/mapping.c:pfn_valid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119efe9)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:pfn_valid
```
```
In kernel/iomem.c (ffffffff81259fe9)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - kernel/iomem.c:pfn_valid
```
```
In mm/compaction.c (ffffffff812912e0)
Location: include/linux/mmzone.h:1314
Inline: True
```
```
In mm/memory.c (ffffffff8129c4a9)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - mm/memory.c:pfn_valid
```
```
In mm/vmalloc.c (ffffffff812b7889)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - mm/vmalloc.c:pfn_valid
```
```
In mm/page_alloc.c (ffffffff812c59ec)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
  - mm/page_alloc.c:pfn_valid
```
```
In mm/memory_hotplug.c (ffffffff812c7579)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:pfn_to_online_page
  - mm/memory_hotplug.c:pfn_valid
Direct callers:
  - mm/memory_hotplug.c:section_taint_zone_device
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/hugetlb.c (ffffffff812d603b)
Location: include/linux/mmzone.h:1314
Inline: True
```
```
In mm/sparse.c (ffffffff812e4656)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:__section_nr
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:next_present_section_nr
```
```
In mm/migrate.c (ffffffff812f2e09)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - mm/migrate.c:pfn_valid
```
```
In mm/huge_memory.c (ffffffff81300340)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff81312959)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - mm/memory-failure.c:pfn_valid
```
```
In fs/proc/kcore.c (ffffffff813e2c99)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - fs/proc/kcore.c:pfn_valid
```
```
In drivers/acpi/apei/ghes.c (ffffffff816ef869)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:pfn_valid
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723cc9)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:pfn_valid
```
```
In drivers/base/node.c (ffffffff817d06f9)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff83218165)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8188f949)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:pfn_valid
```
```
In drivers/edac/edac_mc.c (ffffffff81970329)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:pfn_valid
```
```
In drivers/ras/cec.c (ffffffff819be959)
Location: include/linux/mmzone.h:1314
Inline: True
Inline callers:
  - drivers/ras/cec.c:pfn_valid
```
**Symbols:**

```
ffffffff812c5ee0-ffffffff812c5f08: __nr_to_section (STB_LOCAL)
ffffffff812e45c0-ffffffff812e45e8: __nr_to_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct mem_section *__nr_to_section(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81095a4f)
Location: include/linux/mmzone.h:1352
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81098837)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:pfn_valid
```
```
In arch/x86/mm/mmap.c (ffffffff810995e7)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_valid
```
```
In arch/x86/mm/physaddr.c (ffffffff8109aa26)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:pfn_valid
```
```
In kernel/power/snapshot.c (ffffffff81132d6f)
Location: include/linux/mmzone.h:1352
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff8115b1f6)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - kernel/dma/mapping.c:pfn_valid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c8e76)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:pfn_valid
```
```
In kernel/iomem.c (ffffffff81295db6)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - kernel/iomem.c:pfn_valid
```
```
In mm/compaction.c (ffffffff812d0ef7)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - mm/compaction.c:pfn_valid
```
```
In mm/memory.c (ffffffff812dd1bf)
Location: include/linux/mmzone.h:1352
Inline: True
```
```
In mm/vmalloc.c (ffffffff812f9fb7)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - mm/vmalloc.c:pfn_valid
```
```
In mm/page_alloc.c (ffffffff8130a107)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff8130c300)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:pfn_to_online_page
Direct callers:
  - mm/memory_hotplug.c:section_taint_zone_device
```
```
In mm/hugetlb.c (ffffffff8131bb07)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - mm/hugetlb.c:pfn_valid
```
```
In mm/sparse.c (ffffffff8132b966)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:next_present_section_nr
```
```
In mm/huge_memory.c (ffffffff81349fa8)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff8135e58f)
Location: include/linux/mmzone.h:1352
Inline: True
```
```
In mm/bootmem_info.c (ffffffff81cc378a)
Location: include/linux/mmzone.h:1352
Inline: False
Direct callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff814347c7)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - fs/proc/kcore.c:pfn_valid
```
```
In drivers/acpi/apei/ghes.c (ffffffff817698d6)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:pfn_valid
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2c4f)
Location: include/linux/mmzone.h:1352
Inline: True
```
```
In drivers/base/node.c (ffffffff8185b08f)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff83301baa)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923267)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:pfn_valid
```
```
In drivers/edac/edac_mc.c (ffffffff81a18c47)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:pfn_valid
```
```
In drivers/ras/cec.c (ffffffff81a6def6)
Location: include/linux/mmzone.h:1352
Inline: True
Inline callers:
  - drivers/ras/cec.c:pfn_valid
```
**Symbols:**

```
ffffffff8130a7f0-ffffffff8130a818: __nr_to_section (STB_LOCAL)
ffffffff8132b8d0-ffffffff8132b8f8: __nr_to_section (STB_LOCAL)
ffffffff81cc378a-ffffffff81cc37b2: __nr_to_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct mem_section *__nr_to_section(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810a92ae)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810ab4f5)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810aca7e)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810add82)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81156dd3)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fca80)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812ebb24)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff8132fd26)
Location: include/linux/mmzone.h:1395
Inline: True
```
```
In mm/memory.c (ffffffff81348bed)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
```
```
In mm/vmalloc.c (ffffffff81360308)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff81372d90)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff81f1ba4b)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:pfn_to_online_page
Direct callers:
  - mm/memory_hotplug.c:section_taint_zone_device
```
```
In mm/hugetlb.c (ffffffff813881ce)
Location: include/linux/mmzone.h:1395
Inline: True
```
```
In mm/sparse.c (ffffffff8139b59d)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:online_mem_sections
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:next_present_section_nr
```
```
In mm/huge_memory.c (ffffffff813c09d5)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff813dd1a1)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff81e75ea4)
Location: include/linux/mmzone.h:1395
Inline: False
Direct callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff814aed9f)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e59c)
Location: include/linux/mmzone.h:1395
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd0f4)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff819a1fe9)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff834bab6d)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - drivers/base/memory.c:add_boot_memory_block
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a794c5)
Location: include/linux/mmzone.h:1395
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81b81f77)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81bdf13d)
Location: include/linux/mmzone.h:1395
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81373440-ffffffff81373491: __nr_to_section (STB_LOCAL)
ffffffff8139b4c0-ffffffff8139b511: __nr_to_section (STB_LOCAL)
ffffffff81e75ea4-ffffffff81e75f03: __nr_to_section (STB_LOCAL)
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
In arch/x86/mm/ioremap.c (ffffffff810c5935)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810c6b57)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810c7fc9)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81187aa9)
Location: include/linux/mmzone.h:1711
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
In kernel/debug/kdb/kdb_support.c (ffffffff812441a0)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81355d64)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff81378296)
Location: include/linux/mmzone.h:1711
Inline: True
```
```
In mm/compaction.c (ffffffff813a68cf)
Location: include/linux/mmzone.h:1711
Inline: True
```
```
In mm/memory.c (ffffffff813bd942)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/vmalloc.c (ffffffff813dc407)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff813f0510)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff820c3a42)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/sparse.c (ffffffff820cab9a)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory-failure.c (ffffffff81463fec)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff83ec860c)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff8154544f)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7a9c)
Location: include/linux/mmzone.h:1711
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30540)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff81b13f59)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff83ef8485)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - drivers/base/memory.c:add_boot_memory_block
```
```
In drivers/edac/edac_mc.c (ffffffff81d208a9)
Location: include/linux/mmzone.h:1711
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81d8a713)
Location: include/linux/mmzone.h:1711
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
In arch/x86/mm/ioremap.c (ffffffff810c90bc)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810ca2d9)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810cb705)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81198c39)
Location: include/linux/mmzone.h:1836
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
In kernel/debug/kdb/kdb_support.c (ffffffff8125b280)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff813873f4)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813abae6)
Location: include/linux/mmzone.h:1836
Inline: True
```
```
In mm/mm_init.c (ffffffff836e04ef)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff813dba50)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff813f2642)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/vmalloc.c (ffffffff81410d10)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff814240a0)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff821477bc)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/sparse.c (ffffffff8144efcf)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory-failure.c (ffffffff81499aa4)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff836ed66b)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff8157d02f)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a301ac)
Location: include/linux/mmzone.h:1836
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79d4f)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff81b62c89)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff8371e025)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - drivers/base/memory.c:add_boot_memory_block
```
```
In drivers/edac/edac_mc.c (ffffffff81d89aa6)
Location: include/linux/mmzone.h:1836
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81df8d13)
Location: include/linux/mmzone.h:1836
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
In arch/x86/mm/ioremap.c (ffffffff810d0d89)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810d2741)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810d3d64)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff811a7a90)
Location: include/linux/mmzone.h:1847
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
In kernel/debug/kdb/kdb_support.c (ffffffff81275150)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff813b0d77)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813d6206)
Location: include/linux/mmzone.h:1847
Inline: True
```
```
In mm/mm_init.c (ffffffff83912d3d)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff814059b0)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8141d342)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/vmalloc.c (ffffffff8143ef2a)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff81449b57)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff8222a04c)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/sparse.c (ffffffff81488b8f)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory-failure.c (ffffffff814c91fa)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff83920673)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff815b597f)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b30c)
Location: include/linux/mmzone.h:1847
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc1b5)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff81bb6799)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff839519f5)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - drivers/base/memory.c:add_boot_memory_block
```
```
In drivers/edac/edac_mc.c (ffffffff81e410ec)
Location: include/linux/mmzone.h:1847
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81eaf3a3)
Location: include/linux/mmzone.h:1847
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/init.c (ffff8000100ad694)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/arm64/mm/init.c:pfn_valid
```
```
In mm/vmstat.c (ffff8000102da25c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffff8000102e99dc)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffff8000103150b8)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/shuffle.c (ffff800010da00f4)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/hugetlb.c (ffff80001032e790)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
```
```
In mm/sparse.c (ffff800010da07b4)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:__section_nr
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffff800010d9ce8c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
```
In mm/memory-failure.c (ffff80001036f36c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffff800010371f90)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (ffff80001044faa4)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/node.c (ffff80001090ece8)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffff8000109107e4)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_block_action
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
In arch/powerpc/kernel/stacktrace.c (c00000000006913c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/powerpc/kernel/stacktrace.c:pfn_valid
```
```
In arch/powerpc/mm/pgtable.c (c000000000087858)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:maybe_pte_to_page
```
```
In arch/powerpc/mm/init_64.c (c000000000eeb13c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/powerpc/mm/init_64.c:vmemmap_populated
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008cf40)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_do_lazy_icache
```
```
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fade8)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock
```
```
In kernel/debug/kdb/kdb_support.c (c00000000027e430)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/events/core.c (c000000000350a58)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/iomem.c (c00000000035fad8)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (c00000000039aabc)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (c0000000003ad8fc)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (c0000000003c788c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (c0000000003edec0)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/shuffle.c (c000000000eecd30)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/hugetlb.c (c0000000004077c0)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (c000000000eed6c4)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:__section_nr
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (c000000000430968)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (c0000000004324bc)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (c000000000443b9c)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/memory-failure.c (c000000000460920)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (c000000000463874)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (c000000000469a48)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (c00000000046bf68)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c00000000046cf70)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/usercopy.c (c00000000046d3f4)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In fs/proc/kcore.c (c000000000565500)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In fs/proc/page.c (c000000000567e2c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/node.c (c0000000009af7e0)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (c0000000009b1608)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/spi/spi.c (c000000000a89f0c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/edac/edac_mc.c (c000000000c0333c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5b5e8)
Location: include/linux/mmzone.h:1235
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
In kernel/events/core.c (ffffffe0001cefd6)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/iomem.c (ffffffe0001d3644)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffe0001f454c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffe0001ff0e8)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffe00020b6c2)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/page_alloc.c (ffffffe00021bb3a)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/shuffle.c (ffffffe00004748a)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/hugetlb.c (ffffffe00022c7b8)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffe000018832)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:__section_nr
  - mm/sparse.c:present_section_nr
```
```
In mm/migrate.c (ffffffe00023e90e)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/page_isolation.c (ffffffe00024b2fe)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffe00024f4b4)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffe000250902)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffe000250f46)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/usercopy.c (ffffffe00025123a)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In fs/proc/kcore.c (ffffffe0002e250a)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In fs/proc/page.c (ffffffe0002e3092)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/spi/spi.c (ffffffe000618b3a)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/edac/edac_mc.c (ffffffe0006fcf20)
Location: include/linux/mmzone.h:1235
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
In arch/x86/mm/init_64.c (ffffffff8107defd)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81080604)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81084f4c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087144)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81104cd6)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81184f08)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81217a31)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffff8123f50d)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8124b9eb)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff8125dd1f)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8127a93b)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/shuffle.c (ffffffff81a6bf41)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/hugetlb.c (ffffffff81289ba6)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81a6da5c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:__section_nr
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff81a68810)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a6053)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b1fe4)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c4023)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812c610d)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff812c9fcd)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812cbae1)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812cc2c0)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81378518)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In fs/proc/page.c (ffffffff8137a2a1)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81639218)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff816e16d3)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816e2e0c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/edac/edac_mc.c (ffffffff8185d8d9)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818a1cfc)
Location: include/linux/mmzone.h:1235
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
In arch/x86/mm/init_64.c (ffffffff8106d1a9)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106f554)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81073c1c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81075d14)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810f5f76)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81178048)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8120ac41)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffff8123250d)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8123e98b)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff8125016f)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8126c81b)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/shuffle.c (ffffffff81a28488)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/hugetlb.c (ffffffff8127b9d6)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81a29fa3)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:__section_nr
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff81a252d0)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81297b03)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a3374)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/memory-failure.c (ffffffff812b5063)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812b714d)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff812bb00d)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812bc961)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812bd130)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81368fe8)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In fs/proc/page.c (ffffffff8136ad71)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/node.c (ffffffff816bbd13)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816bd44c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d1a8)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81824ea9)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8185d46c)
Location: include/linux/mmzone.h:1235
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
In arch/x86/mm/init_64.c (ffffffff8107dead)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810805b4)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81084efc)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810870f4)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81102f86)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81182cd8)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812157d1)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffff8123d2ad)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8124978b)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff8125babf)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff812786db)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/shuffle.c (ffffffff81ad8351)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/hugetlb.c (ffffffff812879b6)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81ad9e6c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:__section_nr
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff81ad4c20)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a3e63)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812afdf4)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c1e33)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812c3f1d)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff812c7ddd)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812c98f1)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812ca0d0)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81375fe8)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In fs/proc/page.c (ffffffff81377d71)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff816382d8)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81667368)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff8170ec03)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff8170ff9c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c7f78)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818acf09)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818f32ec)
Location: include/linux/mmzone.h:1235
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
In arch/x86/mm/init_64.c (ffffffff8107ff9d)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810826d4)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff8108704c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81089224)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8110e376)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811905f8)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812247d1)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffff8124c9dd)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8125900b)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff8126b4a6)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff812882cb)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/shuffle.c (ffffffff81ae480c)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/hugetlb.c (ffffffff81297f53)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81ae6322)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:__section_nr
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff81ae10fb)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812b4732)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812c0134)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In mm/memory-failure.c (ffffffff812d28d3)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812d49bd)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff812d8aed)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812da5f1)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812dadd0)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81389a98)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In fs/proc/page.c (ffffffff8138b81b)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652618)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81681928)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff817299c3)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff8172b0fc)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2218)
Location: include/linux/mmzone.h:1235
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818c9159)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8191438c)
Location: include/linux/mmzone.h:1235
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
