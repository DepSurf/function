# Function: <code>clear_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/mm/init.c:alloc_low_pages
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/swap.c:swsusp_check
  - kernel/kexec_core.c:kimage_load_segment
  - mm/page_alloc.c:get_page_from_freelist
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/huge_memory.c:khugepaged
  - fs/libfs.c:simple_readpage
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
  - fs/dax.c:dax_do_io
  - fs/dax.c:dax_do_io
  - fs/dax.c:dax_zero_page_range
  - fs/dax.c:dax_clear_blocks
  - fs/fuse/dev.c:fuse_copy_page
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/events/events_fifo.c:init_control_block
```
**Symbols:**

```
ffffffff813f5d40-ffffffff813f5d50: clear_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/mm/init.c:alloc_low_pages
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/swap.c:swsusp_check
  - kernel/kexec_core.c:kimage_load_segment
  - mm/page_alloc.c:get_page_from_freelist
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:wp_page_copy
  - mm/khugepaged.c:collapse_huge_page
  - fs/libfs.c:simple_readpage
  - fs/dax.c:dax_fault
  - fs/fuse/dev.c:fuse_copy_page
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/block/brd.c:brd_make_request
```
**Symbols:**

```
ffffffff8143c8d0-ffffffff8143c8e0: clear_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
  - arch/x86/mm/init.c:alloc_low_pages
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/swap.c:swsusp_check
  - kernel/kexec_core.c:kimage_load_segment
  - mm/page_alloc.c:get_page_from_freelist
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:wp_page_copy
  - mm/khugepaged.c:khugepaged
  - fs/libfs.c:simple_readpage
  - fs/dax.c:dax_iomap_fault
  - fs/fuse/dev.c:fuse_copy_page
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/events/events_fifo.c:init_control_block
```
**Symbols:**

```
ffffffff814598b0-ffffffff814598c0: clear_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clear_page(void *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8209d31a)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024a7b)
Location: arch/x86/include/asm/page_64.h:42
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105dfc6)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff818fe3a3)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff810dc905)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/power/swap.c (ffffffff810df97c)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
```
```
In kernel/kexec_core.c (ffffffff8111e28e)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/page_alloc.c (ffffffff811c25e9)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff811d8d0e)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff811f89e3)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:wp_page_copy
```
```
In mm/khugepaged.c (ffffffff8123865e)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/libfs.c (ffffffff8127d242)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/dax.c (ffffffff812ab4ce)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/fuse/dev.c (ffffffff8136d522)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/balloon.c (ffffffff81556f75)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff8155bc24)
Location: arch/x86/include/asm/page_64.h:42
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
**Symbols:**

```
ffffffff81024a7b-ffffffff81024a86: clear_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clear_page(void *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff826a3508)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff8101bbad)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102561b)
Location: arch/x86/include/asm/page_64.h:43
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061c8e)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff819884d3)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff810e4b25)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/power/swap.c (ffffffff810e7c0c)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
```
```
In kernel/kexec_core.c (ffffffff81129a7e)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/page_alloc.c (ffffffff811d7061)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff811edf57)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff81210c8d)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:wp_page_copy
```
```
In mm/khugepaged.c (ffffffff81259b31)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/libfs.c (ffffffff8129fce2)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/dax.c (ffffffff812cee14)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/fuse/dev.c (ffffffff81391c97)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/balloon.c (ffffffff815baf83)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff815bff44)
Location: arch/x86/include/asm/page_64.h:43
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
**Symbols:**

```
ffffffff8102561b-ffffffff81025626: clear_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clear_page(void *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff826cc4e9)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff8101c571)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102635c)
Location: arch/x86/include/asm/page_64.h:47
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064d41)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff819e4e61)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff810ec6ab)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (ffffffff810ef053)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
```
```
In kernel/kexec_core.c (ffffffff811377c2)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/page_alloc.c (ffffffff811f84e0)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff8120f3d9)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff812316ab)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
```
```
In mm/khugepaged.c (ffffffff8127c48d)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/libfs.c (ffffffff812c65a9)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/dax.c (ffffffff812f961b)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
```
```
In fs/fuse/dev.c (ffffffff813c0cb0)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In drivers/xen/balloon.c (ffffffff815f361a)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff815f8562)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
**Symbols:**

