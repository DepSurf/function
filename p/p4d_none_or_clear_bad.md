# Function: <code>p4d_none_or_clear_bad</code>

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
In mm/memory.c (ffffffff811f7249)
Location: include/asm-generic/pgtable.h:494
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff811ff66f)
Location: include/asm-generic/pgtable.h:494
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8120075f)
Location: include/asm-generic/pgtable.h:494
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812023aa)
Location: include/asm-generic/pgtable.h:494
Inline: True
```
```
In mm/vmalloc.c (ffffffff81206da8)
Location: include/asm-generic/pgtable.h:494
Inline: True
```
```
In mm/swapfile.c (ffffffff8120da77)
Location: include/asm-generic/pgtable.h:494
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/memory.c (ffffffff8120f7c0)
Location: include/asm-generic/pgtable.h:495
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81217c0b)
Location: include/asm-generic/pgtable.h:495
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218f0a)
Location: include/asm-generic/pgtable.h:495
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8121af49)
Location: include/asm-generic/pgtable.h:495
Inline: True
```
```
In mm/vmalloc.c (ffffffff8121fdeb)
Location: include/asm-generic/pgtable.h:495
Inline: True
```
```
In mm/swapfile.c (ffffffff81228be6)
Location: include/asm-generic/pgtable.h:495
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
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
In mm/memory.c (ffffffff81230573)
Location: include/asm-generic/pgtable.h:538
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81239a65)
Location: include/asm-generic/pgtable.h:538
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a8d8)
Location: include/asm-generic/pgtable.h:538
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8123ce02)
Location: include/asm-generic/pgtable.h:538
Inline: True
```
```
In mm/vmalloc.c (ffffffff812410b0)
Location: include/asm-generic/pgtable.h:538
Inline: True
```
```
In mm/swapfile.c (ffffffff81249f07)
Location: include/asm-generic/pgtable.h:538
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/memory.c (ffffffff812438e0)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8124d380)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eadb)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812512b7)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81255790)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/swapfile.c (ffffffff8125e547)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
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
In mm/memory.c (ffffffff81255731)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8125fb82)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260e30)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81263597)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81267af3)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/swapfile.c (ffffffff8127b7c6)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/memory.c (ffffffff81263ca1)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8126e442)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f5c9)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81272063)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81276443)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/swapfile.c (ffffffff8128b2a6)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/memory.c (ffffffff812935b5)
Location: include/linux/pgtable.h:750
Inline: True
Inline callers:
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff8129ee64)
Location: include/linux/pgtable.h:750
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129fae9)
Location: include/linux/pgtable.h:750
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
```
```
In mm/pagewalk.c (ffffffff812a2c88)
Location: include/linux/pgtable.h:750
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff812a7e66)
Location: include/linux/pgtable.h:750
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bdc8b)
Location: include/linux/pgtable.h:750
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
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
In mm/memory.c (ffffffff8129dff8)
Location: include/linux/pgtable.h:799
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff812aa224)
Location: include/linux/pgtable.h:799
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aaf79)
Location: include/linux/pgtable.h:799
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812ae5a8)
Location: include/linux/pgtable.h:799
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff812b2f36)
Location: include/linux/pgtable.h:799
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812c97ab)
Location: include/linux/pgtable.h:799
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
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
In mm/memory.c (ffffffff812a01f3)
Location: include/linux/pgtable.h:799
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff812af671)
Location: include/linux/pgtable.h:799
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812b03b3)
Location: include/linux/pgtable.h:799
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812b3979)
Location: include/linux/pgtable.h:799
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff812bc44c)
Location: include/linux/pgtable.h:799
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d041f)
Location: include/linux/pgtable.h:799
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
In mm/memory.c (ffffffff812e1191)
Location: include/linux/pgtable.h:818
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff812f0ea1)
Location: include/linux/pgtable.h:818
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812f1bf5)
Location: include/linux/pgtable.h:818
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff812f54f9)
Location: include/linux/pgtable.h:818
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff812fea2e)
Location: include/linux/pgtable.h:818
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8131596a)
Location: include/linux/pgtable.h:818
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
In mm/memory.c (ffffffff81341b48)
Location: include/linux/pgtable.h:851
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff81354a11)
Location: include/linux/pgtable.h:851
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813557ba)
Location: include/linux/pgtable.h:851
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff813593a0)
Location: include/linux/pgtable.h:851
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff81361223)
Location: include/linux/pgtable.h:851
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff81380f06)
Location: include/linux/pgtable.h:851
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
In mm/memory.c (ffffffff813b9a7a)
Location: include/linux/pgtable.h:887
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff813cef6f)
Location: include/linux/pgtable.h:887
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813cff2a)
Location: include/linux/pgtable.h:887
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff813d3c70)
Location: include/linux/pgtable.h:887
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff813dcbc9)
Location: include/linux/pgtable.h:887
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff813ff74e)
Location: include/linux/pgtable.h:887
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
In mm/memory.c (ffffffff813ee7d9)
Location: include/linux/pgtable.h:899
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff8140366c)
Location: include/linux/pgtable.h:899
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff814049ed)
Location: include/linux/pgtable.h:899
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff81408640)
Location: include/linux/pgtable.h:899
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff81411439)
Location: include/linux/pgtable.h:899
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff814327be)
Location: include/linux/pgtable.h:899
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
In mm/memory.c (ffffffff8141a2b9)
Location: include/linux/pgtable.h:1030
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
```
```
In mm/mprotect.c (ffffffff8142fbec)
Location: include/linux/pgtable.h:1030
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81430fbd)
Location: include/linux/pgtable.h:1030
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
```
```
In mm/pagewalk.c (ffffffff81434d60)
Location: include/linux/pgtable.h:1030
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/vmalloc.c (ffffffff8143dc29)
Location: include/linux/pgtable.h:1030
Inline: True
Inline callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff8146bbde)
Location: include/linux/pgtable.h:1030
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:576
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
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
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:576
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
In mm/memory.c (ffffffff8125c2f1)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81266a92)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267c19)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8126a6b3)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8126ea93)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/swapfile.c (ffffffff81283886)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/memory.c (ffffffff8124e885)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8125894b)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81259f71)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8125c5a7)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81260413)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/swapfile.c (ffffffff81275740)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/memory.c (ffffffff8125a091)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81264832)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812659b9)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81268453)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8126c833)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/swapfile.c (ffffffff81281696)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/memory.c (ffffffff81269a91)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff812741f2)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8127535b)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81277dd3)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8127c373)
Location: include/asm-generic/pgtable.h:576
Inline: True
```
```
In mm/swapfile.c (ffffffff812913d1)
Location: include/asm-generic/pgtable.h:576
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
</details>
</li>
</ul>

## Differences
