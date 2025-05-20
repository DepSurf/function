# Function: <code>hash__pgd_bad</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In arch/powerpc/mm/hugetlbpage.c (c0000000000a6110)
Location: arch/powerpc/include/asm/book3s/64/hash.h:137
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
```
```
In mm/gup.c (c0000000003b88d0)
Location: arch/powerpc/include/asm/book3s/64/hash.h:137
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (c0000000003bb230)
Location: arch/powerpc/include/asm/book3s/64/hash.h:137
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (c0000000003d2b50)
Location: arch/powerpc/include/asm/book3s/64/hash.h:137
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3f90)
Location: arch/powerpc/include/asm/book3s/64/hash.h:137
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (c0000000003d6970)
Location: arch/powerpc/include/asm/book3s/64/hash.h:137
Inline: True
```
```
In mm/vmalloc.c (c0000000003dcfe0)
Location: arch/powerpc/include/asm/book3s/64/hash.h:137
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/swapfile.c (c0000000003fd1f0)
Location: arch/powerpc/include/asm/book3s/64/hash.h:137
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