```
ffffffff8102635c-ffffffff81026367: clear_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clear_page(void *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff828824f4)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff8101c0a0)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025f0c)
Location: arch/x86/include/asm/page_64.h:47
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106a9b1)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff81a2002e)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff810f7d4b)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (ffffffff810fa6e3)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
```
```
In kernel/kexec_core.c (ffffffff81142f62)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
```
```
In mm/page_alloc.c (ffffffff8120a8d7)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff81221c0b)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff81244e7b)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
```
```
In mm/khugepaged.c (ffffffff8128fbd4)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/libfs.c (ffffffff812db7a9)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/dax.c (ffffffff8130d7bc)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
```
```
In fs/fuse/dev.c (ffffffff813da010)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff813e9f01)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In drivers/xen/grant-table.c (ffffffff8160cd25)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8160e699)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff816133b2)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/scsi/sd.c (ffffffff817231af)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
**Symbols:**

```
ffffffff81025f0c-ffffffff81025f17: clear_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clear_page(void *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82899481)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff8101db10)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027c0c)
Location: arch/x86/include/asm/page_64.h:47
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e6cf)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff81a907be)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff81100349)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (ffffffff81102d5d)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
```
```
In kernel/kexec_core.c (ffffffff8114e2b0)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/shmem.c (ffffffff81231474)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff81256e39)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
```
```
In mm/page_alloc.c (ffffffff8126d4da)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812aac6d)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/libfs.c (ffffffff812f9e39)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/dax.c (ffffffff813359dd)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
```
```
In fs/fuse/dev.c (ffffffff814062bf)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff8141608b)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In drivers/xen/grant-table.c (ffffffff816419c8)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8164241e)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff816472a2)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/scsi/sd.c (ffffffff817605fe)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
**Symbols:**

