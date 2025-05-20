# Function: <code>pfn_valid</code>

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
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106b905)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/physaddr.c (ffffffff8107143c)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810d06e5)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811379a5)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In mm/page_alloc.c (ffffffff8181ce32)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/vmstat.c (ffffffff811acfc9)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811b4bb5)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - mm/compaction.c:pageblock_pfn_to_page
  - mm/compaction.c:pageblock_pfn_to_page
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff811c1c69)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_pfn
  - mm/memory.c:clear_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
```
```
In mm/hugetlb.c (ffffffff811daa2a)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/memory_hotplug.c (ffffffff818197e2)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff811f1f55)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff811f5c14)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/memory-failure.c (ffffffff81201b15)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff81f8e319)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff812080e5)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8120898e)
Location: include/linux/mmzone.h:1127
Inline: True
```
```
In fs/proc/page.c (ffffffff81287e7b)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpageflags_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b5ff2)
Location: include/linux/mmzone.h:1127
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d4863)
Location: include/linux/mmzone.h:1127
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff81560f3a)
Location: include/linux/mmzone.h:1127
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
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106b7e5)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/physaddr.c (ffffffff8107132d)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810d6e9f)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8113fe75)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/memremap.c (ffffffff8119e3c3)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
```
```
In mm/page_alloc.c (ffffffff811acaa8)
Location: include/linux/mmzone.h:1199
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
In mm/vmstat.c (ffffffff811c625f)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811cee43)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff811ddf51)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff811fa0bd)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/memory_hotplug.c (ffffffff818933da)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812109dc)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8121858e)
Location: include/linux/mmzone.h:1199
Inline: True
```
```
In mm/memory-failure.c (ffffffff812276b5)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff81fb890d)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff8122db05)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8122e38f)
Location: include/linux/mmzone.h:1199
Inline: True
```
```
In fs/proc/page.c (ffffffff812b51cb)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff815059c8)
Location: include/linux/mmzone.h:1199
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81525815)
Location: include/linux/mmzone.h:1199
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff815b5c8b)
Location: include/linux/mmzone.h:1199
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
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106f3ff)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/physaddr.c (ffffffff81074ead)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810dda20)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81149c45)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/memremap.c (ffffffff811addf3)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
```
```
In mm/page_alloc.c (ffffffff811bd070)
Location: include/linux/mmzone.h:1177
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
In mm/vmstat.c (ffffffff811d6398)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffff811def5a)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/memory.c (ffffffff811edd66)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff8120ab85)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/memory_hotplug.c (ffffffff818c7c27)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81222b29)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8122ab19)
Location: include/linux/mmzone.h:1177
Inline: True
```
```
In mm/memory-failure.c (ffffffff81239c45)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff81ff5274)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff81240045)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812408bf)
Location: include/linux/mmzone.h:1177
Inline: True
```
```
In fs/proc/page.c (ffffffff812caa4e)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff81529bc5)
Location: include/linux/mmzone.h:1177
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81551cd5)
Location: include/linux/mmzone.h:1177
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff815e4fa7)
Location: include/linux/mmzone.h:1177
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
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106eb4b)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/physaddr.c (ffffffff8107445d)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810dcb10)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114ba45)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/memremap.c (ffffffff811b5295)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
```
```
In mm/page_alloc.c (ffffffff811c52c0)
Location: include/linux/mmzone.h:1218
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
In mm/memory.c (ffffffff811f8c40)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff81215e42)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/memory_hotplug.c (ffffffff818ff1ff)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8122e4fb)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812366da)
Location: include/linux/mmzone.h:1218
Inline: True
```
```
In mm/memory-failure.c (ffffffff81245915)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff820d7a07)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff8124bf05)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8124c65a)
Location: include/linux/mmzone.h:1218
Inline: True
```
```
In fs/proc/page.c (ffffffff812d7ed1)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153cca5)
Location: include/linux/mmzone.h:1218
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81566457)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff815f9a91)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/edac/edac_mc.c (ffffffff8175c57d)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff817a4f8b)
Location: include/linux/mmzone.h:1218
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81071479)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81073c38)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In arch/x86/mm/physaddr.c (ffffffff81079ffd)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810e4d2f)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81158305)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/memremap.c (ffffffff811c8a58)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - kernel/memremap.c:memremap
```
```
In mm/page_alloc.c (ffffffff811da071)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory.c (ffffffff81210f99)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff81230a2f)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/memory_hotplug.c (ffffffff81989b5b)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
Direct callers:
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8124a74d)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812556a5)
Location: include/linux/mmzone.h:1231
Inline: True
```
```
In mm/memory-failure.c (ffffffff812658d5)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff8126ad6b)
Location: include/linux/mmzone.h:1231
Inline: False
Direct callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff8126c2b5)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8126cadb)
Location: include/linux/mmzone.h:1231
Inline: True
```
```
In fs/proc/page.c (ffffffff812fc742)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159f7e6)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_do_proc
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815ca5f4)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff81661988)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/edac/edac_mc.c (ffffffff817ce7c0)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8181c12c)
Location: include/linux/mmzone.h:1231
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff811d2e50-ffffffff811d2e96: pfn_valid (STB_LOCAL)
ffffffff81247860-ffffffff812478a6: pfn_valid (STB_LOCAL)
ffffffff8126ad6b-ffffffff8126adb1: pfn_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810742db)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81076678)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In arch/x86/mm/mmap.c (ffffffff8107ac92)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8107cdbd)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810ec9b0)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81166f25)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff811e8f93)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/page_alloc.c (ffffffff811fa8fb)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory.c (ffffffff8123198b)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vm_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff8125267e)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/memory_hotplug.c (ffffffff819e6555)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
Direct callers:
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8126da99)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81279503)
Location: include/linux/mmzone.h:1238
Inline: True
```
```
In mm/memory-failure.c (ffffffff81289cb5)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/cma.c (ffffffff8128f74b)
Location: include/linux/mmzone.h:1238
Inline: False
Direct callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff81290e55)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff8129168a)
Location: include/linux/mmzone.h:1238
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81328b65)
Location: include/linux/mmzone.h:1238
Inline: True
```
```
In fs/proc/page.c (ffffffff8132a347)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d743b)
Location: include/linux/mmzone.h:1238
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81602e02)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff8169d3ba)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - drivers/base/memory.c:store_soft_offline_page
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/edac/edac_mc.c (ffffffff81817433)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff81866324)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff810ed0a4-ffffffff810ed0e5: pfn_valid (STB_LOCAL)
ffffffff811f41f0-ffffffff811f4231: pfn_valid (STB_LOCAL)
ffffffff8126b350-ffffffff8126b391: pfn_valid (STB_LOCAL)
ffffffff8128f74b-ffffffff8128f78c: pfn_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107a1cb)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8107ccc8)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In arch/x86/mm/mmap.c (ffffffff810815d2)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810837cd)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810f8050)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81173c85)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff811f9ca3)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/page_alloc.c (ffffffff8120d07b)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
Direct callers:
  - mm/page_alloc.c:zero_pfn_range
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory.c (ffffffff8124516b)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/hugetlb.c (ffffffff812668de)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/memory_hotplug.c (ffffffff81a218c9)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
Direct callers:
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8128209f)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8128db86)
Location: include/linux/mmzone.h:1246
Inline: True
```
```
In mm/memory-failure.c (ffffffff8129ec25)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/cma.c (ffffffff812a466b)
Location: include/linux/mmzone.h:1246
Inline: False
Direct callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffff812a5e75)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812a66aa)
Location: include/linux/mmzone.h:1246
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8133f9a5)
Location: include/linux/mmzone.h:1246
Inline: True
```
```
In fs/proc/page.c (ffffffff81341657)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f0bbb)
Location: include/linux/mmzone.h:1246
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161df32)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff816bd75a)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/edac/edac_mc.c (ffffffff81842cd3)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff81885ef4)
Location: include/linux/mmzone.h:1246
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff810f6670-ffffffff810f66b1: pfn_valid (STB_LOCAL)
ffffffff81206580-ffffffff812065c1: pfn_valid (STB_LOCAL)
ffffffff8127fbe0-ffffffff8127fc21: pfn_valid (STB_LOCAL)
ffffffff812a466b-ffffffff812a46ac: pfn_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107de5d)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81080925)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff8108524d)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087441)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81100643)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81180a65)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81211be2)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff81244ec7)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8125712f)
Location: include/linux/mmzone.h:1338
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
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
Direct callers:
  - mm/page_alloc.c:zero_pfn_range
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/hugetlb.c (ffffffff81281b88)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/memory_hotplug.c (ffffffff81a921fd)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
Direct callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8129e1b0)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a8515)
Location: include/linux/mmzone.h:1338
Inline: True
```
```
In mm/memory-failure.c (ffffffff812ba2f5)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/cma.c (ffffffff812bfa8b)
Location: include/linux/mmzone.h:1338
Inline: False
Direct callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/page_idle.c (ffffffff812c15b5)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812c1da1)
Location: include/linux/mmzone.h:1338
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81367c95)
Location: include/linux/mmzone.h:1338
Inline: True
```
```
In fs/proc/page.c (ffffffff81369a4a)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/acpi/apei/ghes.c (ffffffff816229b5)
Location: include/linux/mmzone.h:1338
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81650f75)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff816f8673)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/edac/edac_mc.c (ffffffff81885aa6)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818d04cf)
Location: include/linux/mmzone.h:1338
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff810fec10-ffffffff810fec77: pfn_valid (STB_LOCAL)
ffffffff8126c740-ffffffff8126c7a7: pfn_valid (STB_LOCAL)
ffffffff8129bb40-ffffffff8129bba7: pfn_valid (STB_LOCAL)
ffffffff812bfa8b-ffffffff812bfaef: pfn_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107eeed)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810815f5)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81085f3d)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81088131)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8110caa3)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8118c8d5)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8121f3d2)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff81253387)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff812656bf)
Location: include/linux/mmzone.h:1345
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
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
Direct callers:
  - mm/page_alloc.c:zero_pfn_range
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/hugetlb.c (ffffffff81290b5b)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/memory_hotplug.c (ffffffff81ac998d)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812ada60)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b99f5)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In mm/memory-failure.c (ffffffff812cba25)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812d19db)
Location: include/linux/mmzone.h:1345
Inline: False
Direct callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/page_idle.c (ffffffff812d34e5)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812d3cd1)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8137ff15)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff81644485)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81673515)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff8171ca53)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d30e5)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818b7a46)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff819028bf)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff8110b060-ffffffff8110b0c7: pfn_valid (STB_LOCAL)
ffffffff8127b550-ffffffff8127b5b7: pfn_valid (STB_LOCAL)
ffffffff812d19db-ffffffff812d1a3f: pfn_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81085810)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81088547)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff8108969d)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a5d1)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81117d2e)
Location: include/linux/mmzone.h:1322
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
In kernel/debug/kdb/kdb_support.c (ffffffff811a1295)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8124b635)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff812822c6)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff812957fe)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
Direct callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/page_alloc.c (ffffffff812b43ef)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
Direct callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/hugetlb.c (ffffffff812c3ce1)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
```
In mm/memory_hotplug.c (ffffffff812e0d60)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
Direct callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812e2539)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/huge_memory.c (ffffffff812ee52e)
Location: include/linux/mmzone.h:1322
Inline: True
```
```
In mm/memory-failure.c (ffffffff813027d5)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/frame_vector.c (ffffffff813097a8)
Location: include/linux/mmzone.h:1322
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813ca6b5)
Location: include/linux/mmzone.h:1322
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0f4f)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817237b0)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e005)
Location: include/linux/mmzone.h:1322
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81987cd5)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff819d982b)
Location: include/linux/mmzone.h:1322
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff8111826a-ffffffff811182e4: pfn_valid (STB_LOCAL)
ffffffff8128b940-ffffffff8128b9c0: pfn_valid (STB_LOCAL)
ffffffff812ae3a0-ffffffff812ae420: pfn_valid (STB_LOCAL)
ffffffff812e0c20-ffffffff812e0ca0: pfn_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810868c0)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81088787)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff8108987d)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a871)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8111416e)
Location: include/linux/mmzone.h:1360
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
In kernel/dma/mapping.c (ffffffff81137611)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_map_resource
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e3e5)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81255a25)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff8128c409)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff812a0be3)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
Direct callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/vmalloc.c (ffffffff812b21f8)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/page_alloc.c (ffffffff812bcca9)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
Direct callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/hugetlb.c (ffffffff812cf395)
Location: include/linux/mmzone.h:1360
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812ebb60)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
Direct callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812ed969)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/huge_memory.c (ffffffff812f9ba1)
Location: include/linux/mmzone.h:1360
Inline: True
```
```
In mm/memory-failure.c (ffffffff8130ead9)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/frame_vector.c (ffffffff813155b8)
Location: include/linux/mmzone.h:1360
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813dc37b)
Location: include/linux/mmzone.h:1360
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e12f)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817404f0)
Location: include/linux/mmzone.h:1360
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ace45)
Location: include/linux/mmzone.h:1360
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8198bc05)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff819d8b89)
Location: include/linux/mmzone.h:1360
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81bdf701-ffffffff81bdf77b: pfn_valid (STB_LOCAL)
ffffffff812968f0-ffffffff81296970: pfn_valid (STB_LOCAL)
ffffffff812b9fc0-ffffffff812ba040: pfn_valid (STB_LOCAL)
ffffffff812eba20-ffffffff812ebaa0: pfn_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086750)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81089390)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff8108a090)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8108b460)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81112b20)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/dma/mapping.c (ffffffff81138380)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_resource
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119efd0)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81259fd0)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff812912c5)
Location: include/linux/mmzone.h:1430
Inline: True
```
```
In mm/memory.c (ffffffff8129c490)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/vmalloc.c (ffffffff812b7870)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/page_alloc.c (ffffffff812bf290)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory_hotplug.c (ffffffff812c6310)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/hugetlb.c (ffffffff812d6025)
Location: include/linux/mmzone.h:1430
Inline: True
```
```
In mm/migrate.c (ffffffff812f2df0)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81300326)
Location: include/linux/mmzone.h:1430
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff81312940)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In fs/proc/kcore.c (ffffffff813e2c80)
Location: include/linux/mmzone.h:1430
Inline: False
```
```
In drivers/acpi/apei/ghes.c (ffffffff816ef850)
Location: include/linux/mmzone.h:1430
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723cb0)
Location: include/linux/mmzone.h:1430
Inline: False
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8188f930)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
  - drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin
```
```
In drivers/edac/edac_mc.c (ffffffff81970310)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_ce_error
```
```
In drivers/ras/cec.c (ffffffff819be940)
Location: include/linux/mmzone.h:1430
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81086750-ffffffff810867ce: pfn_valid (STB_LOCAL)
ffffffff81089390-ffffffff8108940e: pfn_valid (STB_LOCAL)
ffffffff8108a090-ffffffff8108a10e: pfn_valid (STB_LOCAL)
ffffffff8108b460-ffffffff8108b4de: pfn_valid (STB_LOCAL)
ffffffff81112b20-ffffffff81112b9e: pfn_valid (STB_LOCAL)
ffffffff81138380-ffffffff811383fe: pfn_valid (STB_LOCAL)
ffffffff8119efd0-ffffffff8119f04e: pfn_valid (STB_LOCAL)
ffffffff81259fd0-ffffffff8125a04e: pfn_valid (STB_LOCAL)
ffffffff8129c490-ffffffff8129c50e: pfn_valid (STB_LOCAL)
ffffffff812b7870-ffffffff812b78ee: pfn_valid (STB_LOCAL)
ffffffff812bf290-ffffffff812bf30e: pfn_valid (STB_LOCAL)
ffffffff812c6310-ffffffff812c638e: pfn_valid (STB_LOCAL)
ffffffff812f2df0-ffffffff812f2e6e: pfn_valid (STB_LOCAL)
ffffffff81312940-ffffffff813129be: pfn_valid (STB_LOCAL)
ffffffff813e2c80-ffffffff813e2cfe: pfn_valid (STB_LOCAL)
ffffffff816ef850-ffffffff816ef8ce: pfn_valid (STB_LOCAL)
ffffffff81723cb0-ffffffff81723d2e: pfn_valid (STB_LOCAL)
ffffffff8188f930-ffffffff8188f9ae: pfn_valid (STB_LOCAL)
ffffffff81970310-ffffffff8197038e: pfn_valid (STB_LOCAL)
ffffffff819be940-ffffffff819be9be: pfn_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8109695f)
Location: include/linux/mmzone.h:1478
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff81098800)
Location: include/linux/mmzone.h:1478
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff810995b0)
Location: include/linux/mmzone.h:1478
Inline: False
Direct callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff8109aa00)
Location: include/linux/mmzone.h:1478
Inline: False
Direct callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81134ba9)
Location: include/linux/mmzone.h:1478
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:mark_nosave_pages
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:mark_nosave_pages
```
```
In kernel/dma/mapping.c (ffffffff8115b1d0)
Location: include/linux/mmzone.h:1478
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_resource
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c8e50)
Location: include/linux/mmzone.h:1478
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81295d90)
Location: include/linux/mmzone.h:1478
Inline: False
Direct callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff812d0ec0)
Location: include/linux/mmzone.h:1478
Inline: False
```
```
In mm/memory.c (ffffffff812e79e0)
Location: include/linux/mmzone.h:1478
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
Direct callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/vmalloc.c (ffffffff812f9f80)
Location: include/linux/mmzone.h:1478
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/page_alloc.c (ffffffff832d8718)
Location: include/linux/mmzone.h:1478
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:reserve_bootmem_region
Direct callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory_hotplug.c (ffffffff81d4c0ae)
Location: include/linux/mmzone.h:1478
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff8131bad0)
Location: include/linux/mmzone.h:1478
Inline: False
Direct callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/huge_memory.c (ffffffff81349f79)
Location: include/linux/mmzone.h:1478
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff81361035)
Location: include/linux/mmzone.h:1478
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff832de7b5)
Location: include/linux/mmzone.h:1478
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff81434790)
Location: include/linux/mmzone.h:1478
Inline: False
```
```
In drivers/acpi/apei/ghes.c (ffffffff817698b0)
Location: include/linux/mmzone.h:1478
Inline: False
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2e33)
Location: include/linux/mmzone.h:1478
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
Direct callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923230)
Location: include/linux/mmzone.h:1478
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
  - drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin
```
```
In drivers/edac/edac_mc.c (ffffffff81a18c10)
Location: include/linux/mmzone.h:1478
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_ce_error
```
```
In drivers/ras/cec.c (ffffffff81a6ded0)
Location: include/linux/mmzone.h:1478
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81095a30-ffffffff81095ab4: pfn_valid.part.0 (STB_LOCAL)
ffffffff81098800-ffffffff8109889a: pfn_valid (STB_LOCAL)
ffffffff810995b0-ffffffff8109964a: pfn_valid (STB_LOCAL)
ffffffff8109aa00-ffffffff8109aa80: pfn_valid (STB_LOCAL)
ffffffff81132d50-ffffffff81132dd4: pfn_valid.part.0 (STB_LOCAL)
ffffffff8115b1d0-ffffffff8115b250: pfn_valid (STB_LOCAL)
ffffffff811c8e50-ffffffff811c8ed0: pfn_valid (STB_LOCAL)
ffffffff81295d90-ffffffff81295e10: pfn_valid (STB_LOCAL)
ffffffff812d0ec0-ffffffff812d0f5a: pfn_valid (STB_LOCAL)
ffffffff812dd1a0-ffffffff812dd224: pfn_valid.part.0 (STB_LOCAL)
ffffffff812f9f80-ffffffff812fa01a: pfn_valid (STB_LOCAL)
ffffffff81301bd0-ffffffff81301c54: pfn_valid.part.0 (STB_LOCAL)
ffffffff8130adf0-ffffffff8130ae74: pfn_valid.part.0 (STB_LOCAL)
ffffffff8131bad0-ffffffff8131bb6a: pfn_valid (STB_LOCAL)
ffffffff8135e570-ffffffff8135e5f4: pfn_valid.part.0 (STB_LOCAL)
ffffffff81434790-ffffffff8143482a: pfn_valid (STB_LOCAL)
ffffffff817698b0-ffffffff81769930: pfn_valid (STB_LOCAL)
ffffffff817a2c30-ffffffff817a2cb4: pfn_valid.part.0 (STB_LOCAL)
ffffffff81923230-ffffffff819232ca: pfn_valid (STB_LOCAL)
ffffffff81a18c10-ffffffff81a18caa: pfn_valid (STB_LOCAL)
ffffffff81a6ded0-ffffffff81a6df50: pfn_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810a9287)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810ab4d0)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810aca54)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810add61)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81156daa)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fca45)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812ebaed)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff8132fcf4)
Location: include/linux/mmzone.h:1524
Inline: True
```
```
In mm/memory.c (ffffffff81348bc4)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
Direct callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/vmalloc.c (ffffffff813602db)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff8136d51a)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
Direct callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory_hotplug.c (ffffffff81f1ba22)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff813881a5)
Location: include/linux/mmzone.h:1524
Inline: True
```
```
In mm/huge_memory.c (ffffffff813c09ac)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff813dd165)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff834940a4)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff814aed4e)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e53d)
Location: include/linux/mmzone.h:1524
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd0ba)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79495)
Location: include/linux/mmzone.h:1524
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81b81f45)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81bdf11d)
Location: include/linux/mmzone.h:1524
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81e5a549-ffffffff81e5a612: pfn_valid (STB_LOCAL)
ffffffff8133cc90-ffffffff8133cd49: pfn_valid (STB_LOCAL)
ffffffff81369e50-ffffffff81369f09: pfn_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c5910)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810c6b18)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810c7fa1)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81187940)
Location: include/linux/mmzone.h:1863
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
In kernel/debug/kdb/kdb_support.c (ffffffff81244165)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81355d2d)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff8137826f)
Location: include/linux/mmzone.h:1863
Inline: True
```
```
In mm/compaction.c (ffffffff813a68a1)
Location: include/linux/mmzone.h:1863
Inline: True
```
```
In mm/memory.c (ffffffff813bd878)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
Direct callers:
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/vmalloc.c (ffffffff813dc2fb)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff83ebe756)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory_hotplug.c (ffffffff820c3a21)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/memory-failure.c (ffffffff81463f35)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff83ec85e1)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff815453fe)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7a3d)
Location: include/linux/mmzone.h:1863
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30506)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/edac/edac_mc.c (ffffffff81d20785)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81d8a6f0)
Location: include/linux/mmzone.h:1863
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff813b4dd0-ffffffff813b4e89: pfn_valid (STB_LOCAL)
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
In arch/x86/mm/ioremap.c (ffffffff810c9097)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810ca2a9)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810cb6dd)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81198ad0)
Location: include/linux/mmzone.h:1988
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
In kernel/debug/kdb/kdb_support.c (ffffffff8125b245)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff813873bd)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813ababf)
Location: include/linux/mmzone.h:1988
Inline: True
```
```
In mm/mm_init.c (ffffffff836e04c6)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff813da0ef)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff813f2578)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/vmalloc.c (ffffffff81410c1d)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff8141c746)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory_hotplug.c (ffffffff82147793)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/memory-failure.c (ffffffff814999f5)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff836ed64a)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff8157cfde)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a3014d)
Location: include/linux/mmzone.h:1988
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79d15)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/edac/edac_mc.c (ffffffff81d89965)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81df8cf0)
Location: include/linux/mmzone.h:1988
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810d0d64)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810d2709)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810d3d3d)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff811a79a2)
Location: include/linux/mmzone.h:1999
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
In kernel/debug/kdb/kdb_support.c (ffffffff81275115)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff813b0d4d)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813d61df)
Location: include/linux/mmzone.h:1999
Inline: True
```
```
In mm/mm_init.c (ffffffff83912d14)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff81403dff)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8141d278)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
Direct callers:
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/vmalloc.c (ffffffff8143ee8a)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff814491e6)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/memory_hotplug.c (ffffffff8222a02b)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/memory-failure.c (ffffffff814c9195)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff8392064a)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff815b592e)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b2ad)
Location: include/linux/mmzone.h:1999
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc189)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/edac/edac_mc.c (ffffffff81e410a8)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81eaf380)
Location: include/linux/mmzone.h:1999
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff814143c0-ffffffff814144b0: pfn_valid (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/init.c (ffff8000100ad658)
Location: arch/arm64/mm/init.c:241
Inline: False
Direct callers:
  - arch/arm64/mm/ioremap.c:__ioremap_caller
  - arch/arm64/mm/mmu.c:kern_addr_valid
  - arch/arm64/mm/mmu.c:kern_addr_valid
  - arch/arm64/mm/mmu.c:kern_addr_valid
  - arch/arm64/mm/mmu.c:phys_mem_access_prot
  - virt/kvm/kvm_main.c:__kvm_map_gfn
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:create_hyp_mappings
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - arch/arm/xen/mm.c:xen_dma_sync_for_device
  - arch/arm/xen/mm.c:xen_dma_sync_for_cpu
  - kernel/dma/mapping.c:dma_common_mmap
  - kernel/dma/mapping.c:dma_common_get_sgtable
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
  - kernel/events/core.c:perf_prepare_sample
  - kernel/iomem.c:memremap
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:zero_pfn_range
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:move_freepages_block
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:__free_one_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
  - mm/page_idle.c:page_idle_get_page
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/base/node.c:get_nid_for_pfn
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_block_action
  - drivers/spi/spi.c:spi_map_buf
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
**Symbols:**

```
ffff8000100ad658-ffff8000100ad6d8: pfn_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/init.c (c031a6f8)
Location: arch/arm/mm/init.c:176
Inline: False
Direct callers:
  - arch/arm/mm/flush.c:__sync_icache_dcache
  - arch/arm/mm/ioremap.c:__arm_ioremap_pfn_caller
  - kernel/power/snapshot.c:restore_highmem
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:saveable_highmem_page
  - kernel/power/snapshot.c:saveable_highmem_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
  - kernel/events/core.c:perf_prepare_sample
  - kernel/iomem.c:memremap
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
  - mm/page_idle.c:page_idle_get_page
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/pstore/ram_core.c:persistent_ram_new
  - fs/pstore/ram_core.c:persistent_ram_free
  - drivers/mtd/nand/raw/nand_base.c:nand_do_write_ops
  - drivers/mtd/nand/raw/nand_base.c:nand_do_read_ops
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
  - drivers/spi/spi.c:spi_map_buf
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
**Symbols:**

