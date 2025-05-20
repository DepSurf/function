# Function: <code>pmd_huge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81072b70)
Location: arch/x86/mm/hugetlbpage.c:62
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - mm/gup.c:follow_page_mask
  - mm/hugetlb.c:follow_huge_pmd
```
**Symbols:**

```
ffffffff81072b70-ffffffff81072b98: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81073400)
Location: arch/x86/mm/hugetlbpage.c:62
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - mm/gup.c:follow_page_mask
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:follow_huge_pmd
```
**Symbols:**

```
ffffffff81073400-ffffffff8107342d: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81076fb0)
Location: arch/x86/mm/hugetlbpage.c:62
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - mm/gup.c:follow_page_mask
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:follow_huge_pmd
```
**Symbols:**

```
ffffffff81076fb0-ffffffff81076fdd: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff810757d0)
Location: arch/x86/mm/hugetlbpage.c:65
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - mm/gup.c:__get_user_pages_fast
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:follow_huge_pmd
```
**Symbols:**

```
ffffffff810757d0-ffffffff810757fd: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff8107ba10)
Location: arch/x86/mm/hugetlbpage.c:67
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_offset
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff8107ba10-ffffffff8107ba3d: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff8107e800)
Location: arch/x86/mm/hugetlbpage.c:67
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/gup.c:gup_pgd_range
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_offset
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff8107e800-ffffffff8107e82d: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81085380)
Location: arch/x86/mm/hugetlbpage.c:67
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/gup.c:gup_pud_range
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_offset
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff81085380-ffffffff810853ad: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81088f80)
Location: arch/x86/mm/hugetlbpage.c:67
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/gup.c:gup_pud_range
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_offset
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff81088f80-ffffffff81088fad: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81089bf0)
Location: arch/x86/mm/hugetlbpage.c:67
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/gup.c:gup_pud_range
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_offset
```
**Symbols:**

```
ffffffff81089bf0-ffffffff81089c1d: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff810914d0)
Location: arch/x86/mm/hugetlbpage.c:66
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_pte_range
  - mm/hugetlb.c:follow_huge_pmd
```
**Symbols:**

```
ffffffff810914d0-ffffffff810914fd: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81090e00)
Location: arch/x86/mm/hugetlbpage.c:65
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:apply_to_pte_range
  - mm/hugetlb.c:follow_huge_pmd
```
**Symbols:**

```
ffffffff81090e00-ffffffff81090e2d: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff810917d0)
Location: arch/x86/mm/hugetlbpage.c:65
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/gup.c:gup_pgd_range
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:apply_to_pte_range
  - mm/hugetlb.c:follow_huge_pmd
```
**Symbols:**

```
ffffffff810917d0-ffffffff810917fd: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff810a1350)
Location: arch/x86/mm/hugetlbpage.c:65
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/gup.c:gup_pgd_range
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:apply_to_pte_range
  - mm/hugetlb.c:follow_huge_pmd
```
**Symbols:**

```
ffffffff810a1350-ffffffff810a137d: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff810b5460)
Location: arch/x86/mm/hugetlbpage.c:65
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/gup.c:gup_pgd_range
  - mm/memory.c:apply_to_pte_range
  - mm/hugetlb.c:follow_huge_pmd
```
**Symbols:**

```
ffffffff810b5460-ffffffff810b5498: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff810d03e0)
Location: arch/x86/mm/hugetlbpage.c:27
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/memory.c:apply_to_pte_range
```
**Symbols:**

```
ffffffff810d03e0-ffffffff810d0424: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff810d3a00)
Location: arch/x86/mm/hugetlbpage.c:27
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff810d3a00-ffffffff810d3a44: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff810dc190)
Location: arch/x86/mm/hugetlbpage.c:27
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff810dc190-ffffffff810dc1d4: pmd_huge (STB_GLOBAL)
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
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b113c)
Location: arch/arm64/mm/hugetlbpage.c:42
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_pte_offset
Direct callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:stage2_wp_range
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_get_leaf_entry
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:follow_huge_pmd
```
**Symbols:**

```
ffff8000100b0a58-ffff8000100b0a90: pmd_huge (STB_GLOBAL)
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
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000095af8)
Location: arch/powerpc/include/asm/book3s/64/pgtable-64k.h:17
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_clear_huge
```
```
In mm/gup.c (c0000000003b69d0)
Location: arch/powerpc/include/asm/book3s/64/pgtable-64k.h:17
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (c0000000003bb010)
Location: arch/powerpc/include/asm/book3s/64/pgtable-64k.h:17
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_page_range
```
```
In mm/hugetlb.c (c0000000004104d4)
Location: arch/powerpc/include/asm/book3s/64/pgtable-64k.h:17
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/hugetlbpage.c (ffffffe0000ba5f4)
Location: arch/riscv/mm/hugetlbpage.c:11
Inline: False
Direct callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_offset
```
**Symbols:**

```
ffffffe0000ba5f4-ffffffe0000ba620: pmd_huge (STB_GLOBAL)
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
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81088bb0)
Location: arch/x86/mm/hugetlbpage.c:67
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/gup.c:gup_pud_range
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_offset
```
**Symbols:**

```
ffffffff81088bb0-ffffffff81088bdd: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81077810)
Location: arch/x86/mm/hugetlbpage.c:67
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_offset
```
**Symbols:**

```
ffffffff81077810-ffffffff81077835: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81088b60)
Location: arch/x86/mm/hugetlbpage.c:67
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/gup.c:gup_pud_range
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_offset
```
**Symbols:**

```
ffffffff81088b60-ffffffff81088b8d: pmd_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pmd_huge(pmd_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff8108ae00)
Location: arch/x86/mm/hugetlbpage.c:67
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - mm/gup.c:gup_pud_range
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pte_offset
```
**Symbols:**

```
ffffffff8108ae00-ffffffff8108ae2d: pmd_huge (STB_GLOBAL)
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
