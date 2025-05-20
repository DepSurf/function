# Function: <code>pud_huge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81072ba0)
Location: arch/x86/mm/hugetlbpage.c:68
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - mm/gup.c:follow_page_mask
  - mm/hugetlb.c:huge_pte_offset
```
**Symbols:**

```
ffffffff81072ba0-ffffffff81072bb9: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81073430)
Location: arch/x86/mm/hugetlbpage.c:68
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - mm/gup.c:follow_page_mask
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:huge_pte_offset
```
**Symbols:**

```
ffffffff81073430-ffffffff81073449: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81076fe0)
Location: arch/x86/mm/hugetlbpage.c:68
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - mm/gup.c:follow_page_mask
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:huge_pte_offset
```
**Symbols:**

```
ffffffff81076fe0-ffffffff81076ff9: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81075800)
Location: arch/x86/mm/hugetlbpage.c:71
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - mm/gup.c:__get_user_pages_fast
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:huge_pte_offset
```
**Symbols:**

```
ffffffff81075800-ffffffff81075819: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff8107ba40)
Location: arch/x86/mm/hugetlbpage.c:73
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:huge_pte_offset
```
**Symbols:**

```
ffffffff8107ba40-ffffffff8107ba59: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff8107e830)
Location: arch/x86/mm/hugetlbpage.c:73
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/gup.c:gup_pgd_range
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:huge_pte_offset
```
**Symbols:**

```
ffffffff8107e830-ffffffff8107e849: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff810853b0)
Location: arch/x86/mm/hugetlbpage.c:73
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/gup.c:gup_pud_range
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:huge_pte_offset
```
**Symbols:**

```
ffffffff810853b0-ffffffff810853c9: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81088fb0)
Location: arch/x86/mm/hugetlbpage.c:73
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/gup.c:gup_pud_range
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:huge_pte_offset
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff81088fb0-ffffffff81088fc9: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81089c20)
Location: arch/x86/mm/hugetlbpage.c:73
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/gup.c:gup_pud_range
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:huge_pte_offset
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff81089c20-ffffffff81089c39: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81091500)
Location: arch/x86/mm/hugetlbpage.c:72
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:apply_to_p4d_range
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff81091500-ffffffff81091519: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81090e30)
Location: arch/x86/mm/hugetlbpage.c:71
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff81090e30-ffffffff81090e49: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81091800)
Location: arch/x86/mm/hugetlbpage.c:71
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/gup.c:gup_pgd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff81091800-ffffffff81091819: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff810a1380)
Location: arch/x86/mm/hugetlbpage.c:71
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/gup.c:gup_pgd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff810a1380-ffffffff810a1399: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff810b54a0)
Location: arch/x86/mm/hugetlbpage.c:71
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/gup.c:gup_pgd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff810b54a0-ffffffff810b54be: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff810d0440)
Location: arch/x86/mm/hugetlbpage.c:38
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/gup.c:gup_pgd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff810d0440-ffffffff810d0484: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff810d3a60)
Location: arch/x86/mm/hugetlbpage.c:38
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/gup.c:gup_pgd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff810d3a60-ffffffff810d3aa4: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff810dc1f0)
Location: arch/x86/mm/hugetlbpage.c:38
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/gup.c:gup_pgd_range
  - mm/memory.c:apply_to_pmd_range
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff810dc1f0-ffffffff810dc234: pud_huge (STB_GLOBAL)
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
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b1108)
Location: arch/arm64/mm/hugetlbpage.c:47
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_pte_offset
Direct callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:stage2_wp_range
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_get_leaf_entry
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_mask
  - mm/memory.c:apply_to_page_range
```
**Symbols:**

```
ffff8000100b0a90-ffff8000100b0ac8: pud_huge (STB_GLOBAL)
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
In arch/powerpc/mm/book3s64/radix_pgtable.c (c0000000000958d8)
Location: arch/powerpc/include/asm/book3s/64/pgtable-64k.h:25
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pud_clear_huge
```
```
In mm/gup.c (c0000000003b6860)
Location: arch/powerpc/include/asm/book3s/64/pgtable-64k.h:25
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (c0000000003c5798)
Location: arch/powerpc/include/asm/book3s/64/pgtable-64k.h:25
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/hugetlbpage.c (ffffffe0000ba5c8)
Location: arch/riscv/mm/hugetlbpage.c:5
Inline: False
Direct callers:
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:huge_pte_offset
```
**Symbols:**

```
ffffffe0000ba5c8-ffffffe0000ba5f4: pud_huge (STB_GLOBAL)
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
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81088be0)
Location: arch/x86/mm/hugetlbpage.c:73
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/gup.c:gup_pud_range
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:huge_pte_offset
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff81088be0-ffffffff81088bf9: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81077840)
Location: arch/x86/mm/hugetlbpage.c:73
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/gup.c:gup_pud_range
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:huge_pte_offset
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff81077840-ffffffff81077855: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff81088b90)
Location: arch/x86/mm/hugetlbpage.c:73
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/gup.c:gup_pud_range
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:huge_pte_offset
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff81088b90-ffffffff81088ba9: pud_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pud_huge(pud_t pud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/hugetlbpage.c (ffffffff8108ae30)
Location: arch/x86/mm/hugetlbpage.c:73
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pud_set_huge
  - mm/gup.c:gup_pud_range
  - mm/memory.c:apply_to_page_range
  - mm/hugetlb.c:huge_pte_offset
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff8108ae30-ffffffff8108ae49: pud_huge (STB_GLOBAL)
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
