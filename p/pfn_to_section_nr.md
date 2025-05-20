# Function: <code>pfn_to_section_nr</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: include/linux/mmzone.h:1093
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81073c59)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In arch/x86/mm/physaddr.c (ffffffff81079ffd)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810e4d2f)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81158305)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/memremap.c (ffffffff811c8a58)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
```
```
In mm/page_alloc.c (ffffffff811da08a)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/vmstat.c (ffffffff811f4d38)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811fefd6)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff81210f99)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
```
```
In mm/hugetlb.c (ffffffff81230a2f)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff8198efa2)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:memory_present
  - mm/sparse.c:node_memmap_size_bytes
```
```
In mm/memory_hotplug.c (ffffffff81248cfc)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8124a74d)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812556a5)
Location: include/linux/mmzone.h:1093
Inline: True
```
```
In mm/memory-failure.c (ffffffff812658d5)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff8126719b)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff8126ad6b)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff8126c2b5)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8126cadb)
Location: include/linux/mmzone.h:1093
Inline: True
```
```
In fs/proc/page.c (ffffffff812fc742)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159f7e6)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_do_proc
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815ca5f4)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff816612f5)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - drivers/base/node.c:link_mem_sections
```
```
In drivers/base/memory.c (ffffffff81661988)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/edac/edac_mc.c (ffffffff817ce7c0)
Location: include/linux/mmzone.h:1093
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8181c12c)
Location: include/linux/mmzone.h:1093
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
In arch/x86/mm/init_64.c (ffffffff810742db)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81076678)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In arch/x86/mm/mmap.c (ffffffff8107ac92)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8107cdbd)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810ec9b0)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81166f25)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff811e8f93)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/page_alloc.c (ffffffff811fa8fb)
Location: include/linux/mmzone.h:1092
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
In mm/vmstat.c (ffffffff81215fe2)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff812203d2)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff8123198b)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff8125267e)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff819eb83f)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_early_usemaps_alloc_node
  - mm/sparse.c:sparse_early_usemaps_alloc_node
  - mm/sparse.c:memory_present
