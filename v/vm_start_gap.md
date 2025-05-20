# Function: <code>vm_start_gap</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81031389)
Location: include/linux/mm.h:2249
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81075a49)
Location: include/linux/mm.h:2249
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff811fcad7)
Location: include/linux/mm.h:2249
Inline: True
Inline callers:
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:vma_compute_subtree_gap
  - mm/mmap.c:SyS_brk
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
In arch/x86/kernel/sys_x86_64.c (ffffffff8103364e)
Location: include/linux/mm.h:2358
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8107bcab)
Location: include/linux/mm.h:2358
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff81215067)
Location: include/linux/mm.h:2358
Inline: True
Inline callers:
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:vma_compute_subtree_gap
  - mm/mmap.c:SyS_brk
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
In arch/x86/kernel/sys_x86_64.c (ffffffff810348ff)
Location: include/linux/mm.h:2447
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8107eaa7)
Location: include/linux/mm.h:2447
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff81235f0b)
Location: include/linux/mm.h:2447
Inline: True
Inline callers:
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:vma_compute_subtree_gap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81035adf)
Location: include/linux/mm.h:2520
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81085627)
Location: include/linux/mm.h:2520
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff8124972b)
Location: include/linux/mm.h:2520
Inline: True
Inline callers:
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:vma_compute_subtree_gap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81037c49)
Location: include/linux/mm.h:2514
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81089222)
Location: include/linux/mm.h:2514
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff8125ba5b)
Location: include/linux/mm.h:2514
Inline: True
Inline callers:
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:vma_compute_subtree_gap
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81038419)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81089e92)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff8126a86d)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
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
In arch/x86/kernel/sys_x86_64.c (ffffffff8103ae86)
Location: include/linux/mm.h:2698
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810916f6)
Location: include/linux/mm.h:2698
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff8129b2b0)
Location: include/linux/mm.h:2698
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:__do_sys_brk
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
In arch/x86/kernel/sys_x86_64.c (ffffffff8103b696)
Location: include/linux/mm.h:2698
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81091026)
Location: include/linux/mm.h:2698
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff812a6470)
Location: include/linux/mm.h:2698
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:__do_sys_brk
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
In arch/x86/kernel/sys_x86_64.c (ffffffff8103d049)
Location: include/linux/mm.h:2694
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81091ada)
Location: include/linux/mm.h:2694
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff812ab79c)
Location: include/linux/mm.h:2694
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:__do_sys_brk
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81042b49)
Location: include/linux/mm.h:2752
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810a165a)
Location: include/linux/mm.h:2752
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff812ece19)
Location: include/linux/mm.h:2752
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:__do_sys_brk
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
In arch/x86/kernel/sys_x86_64.c (ffffffff8104aa16)
Location: include/linux/mm.h:2827
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810b579b)
Location: include/linux/mm.h:2827
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff813501c3)
Location: include/linux/mm.h:2827
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/mmap.c:vma_link
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:__do_sys_brk
```
```
In fs/hugetlbfs/inode.c (ffffffff81556544)
Location: include/linux/mm.h:2827
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
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
In arch/x86/kernel/sys_x86_64.c (ffffffff8105662c)
Location: include/linux/mm.h:2978
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810d075e)
Location: include/linux/mm.h:2978
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff813c918d)
Location: include/linux/mm.h:2978
Inline: True
Inline callers:
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
  - mm/mmap.c:__do_sys_brk
```
```
In fs/hugetlbfs/inode.c (ffffffff815f801f)
Location: include/linux/mm.h:2978
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
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
In arch/x86/kernel/sys_x86_64.c (ffffffff810575fc)
Location: include/linux/mm.h:3284
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810d3d84)
Location: include/linux/mm.h:3284
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff813fd522)
Location: include/linux/mm.h:3284
Inline: True
Inline callers:
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
  - mm/mmap.c:vm_unmapped_area
  - mm/mmap.c:vm_unmapped_area
  - mm/mmap.c:vm_unmapped_area
  - mm/mmap.c:__do_sys_brk
```
```
In fs/hugetlbfs/inode.c (ffffffff8162ffb2)
Location: include/linux/mm.h:3284
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
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
In arch/x86/kernel/sys_x86_64.c (ffffffff8105e806)
Location: include/linux/mm.h:3473
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810dc514)
Location: include/linux/mm.h:3473
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff81429f4f)
Location: include/linux/mm.h:3473
Inline: True
Inline callers:
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
  - mm/mmap.c:vm_unmapped_area
  - mm/mmap.c:vm_unmapped_area
  - mm/mmap.c:__do_sys_brk
```
```
In fs/hugetlbfs/inode.c (ffffffff8166944a)
Location: include/linux/mm.h:3473
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
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
In mm/mmap.c (ffff800010301f84)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:arch_get_unmapped_area_topdown
  - mm/mmap.c:arch_get_unmapped_area
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:__arm64_sys_brk
```
```
In fs/hugetlbfs/inode.c (ffff8000104e17fc)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_get_unmapped_area
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
In arch/arm/mm/mmap.c (c031f650)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - arch/arm/mm/mmap.c:arch_get_unmapped_area_topdown
  - arch/arm/mm/mmap.c:arch_get_unmapped_area
```
```
In mm/mmap.c (c05206b8)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:__se_sys_brk
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
In arch/powerpc/mm/mmap.c (c00000000008871c)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - arch/powerpc/mm/mmap.c:radix__arch_get_unmapped_area_topdown
  - arch/powerpc/mm/mmap.c:radix__arch_get_unmapped_area
```
```
In arch/powerpc/mm/book3s64/radix_hugetlbpage.c (c00000000009ef94)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__hugetlb_get_unmapped_area
```
```
In arch/powerpc/mm/slice.c (c0000000000a3da4)
Location: include/linux/mm.h:2488
Inline: True
```
```
In mm/mmap.c (c0000000003ce29c)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:__se_sys_brk
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
In mm/mmap.c (ffffffe00020efca)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:arch_get_unmapped_area_topdown
  - mm/mmap.c:arch_get_unmapped_area
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:__se_sys_brk
```
```
In fs/hugetlbfs/inode.c (ffffffe000355772)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_get_unmapped_area
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81038579)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81088e52)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff81262ebd)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81027f59)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81077ab2)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff812552dd)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
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
In arch/x86/kernel/sys_x86_64.c (ffffffff810383d9)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81088e02)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff81260c5d)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
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
In arch/x86/kernel/sys_x86_64.c (ffffffff810393d9)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8108b0a2)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff8127062d)
Location: include/linux/mm.h:2488
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
</details>
</li>
</ul>

## Differences
