# Function: <code>PageReserved</code>

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
In arch/x86/kernel/alternative.c (ffffffff8103677e)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff8181bb3a)
Location: include/linux/page-flags.h:222
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff8106b939)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In kernel/power/snapshot.c (ffffffff810d07b5)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/hugetlb.c (ffffffff811dbd7c)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff811e0181)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memory_hotplug.c (ffffffff811ef11a)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages_range
```
```
In mm/memory-failure.c (ffffffff81202794)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/proc/task_mmu.c (ffffffff81276fa6)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:can_gather_numa_stats
```
```
In drivers/base/memory.c (ffffffff81560fa7)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/firmware/memmap.c (ffffffff8181f6bc)
Location: include/linux/page-flags.h:222
Inline: True
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
In arch/x86/kernel/alternative.c (ffffffff81035970)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81895d5d)
Location: include/linux/page-flags.h:275
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff8106b819)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In kernel/power/snapshot.c (ffffffff810d52e3)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/hugetlb.c (ffffffff811fa134)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/mempolicy.c (ffffffff811fee72)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memory_hotplug.c (ffffffff8120e3c9)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages_range
```
```
In mm/memory-failure.c (ffffffff81226dee)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/proc/task_mmu.c (ffffffff812a5588)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/base/memory.c (ffffffff815b56f3)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/firmware/memmap.c (ffffffff81899dbb)
Location: include/linux/page-flags.h:275
Inline: True
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
In arch/x86/kernel/alternative.c (ffffffff8103569d)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff818ca47d)
Location: include/linux/page-flags.h:285
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff8106f433)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In kernel/power/snapshot.c (ffffffff810dbe85)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/hugetlb.c (ffffffff8120ac08)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff812106b1)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memory_hotplug.c (ffffffff81220409)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages_range
```
```
In mm/memory-failure.c (ffffffff81239396)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/proc/task_mmu.c (ffffffff812baed8)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/base/memory.c (ffffffff815e49d0)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/firmware/memmap.c (ffffffff818ce461)
Location: include/linux/page-flags.h:285
Inline: True
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
In arch/x86/kernel/alternative.c (ffffffff81033666)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff819019fa)
Location: include/linux/page-flags.h:285
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff8106eb86)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In kernel/power/snapshot.c (ffffffff810dacc5)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/hugetlb.c (ffffffff81215f13)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8121c09b)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memory_hotplug.c (ffffffff8122c327)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages_range
```
```
In mm/memory-failure.c (ffffffff812449ba)
Location: include/linux/page-flags.h:285
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812c8055)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/base/memory.c (ffffffff815f95a3)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
```
```
In drivers/firmware/memmap.c (ffffffff8190591d)
Location: include/linux/page-flags.h:285
Inline: True
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
In arch/x86/kernel/alternative.c (ffffffff81035994)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff8198ba2a)
Location: include/linux/page-flags.h:286
Inline: True
```
```
In arch/x86/mm/ioremap.c (ffffffff81073c8f)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In kernel/power/snapshot.c (ffffffff810e3441)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff811d99ee)
Location: include/linux/page-flags.h:286
Inline: True
```
```
In mm/hugetlb.c (ffffffff81230aaf)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff812374d7)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memory_hotplug.c (ffffffff81247af7)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages_range
```
```
In mm/memory-failure.c (ffffffff812648aa)
Location: include/linux/page-flags.h:286
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812eb913)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/base/memory.c (ffffffff81661e35)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
```
```
In drivers/firmware/memmap.c (ffffffff8198f990)
Location: include/linux/page-flags.h:286
Inline: True
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
In arch/x86/kernel/alternative.c (ffffffff81036904)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff819e8307)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff810766b8)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In kernel/power/snapshot.c (ffffffff810ed186)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff811fa2c3)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff82707ef6)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8125a9ff)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memory_hotplug.c (ffffffff8126b567)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages_range
```
```
In mm/memory-failure.c (ffffffff8128900d)
Location: include/linux/page-flags.h:293
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81318dd6)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/firmware/memmap.c (ffffffff819ec1fd)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In arch/x86/kernel/alternative.c (ffffffff81037b12)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81a238f7)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff8107cd08)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
```
```
In kernel/power/snapshot.c (ffffffff810f87e5)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff8120c9b1)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff828bf2c8)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8126e935)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memory_hotplug.c (ffffffff8127fdf7)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages_range
```
```
In mm/memory-failure.c (ffffffff8129df5d)
Location: include/linux/page-flags.h:304
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8132fe86)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/firmware/memmap.c (ffffffff81a2744d)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In arch/x86/kernel/alternative.c (ffffffff81039793)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81a93c25)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff8108098b)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In kernel/power/snapshot.c (ffffffff81100e27)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff81272d7f)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff828d8497)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8128a013)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memory_hotplug.c (ffffffff8129bd69)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages_range
```
```
In mm/memory-failure.c (ffffffff812b910d)
Location: include/linux/page-flags.h:337
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81357cbd)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/firmware/memmap.c (ffffffff81a97d10)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In arch/x86/kernel/alternative.c (ffffffff81039f64)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81acb505)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff8108165b)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In kernel/power/snapshot.c (ffffffff8110d287)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff81281bdf)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff828e093c)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81299b83)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff8129d759)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff812caffd)
Location: include/linux/page-flags.h:337
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136feed)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3154)
Location: include/linux/page-flags.h:337
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff81acf5de)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In arch/x86/kernel/alternative.c (ffffffff8103cbd2)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81bc3a0b)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff810885b4)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In kernel/power/snapshot.c (ffffffff81118441)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff812ae1b6)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff82cfd81c)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
```
```
In mm/mempolicy.c (ffffffff812cee6a)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff812d1418)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff813010ad)
Location: include/linux/page-flags.h:345
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813b7f18)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e05f)
Location: include/linux/page-flags.h:345
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff81bc801a)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In arch/x86/kernel/alternative.c (ffffffff8103d092)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81c3c93b)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff810887f4)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In kernel/power/snapshot.c (ffffffff81bdf8d8)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff812b9c36)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff82fea24d)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
```
```
In mm/mempolicy.c (ffffffff812da7aa)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff812dcf38)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff8130d0fd)
Location: include/linux/page-flags.h:354
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c9dd8)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ace9f)
Location: include/linux/page-flags.h:354
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff81c40d54)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In arch/x86/kernel/alternative.c (ffffffff8103e8a2)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81c2ee17)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81089498)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In kernel/power/snapshot.c (ffffffff81bd17fb)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff812c54c5)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff831f4bc2)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
```
```
In mm/mempolicy.c (ffffffff812e201a)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff812e472c)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff813136bd)
Location: include/linux/page-flags.h:354
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813d1438)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189357d)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
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
In drivers/firmware/memmap.c (ffffffff81c32cb7)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In arch/x86/kernel/alternative.c (ffffffff81044612)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81d4d518)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81098928)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In kernel/power/snapshot.c (ffffffff81caa453)
Location: include/linux/page-flags.h:368
Inline: True
```
```
In mm/page_alloc.c (ffffffff81309a2e)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff832dae8c)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - mm/hugetlb.c:gather_bootmem_prealloc
```
```
In mm/mempolicy.c (ffffffff813290fa)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff8132ba3c)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/sparse-vmemmap.c (ffffffff8132c6f8)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
```
In mm/memory-failure.c (ffffffff813603b9)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff81422938)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8192711e)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
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
In drivers/firmware/memmap.c (ffffffff81d516c8)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In arch/x86/kernel/alternative.c (ffffffff8104cc5e)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81f1d222)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff810ab554)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In kernel/power/snapshot.c (ffffffff81e5a86b)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff81372213)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
```
```
In mm/hugetlb.c (ffffffff83490be0)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff8139835d)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff8139b6da)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/sparse-vmemmap.c (ffffffff8139c776)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_free
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/memory-failure.c (ffffffff813dba4c)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_isolation.c (ffffffff813ddcc5)
Location: include/linux/page-flags.h:518
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81499a48)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79528)
Location: include/linux/page-flags.h:518
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff81f21bcc)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In arch/x86/kernel/alternative.c (ffffffff81059070)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff820c5390)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff810c598c)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In kernel/power/snapshot.c (ffffffff81185d19)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff813efa43)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413d60)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/mempolicy.c (ffffffff81418119)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff8141b71a)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff8146226f)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_isolation.c (ffffffff81464955)
Location: include/linux/page-flags.h:497
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152dc78)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/firmware/memmap.c (ffffffff820cc29a)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In arch/x86/kernel/alternative.c (ffffffff8105a61e)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff821493f0)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff810c910f)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In kernel/power/snapshot.c (ffffffff81196ee9)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff814235c0)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
```
```
In mm/hugetlb_vmemmap.c (ffffffff81447460)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/sparse.c (ffffffff8144ecba)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff81498446)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_isolation.c (ffffffff8149a455)
Location: include/linux/page-flags.h:490
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff815660d0)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/firmware/memmap.c (ffffffff8215054a)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In arch/x86/kernel/alternative.c (ffffffff8106186f)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff8222beb0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff810d0dfb)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In kernel/power/snapshot.c (ffffffff811a599b)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff814504f0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480419)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:free_vmemmap_page_list
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/sparse.c (ffffffff81488865)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff814c7a1a)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_isolation.c (ffffffff814c9bd6)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159e0bc)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/firmware/memmap.c (ffffffff8223338a)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In virt/kvm/kvm_main.c (ffff8000100bb598)
Location: include/linux/page-flags.h:337
Inline: True
```
```
In mm/page_alloc.c (ffff80001031a328)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffff800011459bcc)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_gigantic_page
```
```
In mm/mempolicy.c (ffff80001033877c)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffff80001033c914)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffff80001036e9f0)
Location: include/linux/page-flags.h:337
Inline: True
```
```
In fs/proc/task_mmu.c (ffff800010439ce0)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/firmware/memmap.c (ffff800010da11c4)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03bff00)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:saveable_highmem_page
```
```
In mm/page_alloc.c (c05349b4)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In drivers/firmware/memmap.c (c15be58c)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/pgtable.c (c0000000000878d0)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:maybe_pte_to_page
```
```
In arch/powerpc/mm/init_64.c (c000000000088e18)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/powerpc/mm/init_64.c:vmemmap_free
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008cfc8)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_do_lazy_icache
```
```
In mm/page_alloc.c (c0000000003ed438)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (c00000000138384c)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (c000000000413504)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (c000000000417910)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (c00000000045f6cc)
Location: include/linux/page-flags.h:337
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054d598)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
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
In mm/page_alloc.c (ffffffe00021fbec)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffe000018004)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
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
In arch/x86/kernel/alternative.c (ffffffff8103a0c4)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81a6a375)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff8108065b)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In kernel/power/snapshot.c (ffffffff811054a7)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff8127a22f)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff828c97f0)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81292163)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff81295d39)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff812c35dd)
Location: include/linux/page-flags.h:337
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813684cd)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/firmware/memmap.c (ffffffff81a6e44e)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In arch/x86/kernel/alternative.c (ffffffff810299a0)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81a26837)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff8106f5ab)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In kernel/power/snapshot.c (ffffffff810f6747)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff8126c11f)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff828c1f15)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81283cdd)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff81287949)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff812b461d)
Location: include/linux/page-flags.h:337
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8135980d)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d204)
Location: include/linux/page-flags.h:337
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff81a2a856)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In arch/x86/kernel/alternative.c (ffffffff81039f24)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81ad6785)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff8108060b)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In kernel/power/snapshot.c (ffffffff81103757)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff81277fcf)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff828dc570)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8128ff73)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff81293b49)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff812c13ed)
Location: include/linux/page-flags.h:337
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81365f9d)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c7fd4)
Location: include/linux/page-flags.h:337
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff81ada85e)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
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
In arch/x86/kernel/alternative.c (ffffffff8103af24)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81ae2c45)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff8108272b)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
```
In kernel/power/snapshot.c (ffffffff8110eb47)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff81287bbf)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff828e198c)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8129f3a6)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff812a39a9)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-failure.c (ffffffff812d1ead)
Location: include/linux/page-flags.h:337
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81379b88)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2274)
Location: include/linux/page-flags.h:337
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff81ae6d14)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
</details>
</li>
</ul>

## Differences