```
c031a6f8-c031a72c: pfn_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/stacktrace.c (c000000000069120)
Location: include/linux/mmzone.h:1345
Inline: False
```
```
In arch/powerpc/mm/pgtable.c (c000000000087850)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:maybe_pte_to_page
```
```
In arch/powerpc/mm/init_64.c (c000000000eeb130)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/powerpc/mm/init_64.c:vmemmap_populated
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008cf38)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_do_lazy_icache
```
```
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fadd8)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock
```
```
In kernel/debug/kdb/kdb_support.c (c00000000027e420)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/events/core.c (c000000000350a50)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/iomem.c (c00000000035fac8)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (c0000000003ad8ec)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (c0000000003c7878)
Location: include/linux/mmzone.h:1345
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
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
Direct callers:
  - mm/page_alloc.c:zero_pfn_range
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/hugetlb.c (c000000000406c3c)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/memory_hotplug.c (c00000000043095c)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (c0000000004324a8)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (c000000000443b90)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In mm/memory-failure.c (c000000000460910)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (c000000000469a2c)
Location: include/linux/mmzone.h:1345
Inline: False
Direct callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/page_idle.c (c00000000046bf58)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c00000000046cf78)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In mm/usercopy.c (c00000000046d3ec)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In fs/proc/kcore.c (c0000000005654e8)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In drivers/base/memory.c (c0000000009b1604)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/spi/spi.c (c000000000a89f00)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/edac/edac_mc.c (c000000000c0332c)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5b5e0)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
**Symbols:**

```
c000000000069120-c0000000000691b8: pfn_valid (STB_LOCAL)
c0000000003e3850-c0000000003e38e8: pfn_valid (STB_LOCAL)
c000000000469a2c-c000000000469ab8: pfn_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cefca)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/iomem.c (ffffffe0001d3638)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/vmstat.c (ffffffe0001f4548)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/compaction.c (ffffffe0001ff0dc)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/memory.c (ffffffe00020b63c)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/page_alloc.c (ffffffe00021bbba)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
Direct callers:
  - mm/page_alloc.c:zero_pfn_range
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/hugetlb.c (ffffffe00022c622)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/migrate.c (ffffffe00023e906)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/page_isolation.c (ffffffe00024b2ec)
Location: include/linux/mmzone.h:1345
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
Location: include/linux/mmzone.h:1345
Inline: False
Direct callers:
  - mm/cma.c:cma_init_reserved_areas
  - mm/cma.c:cma_init_reserved_areas
