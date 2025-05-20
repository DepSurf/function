# Function: <code>set_page_count</code>

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
In mm/page_alloc.c (ffffffff81191739)
Location: mm/internal.h:39
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff811da2ca)
Location: mm/internal.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_node
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
```
```
In mm/page_isolation.c (ffffffff81203be5)
Location: mm/internal.h:39
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In arch/x86/mm/init_64.c (ffffffff81895da7)
Location: include/linux/page_ref.h:74
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81114f0d)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811a9201)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff811fe0e4)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_node
```
```
In mm/memory_hotplug.c (ffffffff8120ecbe)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815174de)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff818ca4c7)
Location: include/linux/page_ref.h:74
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8111c625)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811b9757)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff8120ebb4)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_node
```
```
In mm/memory_hotplug.c (ffffffff81220cee)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff8154390e)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81901a46)
Location: include/linux/page_ref.h:74
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8111e555)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811c17d7)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff8121530d)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (ffffffff8122c5fe)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815577bc)
Location: include/linux/page_ref.h:74
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff8198ba76)
Location: include/linux/page_ref.h:75
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81129cb5)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811d5bf7)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff8122fe50)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81247dde)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815bb8fa)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff819e8366)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81137c00)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811f7033)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff812522b4)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (ffffffff8126b72c)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815f3e53)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81a23956)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81143420)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812093d3)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:memblock_free_pages
  - mm/page_alloc.c:memblock_free_pages
  - mm/page_alloc.c:memblock_free_pages
```
```
In mm/hugetlb.c (ffffffff81266522)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (ffffffff8127ffbc)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff8160ecb8)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81a93c82)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8114e762)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812728ef)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff812817be)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (ffffffff8129bfee)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81642a7b)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81acb562)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8115a472)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff8128174f)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff81290b1e)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812abd5e)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81665023)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81bc3a64)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8116b242)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812b3c39)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812c3c62)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812e1651)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81713fcb)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - drivers/xen/balloon.c:increase_reservation
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
In arch/x86/mm/init_64.c (ffffffff81c3c98d)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81167982)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812bf6ed)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812cf8a8)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812ec5a1)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81730f9b)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - drivers/xen/balloon.c:increase_reservation
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
In arch/x86/mm/init_64.c (ffffffff81c2ee69)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81168712)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812c4d6d)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/memory_hotplug.c (ffffffff812c6e41)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/hugetlb.c (ffffffff812d60f8)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:remove_hugetlb_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In drivers/xen/balloon.c (ffffffff81714c9e)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81d4d56a)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8118e442)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff8130921d)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:split_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff81325506)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:remove_hugetlb_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/bootmem_info.c (ffffffff8136cb71)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81791bc4)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
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
In arch/x86/mm/init_64.c (ffffffff81f1d274)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff811bd9f0)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff81371719)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:split_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff81389adb)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__remove_hugetlb_page
  - mm/hugetlb.c:__destroy_compound_gigantic_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memremap.c (ffffffff813e7c51)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In mm/bootmem_info.c (ffffffff813eaf0b)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff818ca846)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
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
In arch/x86/mm/init_64.c (ffffffff820c53da)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff811ffb24)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_shrink_memory
```
```
In mm/page_alloc.c (ffffffff813eee49)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:__init_zone_device_page
  - mm/page_alloc.c:__init_zone_device_page
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:split_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff8140a942)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memremap.c (ffffffff8146f84a)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:free_zone_device_page
```
```
In mm/bootmem_info.c (ffffffff8147310b)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81a1b3f2)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
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
In arch/x86/mm/init_64.c (ffffffff8214943a)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff812138b5)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
```
```
In mm/mm_init.c (ffffffff8214bfbc)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
```
```
In mm/page_alloc.c (ffffffff81422c19)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:split_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff81438ef9)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
```
```
In mm/memremap.c (ffffffff814a402a)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:free_zone_device_page
```
```
In mm/bootmem_info.c (ffffffff814a787b)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81a64587)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
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
In arch/x86/mm/init_64.c (ffffffff8222befa)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8122b814)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
```
```
In mm/mm_init.c (ffffffff8222eb52)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
```
```
In mm/page_alloc.c (ffffffff8144faf9)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:split_page
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff814728c2)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
```
```
In mm/memremap.c (ffffffff814d4eda)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/memremap.c:zone_device_page_init
  - mm/memremap.c:free_zone_device_page
```
```
In mm/bootmem_info.c (ffffffff814d88ab)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81ab6de7)
Location: include/linux/page_ref.h:97
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
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
In kernel/kexec_core.c (ffff8000101c9afc)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffff800010319be4)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffff80001032e1bc)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (ffff80001034de20)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffff80001082ee14)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In kernel/kexec_core.c (c0410b0c)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (c0534590)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
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
In arch/powerpc/kernel/crash_dump.c (c00000000004be2c)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/powerpc/kernel/crash_dump.c:crash_free_reserved_phys_range
```
```
In arch/powerpc/kernel/fadump.c (c00000000004c17c)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/powerpc/kernel/fadump.c:fadump_release_reserved_area
```
```
In arch/powerpc/mm/init_64.c (c000000000088e78)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/powerpc/mm/init_64.c:vmemmap_free
```
```
In kernel/kexec_core.c (c000000000232590)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (c0000000003ecc74)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (c000000000406bec)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (c00000000042d350)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
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
In mm/page_alloc.c (ffffffe00021f6ae)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffe00022c43e)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
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
In arch/x86/mm/init_64.c (ffffffff81a6a3d2)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81152a92)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff81279d9f)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff812890fe)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812a433e)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff8162abb6)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81a26894)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81145d72)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff8126bc8f)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff8127af9e)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81295e0e)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
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
In arch/x86/mm/init_64.c (ffffffff81ad67e2)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81150942)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff81277b3f)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff81286f0e)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812a214e)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81658e63)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81ae2ca2)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8115d762)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff8128772f)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff812975de)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812b23de)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81673473)
Location: include/linux/page_ref.h:75
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
</details>
</li>
</ul>

## Differences
