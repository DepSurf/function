# Function: <code>vma_kernel_pagesize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811daca0)
Location: mm/hugetlb.c:633
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_numa_map
```
**Symbols:**

```
ffffffff811daca0-ffffffff811dace0: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fa665)
Location: mm/hugetlb.c:636
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff811f8e10-ffffffff811f8e50: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120b095)
Location: mm/hugetlb.c:636
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
```
**Symbols:**

```
ffffffff81209a00-ffffffff81209a40: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81219229)
Location: mm/hugetlb.c:638
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
Direct callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81214bd0-ffffffff81214c03: vma_kernel_pagesize.part.39 (STB_LOCAL)
ffffffff81214c10-ffffffff81214c2c: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff812341de)
Location: mm/hugetlb.c:639
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
Direct callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff8122f760-ffffffff8122f793: vma_kernel_pagesize.part.47 (STB_LOCAL)
ffffffff8122f7a0-ffffffff8122f7bc: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81253fa5)
Location: mm/hugetlb.c:638
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
```
**Symbols:**

```
ffffffff81251680-ffffffff812516b1: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81268385)
Location: mm/hugetlb.c:638
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81265a80-ffffffff81265ab1: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81283665)
Location: mm/hugetlb.c:640
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81280af0-ffffffff81280b21: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81293205)
Location: mm/hugetlb.c:641
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81290500-ffffffff81290531: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c63d5)
Location: mm/hugetlb.c:780
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812c3160-ffffffff812c3191: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d1fc5)
Location: mm/hugetlb.c:810
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812ceeb0-ffffffff812ceee1: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d8935)
Location: mm/hugetlb.c:817
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812d5ad0-ffffffff812d5b01: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131ec45)
Location: mm/hugetlb.c:819
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8131b900-ffffffff8131b931: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138b435)
Location: mm/hugetlb.c:836
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81387120-ffffffff81387169: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81408b05)
Location: mm/hugetlb.c:980
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff814050d0-ffffffff81405116: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8143c175)
Location: mm/hugetlb.c:974
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81438750-ffffffff81438796: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814768c5)
Location: mm/hugetlb.c:1005
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff814720e0-ffffffff81472126: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010330f98)
Location: mm/hugetlb.c:641
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - virt/kvm/kvm_main.c:kvm_host_page_size
  - virt/kvm/arm/mmu.c:user_mem_abort
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffff80001032d618-ffff80001032d668: vma_kernel_pagesize (STB_GLOBAL)
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
In fs/userfaultfd.c (0)
Location: include/linux/hugetlb.h:659
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:659
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000409be0)
Location: mm/hugetlb.c:641
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - arch/powerpc/mm/hugetlbpage.c:vma_mmu_pagesize
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
c000000000405140-c0000000004051ac: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022e17c)
Location: mm/hugetlb.c:641
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffe00022bc26-ffffffe00022bc60: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128b7e5)
Location: mm/hugetlb.c:641
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81288ae0-ffffffff81288b11: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127d615)
Location: mm/hugetlb.c:641
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8127a930-ffffffff8127a961: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812895f5)
Location: mm/hugetlb.c:641
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812868f0-ffffffff81286921: vma_kernel_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_kernel_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812993d5)
Location: mm/hugetlb.c:641
Inline: True
Inline callers:
  - mm/hugetlb.c:vma_mmu_pagesize
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812966e0-ffffffff81296711: vma_kernel_pagesize (STB_GLOBAL)
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
