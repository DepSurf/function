# Function: <code>pgd_none_or_clear_bad</code>

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
In mm/memory.c (ffffffff811bcc96)
Location: include/asm-generic/pgtable.h:360
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811c852d)
Location: include/asm-generic/pgtable.h:360
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c936c)
Location: include/asm-generic/pgtable.h:360
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff811ce28b)
Location: include/asm-generic/pgtable.h:360
Inline: True
```
```
In mm/pagewalk.c (ffffffff811cfe15)
Location: include/asm-generic/pgtable.h:360
Inline: True
```
```
In mm/swapfile.c (ffffffff811d40fd)
Location: include/asm-generic/pgtable.h:360
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/memory.c (ffffffff811d8c44)
Location: include/asm-generic/pgtable.h:365
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811e4671)
Location: include/asm-generic/pgtable.h:365
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e575a)
Location: include/asm-generic/pgtable.h:365
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/vmalloc.c (ffffffff811eae2b)
Location: include/asm-generic/pgtable.h:365
Inline: True
```
```
In mm/pagewalk.c (ffffffff811ecf73)
Location: include/asm-generic/pgtable.h:365
Inline: True
```
```
In mm/swapfile.c (ffffffff811f1f70)
Location: include/asm-generic/pgtable.h:365
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/memory.c (ffffffff811e8114)
Location: include/asm-generic/pgtable.h:389
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811f4691)
Location: include/asm-generic/pgtable.h:389
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5999)
Location: include/asm-generic/pgtable.h:389
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff811f7363)
Location: include/asm-generic/pgtable.h:389
Inline: True
```
```
In mm/vmalloc.c (ffffffff811fc08b)
Location: include/asm-generic/pgtable.h:389
Inline: True
```
```
In mm/swapfile.c (ffffffff81202960)
Location: include/asm-generic/pgtable.h:389
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:483
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:483
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:483
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:483
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:483
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:483
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:484
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:484
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:484
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:484
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:484
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:484
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:527
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:527
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:527
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:527
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:527
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:527
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
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
In mm/memory.c (ffffffff81293760)
Location: include/linux/pgtable.h:739
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8129f098)
Location: include/linux/pgtable.h:739
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8129fa5e)
Location: include/linux/pgtable.h:739
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/pagewalk.c (ffffffff812a2ddd)
Location: include/linux/pgtable.h:739
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff812ab72e)
Location: include/linux/pgtable.h:739
Inline: True
Inline callers:
  - mm/vmalloc.c:unmap_kernel_range_noflush
```
```
In mm/swapfile.c (ffffffff812bdfcc)
Location: include/linux/pgtable.h:739
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/memory.c (ffffffff8129de4b)
Location: include/linux/pgtable.h:788
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812aa458)
Location: include/linux/pgtable.h:788
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812aaeee)
Location: include/linux/pgtable.h:788
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812ae6fd)
Location: include/linux/pgtable.h:788
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff812b6c86)
Location: include/linux/pgtable.h:788
Inline: True
Inline callers:
  - mm/vmalloc.c:unmap_kernel_range_noflush
```
```
In mm/swapfile.c (ffffffff812c9aec)
Location: include/linux/pgtable.h:788
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/memory.c (ffffffff812a0135)
Location: include/linux/pgtable.h:788
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812af898)
Location: include/linux/pgtable.h:788
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812b0356)
Location: include/linux/pgtable.h:788
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812b3abd)
Location: include/linux/pgtable.h:788
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff812bc386)
Location: include/linux/pgtable.h:788
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d0354)
Location: include/linux/pgtable.h:788
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/memory.c (ffffffff812e1086)
Location: include/linux/pgtable.h:807
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812f10e0)
Location: include/linux/pgtable.h:807
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812f1b95)
Location: include/linux/pgtable.h:807
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812f565c)
Location: include/linux/pgtable.h:807
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff812fe9a1)
Location: include/linux/pgtable.h:807
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8131589f)
Location: include/linux/pgtable.h:807
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/memory.c (ffffffff81341a91)
Location: include/linux/pgtable.h:840
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff813548ef)
Location: include/linux/pgtable.h:840
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81355755)
Location: include/linux/pgtable.h:840
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff81359518)
Location: include/linux/pgtable.h:840
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81365ab9)
Location: include/linux/pgtable.h:840
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81380e4f)
Location: include/linux/pgtable.h:840
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/memory.c (ffffffff813b99bb)
Location: include/linux/pgtable.h:876
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff813cee15)
Location: include/linux/pgtable.h:876
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813cfec5)
Location: include/linux/pgtable.h:876
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff813d3df8)
Location: include/linux/pgtable.h:876
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff813e15e5)
Location: include/linux/pgtable.h:876
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff6b6)
Location: include/linux/pgtable.h:876
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/memory.c (ffffffff813ee6ed)
Location: include/linux/pgtable.h:888
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81403a6d)
Location: include/linux/pgtable.h:888
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81404988)
Location: include/linux/pgtable.h:888
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff814087c8)
Location: include/linux/pgtable.h:888
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81416355)
Location: include/linux/pgtable.h:888
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8143272b)
Location: include/linux/pgtable.h:888
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/memory.c (ffffffff8141a1cd)
Location: include/linux/pgtable.h:1019
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8142ffed)
Location: include/linux/pgtable.h:1019
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81430f58)
Location: include/linux/pgtable.h:1019
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff81434ee8)
Location: include/linux/pgtable.h:1019
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81442e25)
Location: include/linux/pgtable.h:1019
Inline: True
Inline callers:
  - mm/vmalloc.c:__vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8146bb4b)
Location: include/linux/pgtable.h:1019
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/memory.c (ffff8000102f6ae4)
Location: include/asm-generic/pgtable.h:565
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffff800010304f8c)
Location: include/asm-generic/pgtable.h:565
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff800010305eb8)
Location: include/asm-generic/pgtable.h:565
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffff8000103078fc)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/vmalloc.c (ffff80001030c6a8)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (ffff800010326694)
Location: include/asm-generic/pgtable.h:565
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In arch/arm/mm/pgd.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
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
In arch/powerpc/mm/hugetlbpage.c (c0000000000a5bb8)
Location: include/asm-generic/pgtable.h:565
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
```
```
In mm/memory.c (c0000000003bfb50)
Location: include/asm-generic/pgtable.h:565
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (c0000000003d1e98)
Location: include/asm-generic/pgtable.h:565
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3be4)
Location: include/asm-generic/pgtable.h:565
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (c0000000003d6650)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/vmalloc.c (c0000000003dcb00)
Location: include/asm-generic/pgtable.h:565
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/swapfile.c (c0000000003fcdd8)
Location: include/asm-generic/pgtable.h:565
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:565
Inline: True
```
</details>
</li>
</ul>

## Differences
