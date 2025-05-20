# Function: <code>__pfn_to_section</code>

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
In mm/page_alloc.c (ffffffff81194005)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - mm/page_alloc.c:get_pfnblock_flags_mask
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff8181f014)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/memory_hotplug.c (ffffffff811ef19d)
Location: include/linux/mmzone.h:1121
Inline: True
Inline callers:
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
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
In mm/page_alloc.c (ffffffff811a8d31)
Location: include/linux/mmzone.h:1193
Inline: True
Inline callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff81899523)
Location: include/linux/mmzone.h:1193
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/memory_hotplug.c (ffffffff8120e6bb)
Location: include/linux/mmzone.h:1193
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
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
In mm/page_alloc.c (ffffffff811b92ce)
Location: include/linux/mmzone.h:1171
Inline: True
Inline callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff818cdbdb)
Location: include/linux/mmzone.h:1171
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/memory_hotplug.c (ffffffff812206fb)
Location: include/linux/mmzone.h:1171
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
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
In mm/page_alloc.c (ffffffff811c134d)
Location: include/linux/mmzone.h:1210
Inline: True
Inline callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff81905076)
Location: include/linux/mmzone.h:1210
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/memory_hotplug.c (ffffffff8122cb4a)
Location: include/linux/mmzone.h:1210
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
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
In mm/page_alloc.c (ffffffff811d431d)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff8198f038)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/memory_hotplug.c (ffffffff81248384)
Location: include/linux/mmzone.h:1223
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
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
In mm/page_alloc.c (ffffffff811f5d39)
Location: include/linux/mmzone.h:1230
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff819eb8f6)
Location: include/linux/mmzone.h:1230
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/memory_hotplug.c (ffffffff819e5fc0)
Location: include/linux/mmzone.h:1230
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
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
In mm/page_alloc.c (ffffffff812079d9)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff81a26b8c)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/memory_hotplug.c (ffffffff81a21367)
Location: include/linux/mmzone.h:1238
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:__add_pages
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
In mm/page_alloc.c (ffffffff8126dcca)
Location: include/linux/mmzone.h:1311
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff81a9730a)
Location: include/linux/mmzone.h:1311
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffffffff81a91a17)
Location: include/linux/mmzone.h:1311
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
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
In mm/page_alloc.c (ffffffff8127caea)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff81acebec)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffffffff81ac91b7)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
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
In mm/page_alloc.c (ffffffff812b1ca6)
Location: include/linux/mmzone.h:1295
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff81bc750f)
Location: include/linux/mmzone.h:1295
Inline: True
Inline callers:
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:clear_subsection_map
```
```
In mm/memory_hotplug.c (ffffffff812e08eb)
Location: include/linux/mmzone.h:1295
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:__remove_pages
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
In mm/page_alloc.c (ffffffff812c026b)
Location: include/linux/mmzone.h:1333
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff81c4023b)
Location: include/linux/mmzone.h:1333
Inline: True
Inline callers:
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:clear_subsection_map
```
```
In mm/memory_hotplug.c (ffffffff812ec643)
Location: include/linux/mmzone.h:1333
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
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
In mm/page_alloc.c (ffffffff812c59e5)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff81bda462)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - mm/memory_hotplug.c:section_taint_zone_device
  - mm/memory_hotplug.c:__remove_pages
```
```
In mm/sparse.c (ffffffff81c323b0)
Location: include/linux/mmzone.h:1403
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
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
In mm/page_alloc.c (ffffffff8130a100)
Location: include/linux/mmzone.h:1440
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
In mm/memory_hotplug.c (ffffffff8130bdbf)
Location: include/linux/mmzone.h:1440
Inline: True
Inline callers:
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:section_taint_zone_device
  - mm/memory_hotplug.c:__remove_pages
```
```
In mm/sparse.c (ffffffff81d50dac)
Location: include/linux/mmzone.h:1440
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
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
In arch/x86/mm/init_64.c (ffffffff810a92ae)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
```
```
In arch/x86/mm/ioremap.c (ffffffff810ab4f5)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810aca7e)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810add82)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81156dd3)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fca80)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff812ebb24)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/compaction.c (ffffffff8132fd26)
Location: include/linux/mmzone.h:1486
Inline: True
```
```
In mm/memory.c (ffffffff81348bed)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
```
```
In mm/vmalloc.c (ffffffff81360308)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff81372d8c)
Location: include/linux/mmzone.h:1486
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
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:section_taint_zone_device
  - mm/memory_hotplug.c:__remove_pages
