# Function: <code>adjust_managed_page_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81191750)
Location: mm/page_alloc.c:5779
Inline: False
Direct callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/hugetlb.c:hugetlb_init
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/balloon.c:balloon_retrieve
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:free_xenballooned_pages
```
**Symbols:**

```
ffffffff81191750-ffffffff811917b7: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a5f70)
Location: mm/page_alloc.c:6406
Inline: False
Direct callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff811a5f70-ffffffff811a5fd2: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b62f0)
Location: mm/page_alloc.c:6445
Inline: False
Direct callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff811b62f0-ffffffff811b6352: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811be1c0)
Location: mm/page_alloc.c:6740
Inline: False
Direct callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff811be1c0-ffffffff811be222: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d2f60)
Location: mm/page_alloc.c:6753
Inline: False
Direct callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff811d2f60-ffffffff811d2fc2: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f4f40)
Location: mm/page_alloc.c:6921
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/hugetlb.c:hugetlb_init
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff811f4f40-ffffffff811f4fa2: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812066b0)
Location: mm/page_alloc.c:7228
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/hugetlb.c:hugetlb_init
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff812066b0-ffffffff812066ee: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126c660)
Location: mm/page_alloc.c:7430
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/hugetlb.c:hugetlb_init
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__online_page_increment_counters
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8126c660-ffffffff8126c69e: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127b470)
Location: mm/page_alloc.c:7460
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/hugetlb.c:hugetlb_init
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__online_page_increment_counters
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8127b470-ffffffff8127b4ae: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812ad610)
Location: mm/page_alloc.c:7489
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:increase_reservation
```
**Symbols:**

```
ffffffff812ad610-ffffffff812ad649: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b8ff0)
Location: mm/page_alloc.c:7635
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:increase_reservation
```
**Symbols:**

```
ffffffff812b8ff0-ffffffff812b9029: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812be4c0)
Location: mm/page_alloc.c:7853
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:put_page_bootmem
  - mm/hugetlb.c:gather_bootmem_prealloc
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff812be4c0-ffffffff812be4f9: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81300c00)
Location: mm/page_alloc.c:8095
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/memory_hotplug.c:offline_pages
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/bootmem_info.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81300c00-ffffffff81300c60: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813680b0)
Location: mm/page_alloc.c:8281
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/memory_hotplug.c:offline_pages
  - mm/hugetlb.c:hugetlb_init
  - mm/bootmem_info.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff813680b0-ffffffff8136811b: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e4100)
Location: mm/page_alloc.c:8455
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:crash_shrink_memory
  - mm/page_alloc.c:free_reserved_area
  - mm/memory_hotplug.c:offline_pages
  - mm/hugetlb.c:hugetlb_init
  - mm/bootmem_info.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff813e4100-ffffffff813e416b: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81418e50)
Location: mm/page_alloc.c:5518
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:__crash_shrink_memory
  - mm/page_alloc.c:free_reserved_area
  - mm/memory_hotplug.c:offline_pages
  - mm/hugetlb.c:hugetlb_init
  - mm/bootmem_info.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81418e50-ffffffff81418ebb: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff814459a0)
Location: mm/page_alloc.c:5660
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:__crash_shrink_memory
  - mm/page_alloc.c:free_reserved_area
  - mm/memory_hotplug.c:offline_pages
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/bootmem_info.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff814459a0-ffffffff81445a0b: adjust_managed_page_count (STB_GLOBAL)
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
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010313920)
Location: mm/page_alloc.c:7460
Inline: False
Direct callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/hugetlb.c:hugetlb_init
  - mm/memory_hotplug.c:__online_page_increment_counters
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffff800010313920-ffff8000103139c4: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052dfc8)
Location: mm/page_alloc.c:7460
Inline: True
Direct callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
c052dfc8-c052e064: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ecc84)
Location: mm/page_alloc.c:7460
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
Direct callers:
  - arch/powerpc/kernel/crash_dump.c:crash_free_reserved_phys_range
  - arch/powerpc/kernel/fadump.c:fadump_release_reserved_area
  - arch/powerpc/kernel/fadump.c:fadump_setup_cpu_notes_buf
  - arch/powerpc/mm/init_64.c:vmemmap_free
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/hugetlb.c:hugetlb_init
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__online_page_increment_counters
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
c0000000003e3a10-c0000000003e3a78: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021f6ce)
Location: mm/page_alloc.c:7460
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
Direct callers:
  - mm/hugetlb.c:hugetlb_init
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffe000219e9e-ffffffe000219eec: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81273ac0)
Location: mm/page_alloc.c:7460
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/hugetlb.c:hugetlb_init
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__online_page_increment_counters
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81273ac0-ffffffff81273afe: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81265a30)
Location: mm/page_alloc.c:7460
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/hugetlb.c:hugetlb_init
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__online_page_increment_counters
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff81265a30-ffffffff81265a6e: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81271860)
Location: mm/page_alloc.c:7460
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/hugetlb.c:hugetlb_init
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__online_page_increment_counters
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81271860-ffffffff8127189e: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page *page, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812812c0)
Location: mm/page_alloc.c:7460
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:free_pagetable
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/hugetlb.c:hugetlb_init
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__online_page_increment_counters
  - mm/memory_hotplug.c:put_page_bootmem
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff812812c0-ffffffff812812fe: adjust_managed_page_count (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