```
```
In mm/page_idle.c (ffffffe0002508f6)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffe000250f46)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In mm/usercopy.c (ffffffe00025122e)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In fs/proc/kcore.c (ffffffe0002e24fe)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In fs/proc/page.c (ffffffe0002e308c)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/spi/spi.c (ffffffe000618b2e)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/edac/edac_mc.c (ffffffe0006fcf14)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
**Symbols:**

```
ffffffe000219cc4-ffffffe000219d24: pfn_valid (STB_LOCAL)
ffffffe00024f4a2-ffffffe00024f4fc: pfn_valid (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107deed)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810805f5)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81084f3d)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81087131)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81104cc3)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81184ef5)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81217a22)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff8124b9d7)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8125dd0f)
Location: include/linux/mmzone.h:1345
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
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
Direct callers:
  - mm/page_alloc.c:zero_pfn_range
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/hugetlb.c (ffffffff8128913b)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/memory_hotplug.c (ffffffff81a687fd)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a6040)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812b1fd5)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c4005)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812c9fbb)
Location: include/linux/mmzone.h:1345
Inline: False
Direct callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/page_idle.c (ffffffff812cbac5)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812cc2b1)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813784f5)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81639205)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff816e2d83)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/edac/edac_mc.c (ffffffff8185d8c6)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818a1cef)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81103280-ffffffff811032e7: pfn_valid (STB_LOCAL)
ffffffff81273ba0-ffffffff81273c07: pfn_valid (STB_LOCAL)
ffffffff812c9fbb-ffffffff812ca01f: pfn_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106d199)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff8106f545)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81073c0d)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81075d01)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff810f5f63)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81178035)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff8120ac32)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff8123e977)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8125015f)
Location: include/linux/mmzone.h:1345
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
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
Direct callers:
  - mm/page_alloc.c:zero_pfn_range
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/hugetlb.c (ffffffff8127afdb)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/memory_hotplug.c (ffffffff81a252bd)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81297af0)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812a3365)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In mm/memory-failure.c (ffffffff812b5045)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812baffb)
Location: include/linux/mmzone.h:1345
Inline: False
Direct callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/page_idle.c (ffffffff812bc945)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812bd121)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81368fc5)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In drivers/base/memory.c (ffffffff816bd3c3)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d195)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81824e96)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8185d45f)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff810f4520-ffffffff810f4587: pfn_valid (STB_LOCAL)
ffffffff81265b10-ffffffff81265b77: pfn_valid (STB_LOCAL)
ffffffff812baffb-ffffffff812bb05f: pfn_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107de9d)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810805a5)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff81084eed)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810870e1)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81102f73)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81182cc5)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812157c2)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff81249777)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8125baaf)
Location: include/linux/mmzone.h:1345
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
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
Direct callers:
  - mm/page_alloc.c:zero_pfn_range
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/hugetlb.c (ffffffff81286f4b)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/memory_hotplug.c (ffffffff81ad4c0d)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a3e50)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812afde5)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In mm/memory-failure.c (ffffffff812c1e15)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812c7dcb)
Location: include/linux/mmzone.h:1345
Inline: False
Direct callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/page_idle.c (ffffffff812c98d5)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812ca0c1)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81375fc5)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff816382c5)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81667355)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff8170ff13)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c7f65)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818acef6)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff818f32df)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff81101530-ffffffff81101597: pfn_valid (STB_LOCAL)
ffffffff81271940-ffffffff812719a7: pfn_valid (STB_LOCAL)
ffffffff812c7dcb-ffffffff812c7e2f: pfn_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pfn_valid(long unsigned int pfn);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107ff8d)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810826c5)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In arch/x86/mm/mmap.c (ffffffff8108703d)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff81089211)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff8110e363)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
Direct callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811905e5)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812247c2)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/compaction.c (ffffffff81258ff7)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8126b492)
Location: include/linux/mmzone.h:1345
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
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
Direct callers:
  - mm/page_alloc.c:zero_pfn_range
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/hugetlb.c (ffffffff8129761b)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/memory_hotplug.c (ffffffff81ae10e8)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812b471e)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812c0125)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In mm/memory-failure.c (ffffffff812d28b5)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/cma.c (ffffffff812d8adb)
Location: include/linux/mmzone.h:1345
Inline: False
Direct callers:
  - mm/cma.c:cma_activate_area
  - mm/cma.c:cma_activate_area
```
```
In mm/page_idle.c (ffffffff812da5d5)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff812dadc1)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In fs/proc/kcore.c (ffffffff81389a75)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff81652605)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81681915)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/memory.c (ffffffff8172b073)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/base/memory.c:soft_offline_page_store
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2205)
Location: include/linux/mmzone.h:1345
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818c9146)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/ras/cec.c (ffffffff8191437f)
Location: include/linux/mmzone.h:1345
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff8110c900-ffffffff8110c967: pfn_valid (STB_LOCAL)
ffffffff812813a0-ffffffff81281407: pfn_valid (STB_LOCAL)
ffffffff812d8adb-ffffffff812d8b3f: pfn_valid (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
