# Function: <code>pte_mkyoung</code>

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
In mm/gup.c (ffffffff811ba72f)
Location: arch/x86/include/asm/pgtable.h:223
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811bf678)
Location: arch/x86/include/asm/pgtable.h:223
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:223
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
In mm/gup.c (ffffffff811d4dac)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811daf41)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/hugetlb.c (ffffffff811fd273)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff811e4deb)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811eab54)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/hugetlb.c (ffffffff8120dd42)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff811ef3b3)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f5ba5)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/hugetlb.c (ffffffff8121783a)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff8120650e)
Location: arch/x86/include/asm/pgtable.h:309
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120d68c)
Location: arch/x86/include/asm/pgtable.h:309
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
```
```
In mm/hugetlb.c (ffffffff812325a1)
Location: arch/x86/include/asm/pgtable.h:309
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff812267d0)
Location: arch/x86/include/asm/pgtable.h:319
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122e387)
Location: arch/x86/include/asm/pgtable.h:319
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
```
```
In mm/hugetlb.c (ffffffff81255596)
Location: arch/x86/include/asm/pgtable.h:319
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff8123ab18)
Location: arch/x86/include/asm/pgtable.h:321
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124217d)
Location: arch/x86/include/asm/pgtable.h:321
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/hugetlb.c (ffffffff81269971)
Location: arch/x86/include/asm/pgtable.h:321
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff8124be53)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812549c9)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
```
```
In mm/hugetlb.c (ffffffff81284aaa)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff8125a343)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81262f29)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
```
```
In mm/hugetlb.c (ffffffff8129464a)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff81288833)
Location: arch/x86/include/asm/pgtable.h:360
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129239e)
Location: arch/x86/include/asm/pgtable.h:360
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:finish_mkwrite_fault
```
```
In mm/hugetlb.c (ffffffff812c7a3c)
Location: arch/x86/include/asm/pgtable.h:360
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff8129250d)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129cc4e)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:finish_mkwrite_fault
```
```
In mm/hugetlb.c (ffffffff812d35a9)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff81297fb8)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a233d)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:wp_page_reuse
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff812da3ca)
Location: arch/x86/include/asm/pgtable.h:359
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff812d89f8)
Location: arch/x86/include/asm/pgtable.h:330
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e36ad)
Location: arch/x86/include/asm/pgtable.h:330
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff813212bf)
Location: arch/x86/include/asm/pgtable.h:330
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff81338a24)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81344a83)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff8138e2f4)
Location: arch/x86/include/asm/pgtable.h:333
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff813b02a0)
Location: arch/x86/include/asm/pgtable.h:350
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813bcc84)
Location: arch/x86/include/asm/pgtable.h:350
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffff8140ceeb)
Location: arch/x86/include/asm/pgtable.h:350
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff813e4806)
Location: arch/x86/include/asm/pgtable.h:351
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813f15bc)
Location: arch/x86/include/asm/pgtable.h:351
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:finish_mkwrite_fault
```
```
In mm/hugetlb.c (ffffffff814402b2)
Location: arch/x86/include/asm/pgtable.h:351
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff8140f06b)
Location: arch/x86/include/asm/pgtable.h:450
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81420a98)
Location: arch/x86/include/asm/pgtable.h:450
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:finish_mkwrite_fault
```
```
In mm/hugetlb.c (ffffffff8147a0d4)
Location: arch/x86/include/asm/pgtable.h:450
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In arch/arm64/mm/hugetlbpage.c (ffff8000100b1474)
Location: arch/arm64/include/asm/pgtable.h:175
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_access_flags
  - arch/arm64/mm/hugetlbpage.c:get_clear_flush
```
```
In virt/kvm/arm/mmu.c (ffff8000100cc4c0)
Location: arch/arm64/include/asm/pgtable.h:175
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
```
```
In mm/gup.c (ffff8000102f1db4)
Location: arch/arm64/include/asm/pgtable.h:175
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102f9ed4)
Location: arch/arm64/include/asm/pgtable.h:175
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/hugetlb.c (ffff800010332f58)
Location: arch/arm64/include/asm/pgtable.h:175
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/huge_memory.c (ffff800010357768)
Location: arch/arm64/include/asm/pgtable.h:175
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
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
In mm/gup.c (c05144b0)
Location: arch/arm/include/asm/pgtable.h:306
Inline: True
```
```
In mm/memory.c (c051be28)
Location: arch/arm/include/asm/pgtable.h:306
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011caa8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:668
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
```
```
In mm/gup.c (c0000000003b661c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:668
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c422c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:668
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
```
```
In mm/hugetlb.c (c00000000040ee78)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:668
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/huge_memory.c (c00000000043fa30)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:668
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
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
In mm/gup.c (ffffffe000204910)
Location: arch/riscv/include/asm/pgtable.h:271
Inline: True
```
```
In mm/memory.c (ffffffe000209970)
Location: arch/riscv/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/hugetlb.c (ffffffe00022f5d6)
Location: arch/riscv/include/asm/pgtable.h:271
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
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
In mm/gup.c (ffffffff81252993)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125b579)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
```
```
In mm/hugetlb.c (ffffffff8128cc2a)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff8124563f)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124d860)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/hugetlb.c (ffffffff8127ea52)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff81250733)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81259319)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
```
```
In mm/hugetlb.c (ffffffff8128aa3a)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/gup.c (ffffffff812600b1)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81268d19)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
```
```
In mm/hugetlb.c (ffffffff8129a82f)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
</details>
</li>
</ul>

## Differences
