# Function: <code>valid_section</code>

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
In arch/x86/mm/init_64.c (ffffffff81069949)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106b92f)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/physaddr.c (ffffffff81071466)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810d0717)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811379dd)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In mm/page_alloc.c (ffffffff8181ce5d)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/vmstat.c (ffffffff811acff3)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811b4bf2)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - mm/compaction.c:pageblock_pfn_to_page
  - mm/compaction.c:pageblock_pfn_to_page
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff811c1c97)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_pfn
  - mm/memory.c:clear_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
```
```
In mm/hugetlb.c (ffffffff811daa56)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/memory_hotplug.c (ffffffff811ef1c0)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff811f1f87)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff811f5c46)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/memory-failure.c (ffffffff81201b56)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff81f8e343)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff81208117)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812089bf)
Location: include/linux/mmzone.h:1111
Inline: True
```
```
In fs/proc/page.c (ffffffff81287ea8)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpageflags_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b606d)
Location: include/linux/mmzone.h:1111
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d488d)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff81560f71)
Location: include/linux/mmzone.h:1111
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:store_soft_offline_page
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
In arch/x86/mm/init_64.c (ffffffff810696c5)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106b80f)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/physaddr.c (ffffffff81071357)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810d6ecd)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8113fea5)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/memremap.c (ffffffff8119e47a)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
```
```
In mm/page_alloc.c (ffffffff811acad9)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/vmstat.c (ffffffff811c6289)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811cee6d)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff811ddf7d)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff811fa0ed)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/memory_hotplug.c (ffffffff8120e6e2)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81210a0b)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812185b8)
Location: include/linux/mmzone.h:1183
Inline: True
```
```
In mm/memory-failure.c (ffffffff812276f6)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff81fb8937)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff8122db40)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8122e3bd)
Location: include/linux/mmzone.h:1183
Inline: True
```
```
In fs/proc/page.c (ffffffff812b51f8)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff815059f3)
Location: include/linux/mmzone.h:1183
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8152584a)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff815b5cbd)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_block_action
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
In arch/x86/mm/init_64.c (ffffffff8106d2a5)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106f429)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/physaddr.c (ffffffff81074ed7)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810dda4d)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81149c79)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/memremap.c (ffffffff811adeaa)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
```
```
In mm/page_alloc.c (ffffffff811bd09b)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/vmstat.c (ffffffff811d63c2)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811def84)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff811edd92)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff8120abb8)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/memory_hotplug.c (ffffffff81220722)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81222b5d)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8122ab43)
Location: include/linux/mmzone.h:1161
Inline: True
```
```
In mm/memory-failure.c (ffffffff81239c86)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff81ff529e)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff81240082)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812408ed)
Location: include/linux/mmzone.h:1161
Inline: True
```
```
In fs/proc/page.c (ffffffff812caa7b)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff81529bf0)
Location: include/linux/mmzone.h:1161
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81551d0a)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff815e4fd9)
Location: include/linux/mmzone.h:1161
Inline: True
Inline callers:
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_block_action
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
In arch/x86/mm/init_64.c (ffffffff8106c8e9)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106eb75)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/physaddr.c (ffffffff81074487)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810dcb42)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114ba81)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/memremap.c (ffffffff811b52bf)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
```
```
In mm/page_alloc.c (ffffffff811c52ea)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory.c (ffffffff811f8c70)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff81215e7b)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff8121f412)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory_hotplug.c (ffffffff8122cb6f)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8122e52b)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81236704)
Location: include/linux/mmzone.h:1183
Inline: True
```
```
In mm/memory-failure.c (ffffffff81245952)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff820d7a35)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff8124bf42)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8124c684)
Location: include/linux/mmzone.h:1183
Inline: True
```
```
In fs/proc/page.c (ffffffff812d7efe)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153cccf)
Location: include/linux/mmzone.h:1183
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81566490)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff815f9ac4)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/edac/edac_mc.c (ffffffff8175c5ae)
Location: include/linux/mmzone.h:1183
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff817a4fba)
Location: include/linux/mmzone.h:1183
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
In arch/x86/mm/init_64.c (ffffffff81071479)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81073c85)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In arch/x86/mm/physaddr.c (ffffffff8107a02f)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810e4d95)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81158349)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/memremap.c (ffffffff811c8a8a)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
```
```
In mm/page_alloc.c (ffffffff811da0b5)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory.c (ffffffff81210fd6)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff81230a61)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff8123a63b)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory_hotplug.c (ffffffff81989b8d)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff8124a78b)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812556d7)
Location: include/linux/mmzone.h:1196
Inline: True
```
```
In mm/memory-failure.c (ffffffff81265920)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff8126ad6f)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff8126c2fc)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8126cb14)
Location: include/linux/mmzone.h:1196
Inline: True
```
```
In fs/proc/page.c (ffffffff812fc777)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159f81a)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_do_proc
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815ca639)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff816619c3)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/edac/edac_mc.c (ffffffff817ce7fd)
Location: include/linux/mmzone.h:1196
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8181c163)
Location: include/linux/mmzone.h:1196
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
In arch/x86/mm/init_64.c (ffffffff81074310)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8107669d)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In arch/x86/mm/mmap.c (ffffffff8107acbe)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8107cde8)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810ec9e5)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81166f5e)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff811e8fbe)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/page_alloc.c (ffffffff811fa92b)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory.c (ffffffff812319d7)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff812526b6)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff8125dc01)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory_hotplug.c (ffffffff819e658c)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff8126dad3)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8127952e)
Location: include/linux/mmzone.h:1203
Inline: True
```
```
In mm/memory-failure.c (ffffffff81289cfd)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/cma.c (ffffffff8128f776)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff81290e95)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812916c1)
Location: include/linux/mmzone.h:1203
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81328baf)
Location: include/linux/mmzone.h:1203
Inline: True
```
```
In fs/proc/page.c (ffffffff8132a375)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d7467)
Location: include/linux/mmzone.h:1203
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81602e46)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff8169d3dc)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/edac/edac_mc.c (ffffffff81817465)
Location: include/linux/mmzone.h:1203
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff81866375)
Location: include/linux/mmzone.h:1203
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
In arch/x86/mm/init_64.c (ffffffff8107a200)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8107cced)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In arch/x86/mm/mmap.c (ffffffff810815fe)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810837f8)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810f8085)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81173cbe)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff811f9cce)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/page_alloc.c (ffffffff8120d0ab)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory.c (ffffffff812451b4)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff81266916)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81272491)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory_hotplug.c (ffffffff81a218f4)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
```
```
In mm/migrate.c (ffffffff812820de)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8128dbb1)
Location: include/linux/mmzone.h:1211
Inline: True
```
```
In mm/memory-failure.c (ffffffff8129ec6d)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/cma.c (ffffffff812a4696)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812a5eb5)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812a66e1)
Location: include/linux/mmzone.h:1211
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8133f9ef)
Location: include/linux/mmzone.h:1211
Inline: True
```
```
In fs/proc/page.c (ffffffff81341685)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f0be7)
Location: include/linux/mmzone.h:1211
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161df76)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff816bd77c)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/edac/edac_mc.c (ffffffff81842d05)
Location: include/linux/mmzone.h:1211
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff81885f45)
Location: include/linux/mmzone.h:1211
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
In arch/x86/mm/init_64.c (ffffffff8107de91)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81080950)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81085278)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087470)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8110067a)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81180a9c)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81211c0d)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff81244f00)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff81257166)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8127349f)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81281bb7)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff8128dcb6)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory_hotplug.c (ffffffff81a92234)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
```
```
In mm/migrate.c (ffffffff8129e1e7)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a8540)
Location: include/linux/mmzone.h:1279
Inline: True
```
```
In mm/memory-failure.c (ffffffff812ba33a)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/cma.c (ffffffff812bfabb)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812c15f5)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812c1dcc)
Location: include/linux/mmzone.h:1279
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81367cdc)
Location: include/linux/mmzone.h:1279
Inline: True
```
```
In fs/proc/page.c (ffffffff81369a75)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff816229ec)
Location: include/linux/mmzone.h:1279
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81650fac)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff816f8698)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/edac/edac_mc.c (ffffffff81885add)
Location: include/linux/mmzone.h:1279
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818d0500)
Location: include/linux/mmzone.h:1279
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
In arch/x86/mm/init_64.c (ffffffff8107ef21)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81081620)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81085f68)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81088160)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8110cada)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8118c90c)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8121f3fd)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff812533c0)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff812656f6)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8128230f)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81290b87)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff8129d9b1)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory_hotplug.c (ffffffff81ac99c4)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812ada97)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b9a20)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In mm/memory-failure.c (ffffffff812cba6a)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812d1a0b)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812d3525)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812d3cfc)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8137ff5c)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff816444bc)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8167354c)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff8171ca78)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3114)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818b7a7d)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff819028f0)
Location: include/linux/mmzone.h:1286
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
In arch/x86/mm/init_64.c (ffffffff8108584e)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81088579)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810896cf)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a606)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81117d6c)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:mark_nosave_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811a12d7)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8124b672)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff81282302)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff81295830)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/page_alloc.c (ffffffff812b442d)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff812c3d14)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
```
In mm/sparse.c (ffffffff812d1651)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory_hotplug.c (ffffffff812e0d9e)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
  - mm/memory_hotplug.c:__remove_pages
```
```
In mm/migrate.c (ffffffff812e256f)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/huge_memory.c (ffffffff812ee56c)
Location: include/linux/mmzone.h:1263
Inline: True
```
```
In mm/memory-failure.c (ffffffff81302825)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/frame_vector.c (ffffffff813097da)
Location: include/linux/mmzone.h:1263
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813ca6ea)
Location: include/linux/mmzone.h:1263
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0f82)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817237e7)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e03b)
Location: include/linux/mmzone.h:1263
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81987d16)
Location: include/linux/mmzone.h:1263
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff819d9866)
Location: include/linux/mmzone.h:1263
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
In arch/x86/mm/init_64.c (ffffffff81086905)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810887c0)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810898b6)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a8ad)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff811141b3)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:mark_nosave_pages
```
```
In kernel/dma/mapping.c (ffffffff8113764b)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_map_resource
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e42e)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81255a69)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff8128c450)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff812a0c1c)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
```
```
In mm/vmalloc.c (ffffffff812b2231)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/page_alloc.c (ffffffff812bccf1)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff812cf3ce)
Location: include/linux/mmzone.h:1301
Inline: True
```
```
In mm/sparse.c (ffffffff812dd178)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory_hotplug.c (ffffffff812ebba5)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
  - mm/memory_hotplug.c:__remove_pages
```
```
In mm/migrate.c (ffffffff812ed9a7)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/huge_memory.c (ffffffff812f9be6)
Location: include/linux/mmzone.h:1301
Inline: True
```
```
In mm/memory-failure.c (ffffffff8130eb1a)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/frame_vector.c (ffffffff813155f1)
Location: include/linux/mmzone.h:1301
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813dc3b1)
Location: include/linux/mmzone.h:1301
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e169)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8174052f)
Location: include/linux/mmzone.h:1301
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ace82)
Location: include/linux/mmzone.h:1301
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8198bc4d)
Location: include/linux/mmzone.h:1301
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff819d8bcb)
Location: include/linux/mmzone.h:1301
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
In arch/x86/mm/init_64.c (ffffffff8108678c)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810893cc)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:pfn_valid
```
```
In arch/x86/mm/mmap.c (ffffffff8108a0cc)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_valid
```
```
In arch/x86/mm/physaddr.c (ffffffff8108b49c)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:pfn_valid
```
```
In kernel/power/snapshot.c (ffffffff81112b5c)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - kernel/power/snapshot.c:pfn_valid
```
```
In kernel/dma/mapping.c (ffffffff811383bc)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - kernel/dma/mapping.c:pfn_valid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119f00c)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:pfn_valid
```
```
In kernel/iomem.c (ffffffff8125a00c)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - kernel/iomem.c:pfn_valid
```
```
In mm/compaction.c (ffffffff8129130c)
Location: include/linux/mmzone.h:1366
Inline: True
```
```
In mm/memory.c (ffffffff8129c4cc)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - mm/memory.c:pfn_valid
```
```
In mm/vmalloc.c (ffffffff812b78ac)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - mm/vmalloc.c:pfn_valid
```
```
In mm/page_alloc.c (ffffffff812bf2cc)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - mm/page_alloc.c:pfn_valid
```
```
In mm/memory_hotplug.c (ffffffff812c6f10)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:pfn_valid
```
```
In mm/hugetlb.c (ffffffff812d605e)
Location: include/linux/mmzone.h:1366
Inline: True
```
```
In mm/sparse.c (ffffffff812e49c8)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/migrate.c (ffffffff812f2e2c)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - mm/migrate.c:pfn_valid
```
```
In mm/huge_memory.c (ffffffff8130036b)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff8131297c)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - mm/memory-failure.c:pfn_valid
```
```
In fs/proc/kcore.c (ffffffff813e2cbc)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - fs/proc/kcore.c:pfn_valid
```
```
In drivers/acpi/apei/ghes.c (ffffffff816ef88c)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:pfn_valid
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723cec)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:pfn_valid
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8188f96c)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:pfn_valid
```
```
In drivers/edac/edac_mc.c (ffffffff8197034c)
Location: include/linux/mmzone.h:1366
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:pfn_valid
```
```
In drivers/ras/cec.c (ffffffff819be97c)
Location: include/linux/mmzone.h:1366
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
In arch/x86/mm/init_64.c (ffffffff81095a72)
Location: include/linux/mmzone.h:1403
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff8109885a)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:pfn_valid
```
```
In arch/x86/mm/mmap.c (ffffffff8109960a)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_valid
```
```
In arch/x86/mm/physaddr.c (ffffffff8109aa49)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:pfn_valid
```
```
In kernel/power/snapshot.c (ffffffff81132d92)
Location: include/linux/mmzone.h:1403
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff8115b219)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - kernel/dma/mapping.c:pfn_valid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c8e99)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:pfn_valid
```
```
In kernel/iomem.c (ffffffff81295dd9)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - kernel/iomem.c:pfn_valid
```
```
In mm/compaction.c (ffffffff812d0f1a)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - mm/compaction.c:pfn_valid
```
```
In mm/memory.c (ffffffff812dd1e2)
Location: include/linux/mmzone.h:1403
Inline: True
```
```
In mm/vmalloc.c (ffffffff812f9fda)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - mm/vmalloc.c:pfn_valid
```
```
In mm/page_alloc.c (ffffffff81301c12)
Location: include/linux/mmzone.h:1403
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8130b960)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
```
```
In mm/hugetlb.c (ffffffff8131bb2a)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - mm/hugetlb.c:pfn_valid
```
```
In mm/sparse.c (ffffffff8132bc48)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/huge_memory.c (ffffffff81349fd3)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff8135e5b2)
Location: include/linux/mmzone.h:1403
Inline: True
```
```
In mm/bootmem_info.c (ffffffff832de804)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff814347ea)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - fs/proc/kcore.c:pfn_valid
```
```
In drivers/acpi/apei/ghes.c (ffffffff817698f9)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:pfn_valid
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2c72)
Location: include/linux/mmzone.h:1403
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8192328a)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:pfn_valid
```
```
In drivers/edac/edac_mc.c (ffffffff81a18c6a)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:pfn_valid
```
```
In drivers/ras/cec.c (ffffffff81a6df19)
Location: include/linux/mmzone.h:1403
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
In arch/x86/mm/init_64.c (ffffffff810a938d)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810ab534)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810acab0)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810addb4)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81156e11)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fcab3)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812ebb56)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff8132fd64)
Location: include/linux/mmzone.h:1449
Inline: True
```
```
In mm/memory.c (ffffffff81348c1f)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
```
```
In mm/vmalloc.c (ffffffff8136033c)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff8136d58b)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory_hotplug.c (ffffffff81f1ba89)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:__remove_pages
```
```
In mm/hugetlb.c (ffffffff81388200)
Location: include/linux/mmzone.h:1449
Inline: True
```
```
In mm/sparse.c (ffffffff8139b927)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/huge_memory.c (ffffffff813c0a13)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff813dd1d3)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff834940e7)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff814aedd1)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e5ce)
Location: include/linux/mmzone.h:1449
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd126)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a794f7)
Location: include/linux/mmzone.h:1449
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81b81fb6)
Location: include/linux/mmzone.h:1449
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81bdf17b)
Location: include/linux/mmzone.h:1449
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
In arch/x86/mm/ioremap.c (ffffffff810c596c)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810c6b89)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810c7fff)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81187ae7)
Location: include/linux/mmzone.h:1781
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
In kernel/debug/kdb/kdb_support.c (ffffffff812441db)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81355d9d)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813782c9)
Location: include/linux/mmzone.h:1781
Inline: True
```
```
In mm/compaction.c (ffffffff813a690d)
Location: include/linux/mmzone.h:1781
Inline: True
```
```
In mm/memory.c (ffffffff813bd980)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/vmalloc.c (ffffffff813dc33b)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff83ebe7bf)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory_hotplug.c (ffffffff820c3a78)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:__remove_pages
```
```
In mm/sparse.c (ffffffff8141b9b7)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory-failure.c (ffffffff81463f85)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff83ec863f)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff81545488)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7ad5)
Location: include/linux/mmzone.h:1781
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a305fd)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/edac/edac_mc.c (ffffffff81d207d9)
Location: include/linux/mmzone.h:1781
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81d8a785)
Location: include/linux/mmzone.h:1781
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
In arch/x86/mm/ioremap.c (ffffffff810c90ef)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810ca30b)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810cb737)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81198c77)
Location: include/linux/mmzone.h:1906
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
In kernel/debug/kdb/kdb_support.c (ffffffff8125b2bb)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8138742d)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813abb19)
Location: include/linux/mmzone.h:1906
Inline: True
```
```
In mm/mm_init.c (ffffffff836e052f)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff813da15f)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff813f2680)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/vmalloc.c (ffffffff81410c5b)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff8141c79b)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory_hotplug.c (ffffffff821477f2)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/sparse.c (ffffffff8144efff)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory-failure.c (ffffffff81499a41)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff836ed69e)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff8157d068)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a301e5)
Location: include/linux/mmzone.h:1906
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79e12)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/edac/edac_mc.c (ffffffff81d899b9)
Location: include/linux/mmzone.h:1906
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81df8d85)
Location: include/linux/mmzone.h:1906
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
In arch/x86/mm/ioremap.c (ffffffff810d0dce)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810d277d)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810d3da0)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff811a7ad9)
Location: include/linux/mmzone.h:1917
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
In kernel/debug/kdb/kdb_support.c (ffffffff812751a5)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff813b0dbe)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813d6243)
Location: include/linux/mmzone.h:1917
Inline: True
```
```
In mm/mm_init.c (ffffffff83912d86)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff81403e79)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8141d37e)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/vmalloc.c (ffffffff8143eea6)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff81449209)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory_hotplug.c (ffffffff8222a094)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/sparse.c (ffffffff81488bbf)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory-failure.c (ffffffff814c9249)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff839206bc)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff815b59ce)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b357)
Location: include/linux/mmzone.h:1917
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc282)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/edac/edac_mc.c (ffffffff81e41142)
Location: include/linux/mmzone.h:1917
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81eaf3c4)
Location: include/linux/mmzone.h:1917
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
In arch/arm64/mm/init.c (ffff8000100ad6ac)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/arm64/mm/init.c:pfn_valid
```
```
In mm/sparse.c (ffff80001033cab0)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory_hotplug.c (ffff80001034e234)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
```
```
In drivers/base/memory.c (ffff800010910ba8)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
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
In arch/powerpc/kernel/stacktrace.c (c000000000069164)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/powerpc/kernel/stacktrace.c:pfn_valid
```
```
In arch/powerpc/mm/pgtable.c (c000000000087880)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:maybe_pte_to_page
```
```
In arch/powerpc/mm/init_64.c (c000000000eeb154)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/powerpc/mm/init_64.c:vmemmap_populated
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008cf6c)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_do_lazy_icache
```
```
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fae10)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock
```
```
In kernel/debug/kdb/kdb_support.c (c00000000027e458)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/events/core.c (c000000000350a80)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/iomem.c (c00000000035fb00)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (c0000000003ad924)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (c0000000003c78b4)
Location: include/linux/mmzone.h:1286
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
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (c000000000406c70)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (c000000000417c78)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory_hotplug.c (c000000000430990)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (c0000000004324e4)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (c000000000443bc4)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In mm/memory-failure.c (c000000000460950)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (c000000000469a74)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (c00000000046bf90)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c00000000046cf70)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In mm/usercopy.c (c00000000046d41c)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In fs/proc/kcore.c (c000000000565528)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In drivers/base/memory.c (c0000000009b1630)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/spi/spi.c (c000000000a89f34)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/edac/edac_mc.c (c000000000c03364)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5b610)
Location: include/linux/mmzone.h:1286
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
In kernel/events/core.c (ffffffe0001ceff4)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/iomem.c (ffffffe0001d3662)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffe0001f4586)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffe0001ff106)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffe00020b6ea)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/page_alloc.c (ffffffe00021bb58)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffe00022c7ea)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffe00023e922)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/page_isolation.c (ffffffe00024b31e)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffe00024f4d6)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffe000250920)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffe000250f7c)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In mm/usercopy.c (ffffffe000251258)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In fs/proc/kcore.c (ffffffe0002e2530)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In fs/proc/page.c (ffffffe0002e30c6)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/spi/spi.c (ffffffe000618b58)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/edac/edac_mc.c (ffffffe0006fcf42)
Location: include/linux/mmzone.h:1286
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
In arch/x86/mm/init_64.c (ffffffff8107df21)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81080620)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81084f68)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087160)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81104cfa)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81184f2c)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81217a4d)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff8124ba10)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8125dd46)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8127a95f)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81289167)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81295f91)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory_hotplug.c (ffffffff81a68834)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a6077)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b2000)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c404a)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812c9feb)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812cbb05)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812cc2dc)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8137853c)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8163923c)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff816e2da8)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/edac/edac_mc.c (ffffffff8185d8fd)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818a1d20)
Location: include/linux/mmzone.h:1286
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
In arch/x86/mm/init_64.c (ffffffff8106d1c5)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106f570)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81073c38)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81075d30)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810f5f9a)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8117806c)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8120ac5d)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff8123e9b0)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff81250196)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8126c83f)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff8127b007)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81287ba1)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory_hotplug.c (ffffffff81a252f4)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81297b27)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a3390)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In mm/memory-failure.c (ffffffff812b508a)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812bb02b)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812bc985)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812bd14c)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8136900c)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In drivers/base/memory.c (ffffffff816bd3e8)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d1c4)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81824ecd)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8185d490)
Location: include/linux/mmzone.h:1286
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
In arch/x86/mm/init_64.c (ffffffff8107ded1)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810805d0)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81084f18)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087110)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81102faa)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81182cfc)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812157ed)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff812497b0)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8125bae6)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff812786ff)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81286f77)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81293da1)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory_hotplug.c (ffffffff81ad4c44)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a3e87)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812afe10)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c1e5a)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812c7dfb)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812c9915)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812ca0ec)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8137600c)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff816382fc)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8166738c)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff8170ff38)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c7f94)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818acf2d)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818f3310)
Location: include/linux/mmzone.h:1286
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
In arch/x86/mm/init_64.c (ffffffff8107ffc1)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810826f0)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81087068)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81089240)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8110e39a)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119061c)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812247ed)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff81259030)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8126b4cd)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff812882ef)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/hugetlb.c (ffffffff81297647)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff812a3c01)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In mm/memory_hotplug.c (ffffffff81ae111f)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812b4756)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812c0150)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In mm/memory-failure.c (ffffffff812d28fa)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812d8b0b)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812da615)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812dadec)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81389abc)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8165263c)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8168194c)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff8172b098)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2234)
Location: include/linux/mmzone.h:1286
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818c917d)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff819143b0)
Location: include/linux/mmzone.h:1286
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
</ul>

## Differences
