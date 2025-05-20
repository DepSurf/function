# Function: <code>pte_protnone</code>

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
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
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
In arch/x86/mm/gup.c (ffffffff810717d7)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (ffffffff811d4a67)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811daead)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/mprotect.c (ffffffff811e4b1d)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In arch/x86/mm/gup.c (ffffffff81075367)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (ffffffff811e49ab)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811eaab6)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/mprotect.c (ffffffff811f4b38)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:538
Inline: True
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
In mm/gup.c (ffffffff811f0ab9)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f5b06)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff811ff9fa)
Location: arch/x86/include/asm/pgtable.h:677
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:677
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
In mm/gup.c (ffffffff8120564a)
Location: arch/x86/include/asm/pgtable.h:687
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120d5ee)
Location: arch/x86/include/asm/pgtable.h:687
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff81218125)
Location: arch/x86/include/asm/pgtable.h:687
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:687
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
In mm/gup.c (ffffffff81226ab1)
Location: arch/x86/include/asm/pgtable.h:729
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122e2e5)
Location: arch/x86/include/asm/pgtable.h:729
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff81239242)
Location: arch/x86/include/asm/pgtable.h:729
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:729
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
In mm/gup.c (ffffffff81239bb2)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812420cb)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff8124d7c9)
Location: arch/x86/include/asm/pgtable.h:754
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:754
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
In mm/gup.c (ffffffff8124ade2)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125491b)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff8125f7d2)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
```
```
In mm/hmm.c (ffffffff812c3d18)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/gup.c (ffffffff812592d2)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81262e7b)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff8126dfe2)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
```
```
In mm/hmm.c (ffffffff812d5a72)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/gup.c (ffffffff81287fe0)
Location: arch/x86/include/asm/pgtable.h:807
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129232c)
Location: arch/x86/include/asm/pgtable.h:807
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff8129e7f8)
Location: arch/x86/include/asm/pgtable.h:807
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:807
Inline: True
```
```
In mm/hmm.c (ffffffff8130b6d7)
Location: arch/x86/include/asm/pgtable.h:807
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/gup.c (ffffffff81291cc0)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129cbdc)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff812a9bae)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
```
```
In mm/hmm.c (ffffffff813175a0)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/gup.c (ffffffff812977e0)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a22cb)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff812af039)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
```
```
In mm/hmm.c (ffffffff8131d2a0)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/gup.c (ffffffff812d81a0)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e363b)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff812f0832)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
```
```
In mm/hmm.c (ffffffff8136a63b)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/gup.c (ffffffff8133809a)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81344a12)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff81353ba7)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
```
```
In mm/hmm.c (ffffffff813e81fe)
Location: arch/x86/include/asm/pgtable.h:775
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/gup.c (ffffffff813af837)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813bcc13)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff813ce062)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/hmm.c (ffffffff8147010b)
Location: arch/x86/include/asm/pgtable.h:792
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/gup.c (ffffffff813e3fbb)
Location: arch/x86/include/asm/pgtable.h:793
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813f1567)
Location: arch/x86/include/asm/pgtable.h:793
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff81402901)
Location: arch/x86/include/asm/pgtable.h:793
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/hmm.c (ffffffff814a48e1)
Location: arch/x86/include/asm/pgtable.h:793
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
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
In mm/gup.c (ffffffff8140e81b)
Location: arch/x86/include/asm/pgtable.h:1008
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81420a58)
Location: arch/x86/include/asm/pgtable.h:1008
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff8142ef34)
Location: arch/x86/include/asm/pgtable.h:1008
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/hmm.c (ffffffff814d5911)
Location: arch/x86/include/asm/pgtable.h:1008
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
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
In mm/gup.c (ffff8000102f1130)
Location: arch/arm64/include/asm/pgtable.h:340
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (0)
Location: arch/arm64/include/asm/pgtable.h:340
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/arm64/include/asm/pgtable.h:340
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/arm64/include/asm/pgtable.h:340
Inline: True
```
```
In mm/huge_memory.c (ffff80001035828c)
Location: arch/arm64/include/asm/pgtable.h:340
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (ffff80001037b540)
Location: arch/arm64/include/asm/pgtable.h:340
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
Location: include/asm-generic/pgtable.h:1026
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:1026
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:1026
Inline: True
```
```
In mm/ksm.c (0)
Location: include/asm-generic/pgtable.h:1026
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:1026
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
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011d834)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:519
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
```
```
In mm/gup.c (c0000000003b6a3c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:519
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c3ee0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:519
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (c0000000003d2550)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:519
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/ksm.c (c000000000419f14)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:519
Inline: True
```
```
In mm/huge_memory.c (c0000000004409bc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:519
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/hmm.c (c00000000046fb74)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:519
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
Location: include/asm-generic/pgtable.h:1026
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:1026
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:1026
Inline: True
```
```
In mm/ksm.c (0)
Location: include/asm-generic/pgtable.h:1026
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:1026
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
In mm/gup.c (ffffffff81251922)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125b4cb)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff81266632)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
```
```
In mm/hmm.c (ffffffff812ce052)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/gup.c (ffffffff812447f7)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124d7bd)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff81258d16)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
```
```
In mm/hmm.c (ffffffff812beec7)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/gup.c (ffffffff8124f6c2)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125926b)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff812643d2)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
```
```
In mm/hmm.c (ffffffff812cbe62)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/gup.c (ffffffff8125f032)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81268c6b)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff81273d92)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
```
```
In mm/hmm.c (ffffffff812dcbc0)
Location: arch/x86/include/asm/pgtable.h:771
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
</details>
</li>
</ul>

## Differences