```
```
In mm/memory_hotplug.c (ffffffff8126b995)
Location: include/linux/mmzone.h:1092
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
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8126da99)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81279503)
Location: include/linux/mmzone.h:1092
Inline: True
```
```
In mm/memory-failure.c (ffffffff81289cb5)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/page_isolation.c (ffffffff8128badb)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff8128f74b)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff81290e55)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8129168a)
Location: include/linux/mmzone.h:1092
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81328b65)
Location: include/linux/mmzone.h:1092
Inline: True
```
```
In fs/proc/page.c (ffffffff8132a347)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d743b)
Location: include/linux/mmzone.h:1092
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/mmzone.h:1092
Inline: True
```
```
In drivers/base/node.c (ffffffff8169caa5)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - drivers/base/node.c:link_mem_sections
```
```
In drivers/base/memory.c (ffffffff8169d3ba)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/edac/edac_mc.c (ffffffff81817433)
Location: include/linux/mmzone.h:1092
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff81866324)
Location: include/linux/mmzone.h:1092
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
In arch/x86/mm/init_64.c (ffffffff8107a1cb)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8107ccc8)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In arch/x86/mm/mmap.c (ffffffff810815d2)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810837cd)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810f8050)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81173c85)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff811f9ca3)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/page_alloc.c (ffffffff8120d07b)
Location: include/linux/mmzone.h:1100
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
In mm/vmstat.c (ffffffff81228ee2)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81233352)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff8124516b)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff812668de)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81a26b00)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
```
```
In mm/memory_hotplug.c (ffffffff81280fce)
Location: include/linux/mmzone.h:1100
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
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8128209f)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8128db86)
Location: include/linux/mmzone.h:1100
Inline: True
```
```
In mm/memory-failure.c (ffffffff8129ec25)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/page_isolation.c (ffffffff812a0a3b)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff812a466b)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812a5e75)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812a66aa)
Location: include/linux/mmzone.h:1100
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8133f9a5)
Location: include/linux/mmzone.h:1100
Inline: True
```
```
In fs/proc/page.c (ffffffff81341657)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f0bbb)
Location: include/linux/mmzone.h:1100
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/mmzone.h:1100
Inline: True
```
```
In drivers/base/node.c (ffffffff816bc73d)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816bd75a)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/edac/edac_mc.c (ffffffff81842cd3)
Location: include/linux/mmzone.h:1100
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff81885ef4)
Location: include/linux/mmzone.h:1100
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
In arch/x86/mm/init_64.c (ffffffff8107de5d)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81080925)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff8108524d)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087441)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81100643)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81180a65)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81211be2)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffff81238bbe)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81244ec7)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff8125712f)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff81273468)
Location: include/linux/mmzone.h:1140
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
In mm/shuffle.c (ffffffff81a957dc)
Location: include/linux/mmzone.h:1140
Inline: True
```
```
In mm/hugetlb.c (ffffffff81281b88)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81a972ee)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory_hotplug.c (ffffffff81a921fd)
Location: include/linux/mmzone.h:1140
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
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8129e1b0)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a8515)
Location: include/linux/mmzone.h:1140
Inline: True
```
```
In mm/memory-failure.c (ffffffff812ba2f5)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/page_isolation.c (ffffffff812bbccc)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff812bfa8b)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812c15b5)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812c1da1)
Location: include/linux/mmzone.h:1140
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81367c95)
Location: include/linux/mmzone.h:1140
Inline: True
```
```
In fs/proc/page.c (ffffffff81369a4a)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff816229b5)
Location: include/linux/mmzone.h:1140
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81650f75)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff816f6f88)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816f9205)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/edac/edac_mc.c (ffffffff81885aa6)
Location: include/linux/mmzone.h:1140
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818d04cf)
Location: include/linux/mmzone.h:1140
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
In arch/x86/mm/init_64.c (ffffffff8107eeed)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810815f5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81085f3d)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81088131)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8110caa3)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8118c8d5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8121f3d2)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffff81246eae)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81253387)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff812656bf)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff812822d8)
Location: include/linux/mmzone.h:1147
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
In mm/shuffle.c (ffffffff81acd0bf)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/hugetlb.c (ffffffff812915b3)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81acebd0)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory_hotplug.c (ffffffff81ac998d)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812ada60)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b99f5)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/memory-failure.c (ffffffff812cba25)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812cdbac)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff812d19db)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812d34e5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812d3cd1)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8137ff15)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In fs/proc/page.c (ffffffff81381caf)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff81644485)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81673515)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff8171b394)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff8171d585)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d30e5)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818b7a46)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff819028bf)
Location: include/linux/mmzone.h:1147
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
In arch/x86/mm/init_64.c (ffffffff81085810)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81088547)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff8108969d)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a5d1)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81117d2e)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:mark_nosave_pages
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811a1295)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8124b635)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmstat.c (ffffffff81274711)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff812822c6)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff812957fe)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/page_alloc.c (ffffffff812b43ef)
Location: include/linux/mmzone.h:1121
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
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/shuffle.c (ffffffff81bc5a73)
Location: include/linux/mmzone.h:1121
Inline: True
```
```
In mm/hugetlb.c (ffffffff812c3ce1)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
```
In mm/sparse.c (ffffffff81bc76c7)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:clear_subsection_map
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory_hotplug.c (ffffffff812e08eb)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:scan_movable_pages
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:register_page_bootmem_info_section
```
```
In mm/migrate.c (ffffffff812e2539)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/huge_memory.c (ffffffff812ee52e)
Location: include/linux/mmzone.h:1121
Inline: True
```
```
In mm/memory-failure.c (ffffffff813027d5)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff81303daa)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/page_idle.c (ffffffff813091c5)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff813097a8)
Location: include/linux/mmzone.h:1121
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813ca6b5)
Location: include/linux/mmzone.h:1121
Inline: True
```
```
In fs/proc/page.c (ffffffff813cc292)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0f4f)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817237b0)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff817d744c)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff817d9425)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e005)
Location: include/linux/mmzone.h:1121
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81987cd5)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff819d982b)
Location: include/linux/mmzone.h:1121
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
In arch/x86/mm/init_64.c (ffffffff810868c0)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81088787)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff8108987d)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a871)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8111416e)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:mark_nosave_pages
```
```
In kernel/dma/mapping.c (ffffffff81137611)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_map_resource
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e3e5)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81255a25)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmstat.c (ffffffff8127ef64)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8128c409)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff812a0be3)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
```
```
In mm/vmalloc.c (ffffffff812b21f8)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/page_alloc.c (ffffffff812c026b)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/shuffle.c (ffffffff81c3ea59)
Location: include/linux/mmzone.h:1159
Inline: True
```
```
In mm/hugetlb.c (ffffffff812cf395)
Location: include/linux/mmzone.h:1159
Inline: True
```
```
In mm/sparse.c (ffffffff81c40413)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:clear_subsection_map
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory_hotplug.c (ffffffff812eb95c)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:scan_movable_pages
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:register_page_bootmem_info_section
```
```
In mm/migrate.c (ffffffff812ed969)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/huge_memory.c (ffffffff812f9ba1)
Location: include/linux/mmzone.h:1159
Inline: True
```
```
In mm/memory-failure.c (ffffffff8130ead9)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff8130fc7a)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/page_idle.c (ffffffff81315035)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff813155b8)
Location: include/linux/mmzone.h:1159
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813dc37b)
Location: include/linux/mmzone.h:1159
Inline: True
```
```
In fs/proc/page.c (ffffffff813ddecf)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e12f)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817404f0)
Location: include/linux/mmzone.h:1159
Inline: True
```
```
In drivers/base/node.c (ffffffff817ebec3)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff817eddc5)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ace45)
Location: include/linux/mmzone.h:1159
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8198bc05)
Location: include/linux/mmzone.h:1159
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff819d8b89)
Location: include/linux/mmzone.h:1159
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
In arch/x86/mm/init_64.c (ffffffff81086750)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:pfn_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81089390)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:pfn_valid
```
```
In arch/x86/mm/mmap.c (ffffffff8108a090)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_valid
```
```
In arch/x86/mm/physaddr.c (ffffffff8108b460)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:pfn_valid
```
```
In kernel/power/snapshot.c (ffffffff81112b20)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - kernel/power/snapshot.c:pfn_valid
```
```
In kernel/dma/mapping.c (ffffffff81138380)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - kernel/dma/mapping.c:pfn_valid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119efd0)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:pfn_valid
```
```
In kernel/iomem.c (ffffffff81259fd0)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - kernel/iomem.c:pfn_valid
```
```
In mm/compaction.c (ffffffff812912c5)
Location: include/linux/mmzone.h:1223
Inline: True
```
```
In mm/memory.c (ffffffff8129c490)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - mm/memory.c:pfn_valid
```
```
In mm/vmalloc.c (ffffffff812b7870)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - mm/vmalloc.c:pfn_valid
```
```
In mm/page_alloc.c (ffffffff812c59e5)
Location: include/linux/mmzone.h:1223
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
In mm/memory_hotplug.c (ffffffff812c7572)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:section_taint_zone_device
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:pfn_to_online_page
  - mm/memory_hotplug.c:pfn_valid
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/hugetlb.c (ffffffff812d6025)
Location: include/linux/mmzone.h:1223
Inline: True
```
```
In mm/sparse.c (ffffffff81c323a3)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/migrate.c (ffffffff812f2df0)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - mm/migrate.c:pfn_valid
```
```
In mm/huge_memory.c (ffffffff81300326)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff81312940)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - mm/memory-failure.c:pfn_valid
```
```
In fs/proc/kcore.c (ffffffff813e2c80)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - fs/proc/kcore.c:pfn_valid
```
```
In drivers/acpi/apei/ghes.c (ffffffff816ef850)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:pfn_valid
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723cb0)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:pfn_valid
```
```
In drivers/base/node.c (ffffffff817d06e3)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff817d2715)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8188f930)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:pfn_valid
```
```
In drivers/edac/edac_mc.c (ffffffff81970310)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:pfn_valid
```
```
In drivers/ras/cec.c (ffffffff819be940)
Location: include/linux/mmzone.h:1223
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
In arch/x86/mm/init_64.c (ffffffff81095a3a)
Location: include/linux/mmzone.h:1261
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81098822)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:pfn_valid
```
```
In arch/x86/mm/mmap.c (ffffffff810995d2)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_valid
```
```
In arch/x86/mm/physaddr.c (ffffffff8109aa11)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:pfn_valid
```
```
In kernel/power/snapshot.c (ffffffff81132d5a)
Location: include/linux/mmzone.h:1261
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff8115b1e1)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - kernel/dma/mapping.c:pfn_valid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c8e61)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:pfn_valid
```
```
In kernel/iomem.c (ffffffff81295da1)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - kernel/iomem.c:pfn_valid
```
```
In mm/compaction.c (ffffffff812d0ee2)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - mm/compaction.c:pfn_valid
```
```
In mm/memory.c (ffffffff812dd1aa)
Location: include/linux/mmzone.h:1261
Inline: True
```
```
In mm/vmalloc.c (ffffffff812f9fa2)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - mm/vmalloc.c:pfn_valid
```
```
In mm/page_alloc.c (ffffffff8130a100)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff8130c2f9)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:section_taint_zone_device
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/hugetlb.c (ffffffff8131baf2)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - mm/hugetlb.c:pfn_valid
```
```
In mm/sparse.c (ffffffff81d50d9f)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/huge_memory.c (ffffffff81349f92)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff8135e57a)
Location: include/linux/mmzone.h:1261
Inline: True
```
```
In mm/bootmem_info.c (ffffffff832de7ea)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff814347b2)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - fs/proc/kcore.c:pfn_valid
```
```
In drivers/acpi/apei/ghes.c (ffffffff817698c1)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:pfn_valid
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2c3a)
Location: include/linux/mmzone.h:1261
Inline: True
```
```
In drivers/base/node.c (ffffffff8185b07d)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff8185d865)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923252)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:pfn_valid
```
```
In drivers/edac/edac_mc.c (ffffffff81a18c32)
Location: include/linux/mmzone.h:1261
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:pfn_valid
```
```
In drivers/ras/cec.c (ffffffff81a6dee1)
Location: include/linux/mmzone.h:1261
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
In arch/x86/mm/init_64.c (ffffffff810a9298)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810ab4df)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810aca6c)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810add6b)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81156dbd)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fca4f)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812ebaf7)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff8132fd0c)
Location: include/linux/mmzone.h:1304
Inline: True
```
```
In mm/memory.c (ffffffff81348bdb)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
```
```
In mm/vmalloc.c (ffffffff813602f2)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff81372d8c)
Location: include/linux/mmzone.h:1304
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
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff81f1ba35)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:section_taint_zone_device
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/hugetlb.c (ffffffff813881bc)
Location: include/linux/mmzone.h:1304
Inline: True
```
```
In mm/sparse.c (ffffffff81f20faf)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/huge_memory.c (ffffffff813c09bf)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff813dd18f)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff834940cd)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff814aed6c)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e547)
Location: include/linux/mmzone.h:1304
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd0c4)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff819a1fd7)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff819a4cd5)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a794b3)
Location: include/linux/mmzone.h:1304
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81b81f61)
Location: include/linux/mmzone.h:1304
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81bdf127)
Location: include/linux/mmzone.h:1304
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
In arch/x86/mm/ioremap.c (ffffffff810c591f)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810c6b45)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810c7fb2)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81187953)
Location: include/linux/mmzone.h:1620
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
In kernel/debug/kdb/kdb_support.c (ffffffff8124416f)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81355d37)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff81378279)
Location: include/linux/mmzone.h:1620
Inline: True
```
```
In mm/compaction.c (ffffffff813a68b5)
Location: include/linux/mmzone.h:1620
Inline: True
```
```
In mm/memory.c (ffffffff813bd92c)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/vmalloc.c (ffffffff813dc3f1)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff813f050c)
Location: include/linux/mmzone.h:1620
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
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff820c3a30)
Location: include/linux/mmzone.h:1620
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
In mm/sparse.c (ffffffff820cab88)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory-failure.c (ffffffff81463fda)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff83ec85fa)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff81545423)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7a47)
Location: include/linux/mmzone.h:1620
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a3050b)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff81b13f47)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff81b17095)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_sub
  - drivers/base/memory.c:memblk_nr_poison_inc
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
```
In drivers/edac/edac_mc.c (ffffffff81d20897)
Location: include/linux/mmzone.h:1620
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81d8a708)
Location: include/linux/mmzone.h:1620
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
In arch/x86/mm/ioremap.c (ffffffff810c90aa)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810ca2c7)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810cb6ee)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81198ae3)
Location: include/linux/mmzone.h:1745
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
In kernel/debug/kdb/kdb_support.c (ffffffff8125b24f)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff813873c7)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813abac9)
Location: include/linux/mmzone.h:1745
Inline: True
```
```
In mm/mm_init.c (ffffffff836e04d9)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff813dba45)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff813f262c)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/vmalloc.c (ffffffff81410cfa)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff8142409c)
Location: include/linux/mmzone.h:1745
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
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff821477a6)
Location: include/linux/mmzone.h:1745
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
In mm/sparse.c (ffffffff8144efc5)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory-failure.c (ffffffff81499a92)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff836ed659)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff8157d003)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a30157)
Location: include/linux/mmzone.h:1745
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79d1a)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff81b62c77)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff81b65e05)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_sub
  - drivers/base/memory.c:memblk_nr_poison_inc
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
```
In drivers/edac/edac_mc.c (ffffffff81d89a94)
Location: include/linux/mmzone.h:1745
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81df8d08)
Location: include/linux/mmzone.h:1745
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
In arch/x86/mm/ioremap.c (ffffffff810d0d77)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810d272b)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810d3d4e)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff811a79b1)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8127511f)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff813b0d57)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813d61e9)
Location: include/linux/mmzone.h:1755
Inline: True
```
```
In mm/mm_init.c (ffffffff83912d27)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff814059a5)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8141d32c)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/vmalloc.c (ffffffff8143ef18)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff81449b4d)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff8222a03a)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:remove_memory_blocks_and_altmaps
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/sparse.c (ffffffff81488b85)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory-failure.c (ffffffff814c91c0)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff8392065d)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff815b5953)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b2b7)
Location: include/linux/mmzone.h:1755
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc18e)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff81bb6787)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff81bb9c85)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_sub
  - drivers/base/memory.c:memblk_nr_poison_inc
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
```
In drivers/edac/edac_mc.c (ffffffff81e410da)
Location: include/linux/mmzone.h:1755
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81eaf398)
Location: include/linux/mmzone.h:1755
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
In arch/arm64/mm/init.c (ffff8000100ad680)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/arm64/mm/init.c:pfn_valid
```
```
In mm/vmstat.c (ffff8000102da250)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffff8000102e99cc)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/page_alloc.c (ffff8000103150a8)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/shuffle.c (ffff800010da00e4)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/hugetlb.c (ffff80001032e770)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
```
```
In mm/sparse.c (ffff800010da0790)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory_hotplug.c (ffff800010d9ce84)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
```
```
In mm/memory-failure.c (ffff80001036f35c)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffff800010371f90)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In fs/proc/page.c (ffff80001044fa98)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/node.c (ffff80001090ece8)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffff800010911264)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
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
In arch/powerpc/kernel/stacktrace.c (c000000000069128)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/powerpc/kernel/stacktrace.c:pfn_valid
```
```
In arch/powerpc/mm/pgtable.c (c000000000087850)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:maybe_pte_to_page
```
```
In arch/powerpc/mm/init_64.c (c000000000eeb130)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/powerpc/mm/init_64.c:vmemmap_populated
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008cf38)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_do_lazy_icache
```
```
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fadd8)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock
```
```
In kernel/debug/kdb/kdb_support.c (c00000000027e420)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/events/core.c (c000000000350a50)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/iomem.c (c00000000035fac8)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (c00000000039aab0)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (c0000000003ad8ec)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (c0000000003c7878)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (c0000000003edec0)
Location: include/linux/mmzone.h:1147
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
In mm/shuffle.c (c000000000eecd1c)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/hugetlb.c (c0000000004077b0)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (c000000000eed674)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory_hotplug.c (c00000000043095c)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (c0000000004324a8)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (c000000000443b90)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/memory-failure.c (c000000000460910)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (c000000000463878)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (c000000000469a34)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (c00000000046bf58)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c00000000046cf78)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/usercopy.c (c00000000046d3ec)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In fs/proc/kcore.c (c0000000005654e8)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In fs/proc/page.c (c000000000567e1c)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/node.c (c0000000009af7d4)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (c0000000009b2678)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/spi/spi.c (c000000000a89f00)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/edac/edac_mc.c (c000000000c0332c)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5b5e0)
Location: include/linux/mmzone.h:1147
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
In kernel/events/core.c (ffffffe0001cefca)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/iomem.c (ffffffe0001d3638)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffe0001f4564)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffe0001ff0dc)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffe00020b6b2)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/page_alloc.c (ffffffe00021bb2e)
Location: include/linux/mmzone.h:1147
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
In mm/shuffle.c (ffffffe000047478)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/hugetlb.c (ffffffe00022c7b0)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffe0000186a0)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/migrate.c (ffffffe00023e8a8)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/page_isolation.c (ffffffe00024b2fe)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffe00024f4a2)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffe0002508f6)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffe000250f5e)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/usercopy.c (ffffffe00025122e)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In fs/proc/kcore.c (ffffffe0002e24fe)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In fs/proc/page.c (ffffffe0002e30a2)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/spi/spi.c (ffffffe000618b2e)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/edac/edac_mc.c (ffffffe0006fcf14)
Location: include/linux/mmzone.h:1147
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
In arch/x86/mm/init_64.c (ffffffff8107deed)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810805f5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81084f3d)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087131)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81104cc3)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81184ef5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81217a22)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffff8123f4fe)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8124b9d7)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff8125dd0f)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8127a928)
Location: include/linux/mmzone.h:1147
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
In mm/shuffle.c (ffffffff81a6bf2f)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/hugetlb.c (ffffffff81289b93)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81a6da40)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory_hotplug.c (ffffffff81a687fd)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a6040)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b1fd5)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c4005)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812c618c)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff812c9fbb)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812cbac5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812cc2b1)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813784f5)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In fs/proc/page.c (ffffffff8137a28f)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81639205)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff816e16c4)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816e38b5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/edac/edac_mc.c (ffffffff8185d8c6)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818a1cef)
Location: include/linux/mmzone.h:1147
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
In arch/x86/mm/init_64.c (ffffffff8106d199)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106f545)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81073c0d)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81075d01)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810f5f63)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81178035)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8120ac32)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffff812324fe)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff8123e977)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff8125015f)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff8126c808)
Location: include/linux/mmzone.h:1147
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
In mm/shuffle.c (ffffffff81a28476)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/hugetlb.c (ffffffff8127b9c3)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81a29f87)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory_hotplug.c (ffffffff81a252bd)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81297af0)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a3365)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/memory-failure.c (ffffffff812b5045)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812b71cc)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff812baffb)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812bc945)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812bd121)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81368fc5)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In fs/proc/page.c (ffffffff8136ad5f)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/base/node.c (ffffffff816bbd04)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816bdef5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d195)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81824e96)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8185d45f)
Location: include/linux/mmzone.h:1147
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
In arch/x86/mm/init_64.c (ffffffff8107de9d)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810805a5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81084eed)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810870e1)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81102f73)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81182cc5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812157c2)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffff8123d29e)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81249777)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff8125baaf)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff812786c8)
Location: include/linux/mmzone.h:1147
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
In mm/shuffle.c (ffffffff81ad833f)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/hugetlb.c (ffffffff812879a3)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81ad9e50)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory_hotplug.c (ffffffff81ad4c0d)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a3e50)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812afde5)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c1e15)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812c3f9c)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff812c7dcb)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812c98d5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812ca0c1)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81375fc5)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In fs/proc/page.c (ffffffff81377d5f)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff816382c5)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81667355)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff8170ebf4)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff81710a45)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c7f65)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818acef6)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818f32df)
Location: include/linux/mmzone.h:1147
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
In arch/x86/mm/init_64.c (ffffffff8107ff8d)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810826c5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff8108703d)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81089211)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8110e363)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811905e5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812247c2)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffff8124c9ce)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff81258ff7)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffff8126b492)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff812882b8)
Location: include/linux/mmzone.h:1147
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
In mm/shuffle.c (ffffffff81ae47fa)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/hugetlb.c (ffffffff81297f40)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/sparse.c (ffffffff81ae6306)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
  - mm/sparse.c:subsection_map_init
```
```
In mm/memory_hotplug.c (ffffffff81ae10e8)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812b471e)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812c0125)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In mm/memory-failure.c (ffffffff812d28b5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/page_isolation.c (ffffffff812d4a3c)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/cma.c (ffffffff812d8adb)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/cma.c:pfn_valid
```
```
In mm/page_idle.c (ffffffff812da5d5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812dadc1)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81389a75)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In fs/proc/page.c (ffffffff8138b809)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652605)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81681915)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff817299b4)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff8172bba5)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:walk_memory_blocks
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2205)
Location: include/linux/mmzone.h:1147
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818c9146)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8191437f)
Location: include/linux/mmzone.h:1147
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
</ul>

## Differences
