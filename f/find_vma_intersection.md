# Function: <code>find_vma_intersection</code>

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
In mm/mmap.c (ffffffff811c6dc3)
Location: include/linux/mm.h:2053
Inline: True
Inline callers:
  - mm/mmap.c:SyS_brk
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff811e1153)
Location: include/linux/mm.h:2053
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff8120874a)
Location: include/linux/mm.h:2053
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff8132b72b)
Location: include/linux/mm.h:2053
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/mmap.c (ffffffff811e3632)
Location: include/linux/mm.h:2175
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_brk
```
```
In mm/mempolicy.c (ffffffff811ffb21)
Location: include/linux/mm.h:2175
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff8122e278)
Location: include/linux/mm.h:2175
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff81360348)
Location: include/linux/mm.h:2175
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/mmap.c (ffffffff811f3612)
Location: include/linux/mm.h:2161
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_brk
```
```
In mm/mempolicy.c (ffffffff81211436)
Location: include/linux/mm.h:2161
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff812407b1)
Location: include/linux/mm.h:2161
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff81376b66)
Location: include/linux/mm.h:2161
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/mmap.c (ffffffff811fe66a)
Location: include/linux/mm.h:2240
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff8121cd35)
Location: include/linux/mm.h:2240
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff8124c5e9)
Location: include/linux/mm.h:2240
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff8138a71c)
Location: include/linux/mm.h:2240
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/mmap.c (ffffffff81216c1a)
Location: include/linux/mm.h:2349
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff81237eea)
Location: include/linux/mm.h:2349
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff8126ca2e)
Location: include/linux/mm.h:2349
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff813af892)
Location: include/linux/mm.h:2349
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/mmap.c (ffffffff81237c00)
Location: include/linux/mm.h:2438
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff8125b3ba)
Location: include/linux/mm.h:2438
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff812915de)
Location: include/linux/mm.h:2438
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff813df60c)
Location: include/linux/mm.h:2438
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/mmap.c (ffffffff8124b599)
Location: include/linux/mm.h:2511
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff8126fbeb)
Location: include/linux/mm.h:2511
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff812a65fe)
Location: include/linux/mm.h:2511
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff813f9d2d)
Location: include/linux/mm.h:2511
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/mmap.c (ffffffff8125da43)
Location: include/linux/mm.h:2505
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff8128b1f9)
Location: include/linux/mm.h:2505
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff812c1cab)
Location: include/linux/mm.h:2505
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff814263e3)
Location: include/linux/mm.h:2505
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/mmap.c (ffffffff8126c213)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff8129ad69)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff812d3bdb)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff81440133)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3266)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
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
In mm/mmap.c (ffffffff8129bf56)
Location: include/linux/mm.h:2689
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff812ce0a1)
Location: include/linux/mm.h:2689
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff81309a55)
Location: include/linux/mm.h:2689
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff81490edc)
Location: include/linux/mm.h:2689
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e133)
Location: include/linux/mm.h:2689
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
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
In mm/mmap.c (ffffffff812a71dd)
Location: include/linux/mm.h:2689
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff812d8ffd)
Location: include/linux/mm.h:2689
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff8131589a)
Location: include/linux/mm.h:2689
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff814ae66a)
Location: include/linux/mm.h:2689
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ad483)
Location: include/linux/mm.h:2689
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
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
In mm/mmap.c (ffffffff812acd9b)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff812e0733)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In ipc/shm.c (ffffffff814b4494)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189060c)
Location: include/linux/mm.h:2685
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
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
In mm/mmap.c (ffffffff812ecb56)
Location: include/linux/mm.h:2723
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
```
```
In ipc/shm.c (ffffffff8150cb44)
Location: include/linux/mm.h:2723
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/mmap.c (ffffffff8134fe61)
Location: include/linux/mm.h:2798
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
```
```
In ipc/shm.c (ffffffff8159eab2)
Location: include/linux/mm.h:2798
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *find_vma_intersection(struct mm_struct *mm, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813ca184)
Location: mm/mmap.c:1811
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_mmap
Direct callers:
  - mm/gup.c:__mm_populate
  - mm/gup.c:__mm_populate
  - mm/mremap.c:__do_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff813c6920-ffffffff813c696d: find_vma_intersection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *find_vma_intersection(struct mm_struct *mm, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fe6f8)
Location: mm/mmap.c:1839
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_mmap
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/gup.c:__mm_populate
  - mm/gup.c:__mm_populate
  - mm/mremap.c:__do_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff813fab90-ffffffff813fabe1: find_vma_intersection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct vm_area_struct *find_vma_intersection(struct mm_struct *mm, long unsigned int start_addr, long unsigned int end_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142ab68)
Location: mm/mmap.c:1871
Inline: True
Inline callers:
  - mm/mmap.c:insert_vm_struct
  - mm/mmap.c:do_mmap
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/gup.c:__mm_populate
  - mm/gup.c:__mm_populate
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81426950-ffffffff814269a1: find_vma_intersection (STB_GLOBAL)
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
In virt/kvm/kvm_main.c (ffff8000100bbe0c)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
```
```
In virt/kvm/arm/mmu.c (ffff8000100cab04)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
```
```
In mm/mmap.c (ffff8000103035ac)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffff800010339974)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/frame_vector.c (ffff800010379b6c)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffff800010528808)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/mmap.c (c0521c44)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/frame_vector.c (c0564d4c)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (c06e1df0)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/mmap.c (c0000000003d0090)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (c000000000414134)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/frame_vector.c (c00000000046cd08)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (c000000000673420)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/mmap.c (ffffffe000210110)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/frame_vector.c (ffffffe000250e80)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffe00038bf62)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/mmap.c (ffffffff81264863)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff81293349)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff812cc1bb)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff81438713)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/mmap.c (ffffffff81256c83)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff81284f59)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff812bd02b)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff81429183)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d316)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
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
In mm/mmap.c (ffffffff81262603)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff81291159)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff812c9fcb)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff814348b3)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c80e6)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
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
In mm/mmap.c (ffffffff81271fc3)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/mempolicy.c (ffffffff812a0f5e)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/frame_vector.c (ffffffff812daccb)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
  - mm/frame_vector.c:get_vaddr_frames
```
```
In ipc/shm.c (ffffffff8144b9fe)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2386)
Location: include/linux/mm.h:2479
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
