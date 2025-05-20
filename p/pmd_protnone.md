# Function: <code>pmd_protnone</code>

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
In arch/x86/mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:508
Inline: True
```
```
In mm/gup.c (ffffffff811ba8db)
Location: arch/x86/include/asm/pgtable.h:508
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811bed5e)
Location: arch/x86/include/asm/pgtable.h:508
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff811f6223)
Location: arch/x86/include/asm/pgtable.h:508
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
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
In arch/x86/mm/gup.c (ffffffff81071cd6)
Location: arch/x86/include/asm/pgtable.h:544
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In mm/gup.c (ffffffff811d4fa8)
Location: arch/x86/include/asm/pgtable.h:544
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811dad47)
Location: arch/x86/include/asm/pgtable.h:544
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff81215cc9)
Location: arch/x86/include/asm/pgtable.h:544
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
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
In arch/x86/mm/gup.c (ffffffff81075846)
Location: arch/x86/include/asm/pgtable.h:544
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In mm/gup.c (ffffffff811e50b7)
Location: arch/x86/include/asm/pgtable.h:544
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811ea90f)
Location: arch/x86/include/asm/pgtable.h:544
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812282e3)
Location: arch/x86/include/asm/pgtable.h:544
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
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
In mm/gup.c (ffffffff811f0d80)
Location: arch/x86/include/asm/pgtable.h:683
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/memory.c (ffffffff811f5870)
Location: arch/x86/include/asm/pgtable.h:683
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812344fb)
Location: arch/x86/include/asm/pgtable.h:683
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
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
In mm/gup.c (ffffffff812058fd)
Location: arch/x86/include/asm/pgtable.h:693
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8120e8aa)
Location: arch/x86/include/asm/pgtable.h:693
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812523c2)
Location: arch/x86/include/asm/pgtable.h:693
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffffffff8126e5d5)
Location: arch/x86/include/asm/pgtable.h:693
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (ffffffff81226da9)
Location: arch/x86/include/asm/pgtable.h:735
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff8123005f)
Location: arch/x86/include/asm/pgtable.h:735
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812767c8)
Location: arch/x86/include/asm/pgtable.h:735
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffffffff81293212)
Location: arch/x86/include/asm/pgtable.h:735
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (ffffffff81239e2e)
Location: arch/x86/include/asm/pgtable.h:760
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81241d49)
Location: arch/x86/include/asm/pgtable.h:760
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff8128b60c)
Location: arch/x86/include/asm/pgtable.h:760
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffffffff812a7765)
Location: arch/x86/include/asm/pgtable.h:760
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (ffffffff8124b071)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff812546b3)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812a62c9)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffffffff812c4894)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (ffffffff81259561)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81262c13)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812b7799)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffffffff812d62a8)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_protnone(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81287620)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
```
```
In mm/memory.c (ffffffff81294bf1)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812ec94e)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffffffff8130b129)
Location: arch/x86/include/asm/pgtable.h:813
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pmd
```
**Symbols:**

```
ffffffff81287620-ffffffff8128765a: pmd_protnone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_protnone(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81291460)
Location: arch/x86/include/asm/pgtable.h:812
Inline: True
```
```
In mm/memory.c (ffffffff8129f471)
Location: arch/x86/include/asm/pgtable.h:812
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812f79df)
Location: arch/x86/include/asm/pgtable.h:812
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffffffff81316fe9)
Location: arch/x86/include/asm/pgtable.h:812
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pmd
```
**Symbols:**

```
ffffffff81291460-ffffffff8129149a: pmd_protnone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_protnone(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129a8d3)
Location: arch/x86/include/asm/pgtable.h:812
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff812a452d)
Location: arch/x86/include/asm/pgtable.h:812
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812fdfbf)
Location: arch/x86/include/asm/pgtable.h:812
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffffffff8131d67b)
Location: arch/x86/include/asm/pgtable.h:812
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812969b0-ffffffff812969e7: pmd_protnone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_protnone(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812db289)
Location: arch/x86/include/asm/pgtable.h:783
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff812e5766)
Location: arch/x86/include/asm/pgtable.h:783
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff81347b5f)
Location: arch/x86/include/asm/pgtable.h:783
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffffffff8136aa1b)
Location: arch/x86/include/asm/pgtable.h:783
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812d7230-ffffffff812d7267: pmd_protnone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_protnone(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133ae45)
Location: arch/x86/include/asm/pgtable.h:781
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff81347922)
Location: arch/x86/include/asm/pgtable.h:781
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff813bdb9f)
Location: arch/x86/include/asm/pgtable.h:781
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffffffff813e8bdc)
Location: arch/x86/include/asm/pgtable.h:781
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff81336bb0-ffffffff81336bef: pmd_protnone (STB_LOCAL)
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
In mm/gup.c (ffffffff813b0504)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
```
```
In mm/memory.c (ffffffff813bfcb0)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff8144034b)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
```
```
In mm/hmm.c (ffffffff81470b66)
Location: arch/x86/include/asm/pgtable.h:798
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (ffffffff813e76e3)
Location: arch/x86/include/asm/pgtable.h:799
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff813f4977)
Location: arch/x86/include/asm/pgtable.h:799
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff81475c0b)
Location: arch/x86/include/asm/pgtable.h:799
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
```
```
In mm/hmm.c (ffffffff814a5105)
Location: arch/x86/include/asm/pgtable.h:799
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (ffffffff81412361)
Location: arch/x86/include/asm/pgtable.h:1014
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff81420fab)
Location: arch/x86/include/asm/pgtable.h:1014
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff814a5553)
Location: arch/x86/include/asm/pgtable.h:1014
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
```
```
In mm/hmm.c (ffffffff814d5689)
Location: arch/x86/include/asm/pgtable.h:1014
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pmd
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
In mm/gup.c (0)
Location: arch/arm64/include/asm/pgtable.h:345
Inline: True
```
```
In mm/memory.c (0)
Location: arch/arm64/include/asm/pgtable.h:345
Inline: True
```
```
In mm/huge_memory.c (ffff80001035828c)
Location: arch/arm64/include/asm/pgtable.h:345
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffff80001037b540)
Location: arch/arm64/include/asm/pgtable.h:345
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:1031
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:1031
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
In mm/gup.c (c0000000003b6da0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1107
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (c0000000003c3ee0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1107
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (c0000000004409bc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1107
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (c00000000047084c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1107
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:1031
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:1031
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
In mm/gup.c (ffffffff81251bb1)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff8125b263)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812afd79)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffffffff812ce888)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (ffffffff8124493d)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8124d591)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812a1206)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffffffff812bf5a9)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (ffffffff8124f951)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81259003)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812adb89)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffffffff812cc698)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/gup.c (ffffffff8125f2db)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81268a03)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff812bdef2)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffffffff812dd3f8)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