```
ffffffff81027c0c-ffffffff81027c17: clear_page (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff8289c481)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff8101e4b0)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7282)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106fc7f)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff81ac7b3e)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff8110c7a9)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (ffffffff8110f1ad)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
```
```
In kernel/kexec_core.c (ffffffff81159fc0)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/shmem.c (ffffffff8123f534)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff812653c9)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
```
```
In mm/page_alloc.c (ffffffff8127c01a)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812bc23e)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff8130ba69)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/dax.c (ffffffff813495dd)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
```
```
In fs/fuse/dev.c (ffffffff81420e1f)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff8142fe5d)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In drivers/xen/grant-table.c (ffffffff81662fd8)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff816649e7)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff81669742)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/scsi/sd.c (ffffffff8178458f)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
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
In arch/x86/kernel/head64.c (ffffffff82cc2556)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff81020960)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82ccc225)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:check_pt_base
  - arch/x86/xen/mmu_pv.c:check_pt_base
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810770f1)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff81bc0651)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff81117a0a)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (ffffffff8111a39d)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/kexec_core.c (ffffffff8116a7ec)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_normal_segment
```
```
In mm/shmem.c (ffffffff8126cd76)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff812957a7)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
```
```
In mm/page_alloc.c (ffffffff812ae34d)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812f1776)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_copy
```
```
In fs/libfs.c (ffffffff81345999)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/dax.c (ffffffff8138e8af)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/fuse/dev.c (ffffffff8146feb1)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff8147feaa)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/xen/grant-table.c (ffffffff8171350c)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81714567)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff81719552)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/scsi/sd.c (ffffffff8184437f)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
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
In arch/x86/kernel/head64.c (ffffffff82fae5ec)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff810213a0)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8063)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:check_pt_base
  - arch/x86/xen/mmu_pv.c:check_pt_base
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077721)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff81c396d1)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff81113e4a)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_or_poison_free_page
```
```
In kernel/power/swap.c (ffffffff81115ded)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/kexec_core.c (ffffffff81166f2c)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_normal_segment
```
```
In mm/shmem.c (ffffffff8127781c)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff812a0697)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
```
```
In mm/page_alloc.c (ffffffff812b9f66)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812fdccb)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81351fe9)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/dax.c (ffffffff813a000d)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/fuse/dev.c (ffffffff8148a74e)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff8149b587)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/xen/grant-table.c (ffffffff817303fc)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81730c47)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff81736702)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/scsi/sd.c (ffffffff81854698)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
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
In arch/x86/kernel/head64.c (ffffffff831b85ec)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff81023742)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff831c3b5a)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810781b1)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff81c2bb71)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff81114757)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/power/swap.c (ffffffff811164dd)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/kexec_core.c (ffffffff81167ccc)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_normal_segment
```
```
In mm/shmem.c (ffffffff8127c67c)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff812a5fd8)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
```
```
In mm/page_alloc.c (ffffffff812bf409)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff81304e41)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81358cf9)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/dax.c (ffffffff813a75a3)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/fuse/dev.c (ffffffff8149021d)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff814a0797)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/xen/grant-table.c (ffffffff81713f9c)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff817147d3)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a152)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/scsi/sd.c (ffffffff81838238)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
  - drivers/scsi/sd.c:sd_setup_unmap_cmnd
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
In arch/x86/kernel/head64.c (ffffffff832986bf)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff810279e2)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff832a46c1)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810859c1)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff81d4a24c)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff81134897)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/power/swap.c (ffffffff81136792)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/kexec_core.c (ffffffff8118d5ec)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_normal_segment
```
```
In mm/shmem.c (ffffffff812ba88c)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff812e7458)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
```
```
In mm/page_alloc.c (ffffffff8130157c)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
```
```
In mm/khugepaged.c (ffffffff8134ebd4)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In mm/secretmem.c (ffffffff81366392)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_freepage
```
```
In fs/libfs.c (ffffffff813a7359)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/dax.c (ffffffff813f4d05)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/fuse/dev.c (ffffffff814e7cd1)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff814f8665)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/xen/grant-table.c (ffffffff817909d7)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81791613)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff81798781)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/scsi/sd.c (ffffffff818c5172)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
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
In arch/x86/kernel/head64.c (ffffffff8344672f)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff8102bdba)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83453a16)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095da1)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff81f1985c)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff81156a47)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/power/swap.c (ffffffff81158c69)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/kexec_core.c (ffffffff811bcac2)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_normal_segment
```
```
In mm/shmem.c (ffffffff81317f22)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff81348629)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:wp_page_copy
```
```
In mm/page_alloc.c (ffffffff813709f8)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff813c5836)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff81467888)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/fuse/dev.c (ffffffff815760d3)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff81588a22)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/xen/grant-table.c (ffffffff818c9814)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff818ca0c9)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d1a4c)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/scsi/sd.c (ffffffff81a11c3e)
Location: arch/x86/include/asm/page_64.h:48
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
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
In arch/x86/kernel/head64.c (ffffffff83e5f835)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff81032c76)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e70fdc)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810aba01)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff820c142c)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff81187697)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/power/swap.c (ffffffff8118adc9)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/kexec_core.c (ffffffff811fea54)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_normal_segment
```
```
In mm/shmem.c (ffffffff8138ccf2)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/memory.c (ffffffff813c0b39)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:wp_page_copy
```
```
In mm/page_alloc.c (ffffffff813ece7a)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff8144a191)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff814f7f48)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/fuse/dev.c (ffffffff8161b1d1)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff8162eee2)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/xen/grant-table.c (ffffffff81a1a5ef)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81a1ac89)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a2383c)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/scsi/sd.c (ffffffff81b91f09)
Location: arch/x86/include/asm/page_64.h:50
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
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
In arch/x86/xen/time.c (ffffffff81032c16)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83691e5a)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/head64.c (ffffffff83694aee)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af5c1)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff821450fc)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff81198827)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/power/swap.c (ffffffff8119c524)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/kexec_core.c (ffffffff81213e54)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_normal_segment
```
```
In mm/shmem.c (ffffffff813c3031)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/memory.c (ffffffff813f58aa)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__wp_page_copy_user
```
```
In mm/page_alloc.c (ffffffff81421db8)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/khugepaged.c (ffffffff8147fc16)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff8152f148)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/fuse/dev.c (ffffffff81653341)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff81667145)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/xen/grant-table.c (ffffffff81a6346f)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81a63e39)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6ccf0)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/scsi/sd.c (ffffffff81be4eea)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_set_special_bvec
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
In arch/x86/xen/time.c (ffffffff81038f06)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c196a)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/head64.c (ffffffff838c49de)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b6151)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff8222781c)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff811a76ad)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
```
In kernel/power/swap.c (ffffffff811ab69f)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swap_write_page
```
```
In kernel/kexec_core.c (ffffffff8122bda4)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_normal_segment
```
```
In mm/shmem.c (ffffffff813edb4a)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/memory.c (ffffffff8141f58a)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__wp_page_copy_user
```
```
In mm/page_alloc.c (ffffffff8144ebea)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/khugepaged.c (ffffffff814add20)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/dax.c (ffffffff81564028)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/fuse/dev.c (ffffffff8168c951)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff816a1492)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_add_dirent_to_cache
```
```
In drivers/xen/grant-table.c (ffffffff81ab5c8f)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81ab6679)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abedc0)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/scsi/sd.c (ffffffff81c3a04a)
Location: arch/x86/include/asm/page_64.h:46
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_set_special_bvec
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm64/mm/copypage.c:__cpu_clear_user_page
  - virt/kvm/arm/mmu.c:free_hyp_pgds
  - kernel/kexec_core.c:kimage_load_segment
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/memory.c:wp_page_copy
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - fs/libfs.c:simple_readpage
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/readdir.c:fuse_emit
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
**Symbols:**