```
```
In mm/hugetlb.c (ffffffff813881ce)
Location: include/linux/mmzone.h:1486
Inline: True
```
```
In mm/sparse.c (ffffffff81f20fbc)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
```
In mm/huge_memory.c (ffffffff813c09d5)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
```
```
In mm/memory-failure.c (ffffffff813dd1a1)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff834940df)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff814aed9f)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e59c)
Location: include/linux/mmzone.h:1486
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd0f4)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff819a1fe9)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a794c5)
Location: include/linux/mmzone.h:1486
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81b81f77)
Location: include/linux/mmzone.h:1486
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81bdf13d)
Location: include/linux/mmzone.h:1486
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
In arch/x86/mm/ioremap.c (ffffffff810c5935)
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810c6b57)
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810c7fc9)
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81187aa9)
Location: include/linux/mmzone.h:1825
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
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff81355d64)
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff81378296)
Location: include/linux/mmzone.h:1825
Inline: True
```
```
In mm/compaction.c (ffffffff813a68cf)
Location: include/linux/mmzone.h:1825
Inline: True
```
```
In mm/memory.c (ffffffff813bd942)
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/vmalloc.c (ffffffff813dc407)
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff813f050c)
Location: include/linux/mmzone.h:1825
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
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In mm/sparse.c (ffffffff820cab9a)
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff81463fec)
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff83ec860c)
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff8154544f)
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7a9c)
Location: include/linux/mmzone.h:1825
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30540)
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff81b13f59)
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/edac/edac_mc.c (ffffffff81d208a9)
Location: include/linux/mmzone.h:1825
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81d8a713)
Location: include/linux/mmzone.h:1825
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
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810ca2d9)
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810cb705)
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff81198c39)
Location: include/linux/mmzone.h:1950
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
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff813873f4)
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813abae6)
Location: include/linux/mmzone.h:1950
Inline: True
```
```
In mm/mm_init.c (ffffffff836e04ef)
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff813da121)
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff813f2642)
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/vmalloc.c (ffffffff81410d10)
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff8142409c)
Location: include/linux/mmzone.h:1950
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
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
```
In mm/sparse.c (ffffffff8144efc5)
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff81499aa4)
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff836ed66b)
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff8157d02f)
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a301ac)
Location: include/linux/mmzone.h:1950
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79d4f)
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff81b62c89)
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/edac/edac_mc.c (ffffffff81d89aa6)
Location: include/linux/mmzone.h:1950
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81df8d13)
Location: include/linux/mmzone.h:1950
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
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810d2741)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810d3d64)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In kernel/power/snapshot.c (ffffffff811a7a90)
Location: include/linux/mmzone.h:1961
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
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/iomem.c (ffffffff813b0d77)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In mm/vmscan.c (ffffffff813d6206)
Location: include/linux/mmzone.h:1961
Inline: True
```
```
In mm/mm_init.c (ffffffff83912d3d)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/compaction.c (ffffffff81403e31)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/memory.c (ffffffff8141d342)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In mm/vmalloc.c (ffffffff8143ef2a)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff81449b4d)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff8222a04c)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
```
In mm/sparse.c (ffffffff81488b85)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff814c91fa)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
```
```
In mm/bootmem_info.c (ffffffff83920673)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff815b597f)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b30c)
Location: include/linux/mmzone.h:1961
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc1b5)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/base/node.c (ffffffff81bb6799)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/edac/edac_mc.c (ffffffff81e410ec)
Location: include/linux/mmzone.h:1961
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81eaf3a3)
Location: include/linux/mmzone.h:1961
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
In mm/page_alloc.c (ffff800010314608)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffff800010da07b4)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffff800010d9ce84)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
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
In mm/page_alloc.c (c0000000003e5c98)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (c000000000eed3e0)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (c00000000042fd5c)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021aff6)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
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
In mm/page_alloc.c (ffffffff8127513a)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff81a6da5c)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffffffff81a68027)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
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
In mm/page_alloc.c (ffffffff812670aa)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff81a29fa3)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffffffff81a24ae7)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
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
In mm/page_alloc.c (ffffffff81272eda)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff81ad9e6c)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffffffff81ad4437)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
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
In mm/page_alloc.c (ffffffff8128299a)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
  - mm/page_alloc.c:get_pfnblock_flags_mask
```
```
In mm/sparse.c (ffffffff81ae6322)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
```
```
In mm/memory_hotplug.c (ffffffff81ae0917)
Location: include/linux/mmzone.h:1318
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
```
</details>
</li>
</ul>

## Differences
