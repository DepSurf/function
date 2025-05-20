# Function: <code>vma_mmu_pagesize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811dc410)
Location: mm/hugetlb.c:653
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff811dc410-ffffffff811dc450: vma_mmu_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fa660)
Location: mm/hugetlb.c:656
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff811fa660-ffffffff811fa6a0: vma_mmu_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120b090)
Location: mm/hugetlb.c:656
Inline: False
```
**Symbols:**

```
ffffffff8120b090-ffffffff8120b0d0: vma_mmu_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81219229)
Location: mm/hugetlb.c:658
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff81216410-ffffffff8121642c: vma_mmu_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812341de)
Location: mm/hugetlb.c:659
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff812310c0-ffffffff812310dc: vma_mmu_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81253fa0)
Location: mm/hugetlb.c:652
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:huge_pmd_share
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff81253fa0-ffffffff81253fd1: vma_mmu_pagesize (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81268380)
Location: mm/hugetlb.c:652
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:huge_pmd_share
  - fs/userfaultfd.c:handle_userfault
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81268380-ffffffff812683b1: vma_mmu_pagesize (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81283660)
Location: mm/hugetlb.c:654
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:huge_pmd_share
  - fs/userfaultfd.c:handle_userfault
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81283660-ffffffff81283691: vma_mmu_pagesize (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81293200)
Location: mm/hugetlb.c:655
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:huge_pmd_share
  - fs/userfaultfd.c:handle_userfault
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81293200-ffffffff81293231: vma_mmu_pagesize (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c63d0)
Location: mm/hugetlb.c:794
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:huge_pmd_share
  - fs/userfaultfd.c:handle_userfault
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812c63d0-ffffffff812c6401: vma_mmu_pagesize (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d1fc0)
Location: mm/hugetlb.c:824
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:huge_pmd_share
  - fs/userfaultfd.c:handle_userfault
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812d1fc0-ffffffff812d1ff1: vma_mmu_pagesize (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d8930)
Location: mm/hugetlb.c:831
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:huge_pmd_share
  - fs/userfaultfd.c:handle_userfault
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812d8930-ffffffff812d8961: vma_mmu_pagesize (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131ec40)
Location: mm/hugetlb.c:833
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:huge_pmd_share
  - fs/userfaultfd.c:handle_userfault
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8131ec40-ffffffff8131ec71: vma_mmu_pagesize (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138b430)
Location: mm/hugetlb.c:850
Inline: False
Direct callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:huge_pmd_share
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8138b430-ffffffff8138b479: vma_mmu_pagesize (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81408b00)
Location: mm/hugetlb.c:994
Inline: False
Direct callers:
  - mm/hugetlb.c:huge_pmd_share
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff81408b00-ffffffff81408b46: vma_mmu_pagesize (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8143c170)
Location: mm/hugetlb.c:988
Inline: False
Direct callers:
  - mm/hugetlb.c:huge_pmd_share
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8143c170-ffffffff8143c1b6: vma_mmu_pagesize (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814768c0)
Location: mm/hugetlb.c:1019
Inline: False
Direct callers:
  - mm/hugetlb.c:huge_pmd_share
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff814768c0-ffffffff81476906: vma_mmu_pagesize (STB_WEAK)
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010330f80)
Location: mm/hugetlb.c:655
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:huge_pmd_share
  - fs/userfaultfd.c:handle_userfault
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffff800010330f80-ffff800010330fd0: vma_mmu_pagesize (STB_WEAK)
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
In mm/rmap.c (0)
Location: include/linux/hugetlb.h:664
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:664
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a6500)
Location: arch/powerpc/mm/hugetlbpage.c:550
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - fs/userfaultfd.c:handle_userfault
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
c0000000000a6500-c0000000000a6574: vma_mmu_pagesize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022e166)
Location: mm/hugetlb.c:655
Inline: False
Direct callers:
  - mm/hugetlb.c:huge_pmd_share
  - fs/userfaultfd.c:handle_userfault
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffe00022e166-ffffffe00022e1a0: vma_mmu_pagesize (STB_WEAK)
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
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128b7e0)
Location: mm/hugetlb.c:655
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:huge_pmd_share
  - fs/userfaultfd.c:handle_userfault
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8128b7e0-ffffffff8128b811: vma_mmu_pagesize (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127d610)
Location: mm/hugetlb.c:655
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:huge_pmd_share
  - fs/userfaultfd.c:handle_userfault
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff8127d610-ffffffff8127d641: vma_mmu_pagesize (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812895f0)
Location: mm/hugetlb.c:655
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:huge_pmd_share
  - fs/userfaultfd.c:handle_userfault
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812895f0-ffffffff81289621: vma_mmu_pagesize (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int vma_mmu_pagesize(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812993d0)
Location: mm/hugetlb.c:655
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:huge_pmd_share
  - fs/userfaultfd.c:handle_userfault
  - fs/proc/task_mmu.c:show_smap
```
**Symbols:**

```
ffffffff812993d0-ffffffff81299401: vma_mmu_pagesize (STB_WEAK)
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