```
ffff800010d81f3c-ffff800010d81f60: clear_page (STB_GLOBAL)
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
In arch/powerpc/mm/mem.c (c0000000000870c0)
Location: arch/powerpc/include/asm/page_64.h:43
Inline: True
Inline callers:
  - arch/powerpc/mm/mem.c:clear_user_page
```
```
In kernel/kexec_core.c (c000000000231f74)
Location: arch/powerpc/include/asm/page_64.h:43
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/shmem.c (c000000000390f6c)
Location: arch/powerpc/include/asm/page_64.h:43
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (c0000000003bc250)
Location: arch/powerpc/include/asm/page_64.h:43
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/page_alloc.c (c0000000003e526c)
Location: arch/powerpc/include/asm/page_64.h:43
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (c000000000448e68)
Location: arch/powerpc/include/asm/page_64.h:43
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (c0000000004bf038)
Location: arch/powerpc/include/asm/page_64.h:43
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/fuse/dev.c (c000000000648798)
Location: arch/powerpc/include/asm/page_64.h:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (c00000000065ced0)
Location: arch/powerpc/include/asm/page_64.h:43
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In drivers/scsi/sd.c (c000000000a4b788)
Location: arch/powerpc/include/asm/page_64.h:43
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/kernel/head64.c (ffffffff8288a481)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff8101e4c0)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8289528b)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ec1f)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff81a669ae)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff811049c9)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (ffffffff8110774d)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
```
```
In kernel/kexec_core.c (ffffffff811525e0)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/shmem.c (ffffffff81237b84)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff8125da19)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
```
```
In mm/page_alloc.c (ffffffff8127466a)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812b481e)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81304049)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/dax.c (ffffffff81341bbd)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
```
```
In fs/fuse/dev.c (ffffffff814193ff)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff8142843d)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In drivers/xen/grant-table.c (ffffffff81628e48)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8162a857)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff8162f5b2)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/scsi/sd.c (ffffffff81738c7f)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
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
In arch/x86/kernel/head64.c (ffffffff82888425)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ecc1)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff81a2346e)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff810f5c69)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (ffffffff810f866d)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
```
```
In kernel/kexec_core.c (ffffffff811458c0)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/shmem.c (ffffffff8122abc4)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff8124fe69)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
```
```
In mm/page_alloc.c (ffffffff812665da)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812a5886)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/libfs.c (ffffffff812f4c69)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/dax.c (ffffffff813324b1)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
```
```
In fs/fuse/dev.c (ffffffff81409e7f)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff81418ebd)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In drivers/scsi/sd.c (ffffffff8171a91f)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
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
In arch/x86/kernel/head64.c (ffffffff8289d481)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff8101e470)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a8282)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f0cf)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff81ad2dbe)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff81102c79)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (ffffffff8110567d)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
```
```
In kernel/kexec_core.c (ffffffff81150490)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/shmem.c (ffffffff81235924)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff8125b7b9)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
```
```
In mm/page_alloc.c (ffffffff8127240a)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812b262e)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81301e39)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/dax.c (ffffffff8133f68d)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8141559f)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff814245dd)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In drivers/xen/grant-table.c (ffffffff81656e18)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81658827)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff8165d582)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/scsi/sd.c (ffffffff8177940f)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
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
In arch/x86/kernel/head64.c (ffffffff8289d481)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff8101e6d4)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_save_time_memory_area
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a8288)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107134f)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:alloc_pgt_page
```
```
In arch/x86/mm/init.c (ffffffff81adf2be)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In kernel/power/snapshot.c (ffffffff8110e069)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/power/swap.c (ffffffff81110a5d)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_check
```
```
In kernel/kexec_core.c (ffffffff8115d2ca)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/shmem.c (ffffffff81245bea)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/memory.c (ffffffff8126b174)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:wp_page_copy
```
```
In mm/page_alloc.c (ffffffff81282250)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/khugepaged.c (ffffffff812c2cd4)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
```
```
In fs/libfs.c (ffffffff81313353)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/libfs.c:simple_readpage
```
```
In fs/dax.c (ffffffff8135305b)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8142c32f)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
```
In fs/fuse/readdir.c (ffffffff8143b705)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In drivers/xen/grant-table.c (ffffffff816713ff)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81672e2e)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_fifo.c (ffffffff81677b92)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/scsi/sd.c (ffffffff81793236)
Location: arch/x86/include/asm/page_64.h:47
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
