# Function: <code>pte_mkspecial</code>

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
In arch/x86/xen/mmu.c (ffffffff8101e963)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In mm/memory.c (ffffffff811bf85a)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/huge_memory.c (ffffffff811f8442)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page_pmd
```
```
In mm/userfaultfd.c (ffffffff81207eba)
Location: arch/x86/include/asm/pgtable.h:253
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In drivers/xen/xlate_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:253
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
In arch/x86/xen/mmu.c (ffffffff8101dd83)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In mm/memory.c (ffffffff811db93d)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range
```
```
In mm/huge_memory.c (ffffffff812164fc)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/userfaultfd.c (ffffffff8122d859)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In drivers/xen/xlate_mmu.c (ffffffff81527ef7)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu.c (ffffffff8101e473)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In mm/memory.c (ffffffff811eb856)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range
```
```
In mm/ksm.c (ffffffff81216577)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff81228aa3)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/userfaultfd.c (ffffffff8123fd97)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In drivers/xen/xlate_mmu.c (ffffffff81554464)
Location: arch/x86/include/asm/pgtable.h:267
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu.c (ffffffff8101a98d)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In mm/memory.c (ffffffff811f63d1)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
```
```
In mm/ksm.c (ffffffff81221cb1)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff812320fb)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff8124bc76)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In drivers/xen/xlate_mmu.c (ffffffff81568fa3)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu.c (ffffffff8101b28d)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In mm/memory.c (ffffffff8120e059)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
```
```
In mm/ksm.c (ffffffff8123cfab)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff81252f46)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/userfaultfd.c (ffffffff8126bff3)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In drivers/xen/xlate_mmu.c (ffffffff815cd153)
Location: arch/x86/include/asm/pgtable.h:339
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu.c (ffffffff8101bc4d)
Location: arch/x86/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff8122e93a)
Location: arch/x86/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
```
```
In mm/ksm.c (ffffffff8126094d)
Location: arch/x86/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff8127747e)
Location: arch/x86/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/userfaultfd.c (ffffffff81290a44)
Location: arch/x86/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In drivers/xen/xlate_mmu.c (ffffffff816057cb)
Location: arch/x86/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu_pv.c (ffffffff8102162d)
Location: arch/x86/include/asm/pgtable.h:351
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff81242876)
Location: arch/x86/include/asm/pgtable.h:351
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
```
```
In mm/ksm.c (ffffffff812750ae)
Location: arch/x86/include/asm/pgtable.h:351
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff81288c8d)
Location: arch/x86/include/asm/pgtable.h:351
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff812a5a28)
Location: arch/x86/include/asm/pgtable.h:351
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In drivers/xen/xlate_mmu.c (ffffffff816208ab)
Location: arch/x86/include/asm/pgtable.h:351
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu_pv.c (ffffffff81023244)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff8124fe73)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
```
```
In mm/ksm.c (ffffffff8128f962)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff812a38f2)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff812c1119)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In drivers/xen/xlate_mmu.c (ffffffff81654073)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu_pv.c (ffffffff81023b84)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff8125e416)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
```
```
In mm/ksm.c (ffffffff8129f702)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff812b4df2)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff812d3069)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In drivers/xen/xlate_mmu.c (ffffffff81676613)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu_pv.c (ffffffff81026292)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff8128e5af)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pte_range
  - mm/memory.c:insert_pfn
```
```
In mm/ksm.c (ffffffff812d3d0a)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff812e8c77)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff81307e6d)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage_pte
```
```
In drivers/xen/xlate_mmu.c (ffffffff817270d7)
Location: arch/x86/include/asm/pgtable.h:390
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu_pv.c (ffffffff810269a2)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff81299208)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pte_range
  - mm/memory.c:insert_pfn
```
```
In mm/vmalloc.c (ffffffff812b2295)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/ksm.c (ffffffff812df702)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff812f40e1)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff81313c1d)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
```
```
In drivers/xen/xlate_mmu.c (ffffffff81743625)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu_pv.c (ffffffff81028612)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff8129e497)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
```
```
In mm/vmalloc.c (ffffffff812b7966)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/ksm.c (ffffffff812e8032)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff812fa393)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff81319db1)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
```
```
In drivers/xen/xlate_mmu.c (ffffffff81727011)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu_pv.c (ffffffff8102cd2b)
Location: arch/x86/include/asm/pgtable.h:360
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff812df5d3)
Location: arch/x86/include/asm/pgtable.h:360
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
```
```
In mm/vmalloc.c (ffffffff812fa096)
Location: arch/x86/include/asm/pgtable.h:360
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/ksm.c (ffffffff8132ff44)
Location: arch/x86/include/asm/pgtable.h:360
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff813441f3)
Location: arch/x86/include/asm/pgtable.h:360
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff81366b61)
Location: arch/x86/include/asm/pgtable.h:360
Inline: True
```
```
In drivers/xen/xlate_mmu.c (ffffffff817a6091)
Location: arch/x86/include/asm/pgtable.h:360
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu_pv.c (ffffffff81031c70)
Location: arch/x86/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff8133fb59)
Location: arch/x86/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
```
```
In mm/vmalloc.c (ffffffff813603ee)
Location: arch/x86/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/ksm.c (ffffffff813a0339)
Location: arch/x86/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff813b96b5)
Location: arch/x86/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff813e3f9a)
Location: arch/x86/include/asm/pgtable.h:363
Inline: True
```
```
In drivers/xen/xlate_mmu.c (ffffffff818e004a)
Location: arch/x86/include/asm/pgtable.h:363
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu_pv.c (ffffffff81039540)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff813b7a83)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
```
```
In mm/vmalloc.c (ffffffff813dc3ca)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/ksm.c (ffffffff8141f22f)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff8143b99e)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff8146ba0a)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a344eb)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu_pv.c (ffffffff81039480)
Location: arch/x86/include/asm/pgtable.h:381
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff813ec8e8)
Location: arch/x86/include/asm/pgtable.h:381
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:insert_pfn
```
```
In mm/vmalloc.c (ffffffff81410caa)
Location: arch/x86/include/asm/pgtable.h:381
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/ksm.c (ffffffff81453d01)
Location: arch/x86/include/asm/pgtable.h:381
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff81471384)
Location: arch/x86/include/asm/pgtable.h:381
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814a08b9)
Location: arch/x86/include/asm/pgtable.h:381
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_pte_zeropage
```
```
In drivers/xen/xlate_mmu.c (ffffffff81a7df0a)
Location: arch/x86/include/asm/pgtable.h:381
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu_pv.c (ffffffff8103f930)
Location: arch/x86/include/asm/pgtable.h:484
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff8141fc4e)
Location: arch/x86/include/asm/pgtable.h:484
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
```
```
In mm/vmalloc.c (ffffffff8143eed3)
Location: arch/x86/include/asm/pgtable.h:484
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:484
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a0f1e)
Location: arch/x86/include/asm/pgtable.h:484
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814d1345)
Location: arch/x86/include/asm/pgtable.h:484
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_zeropage
```
```
In drivers/xen/xlate_mmu.c (ffffffff81ad01e6)
Location: arch/x86/include/asm/pgtable.h:484
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In mm/memory.c (ffff8000102f5e68)
Location: arch/arm64/include/asm/pgtable.h:180
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
```
```
In mm/ksm.c (ffff80001033ef2c)
Location: arch/arm64/include/asm/pgtable.h:180
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffff800010356188)
Location: arch/arm64/include/asm/pgtable.h:180
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffff800010378c48)
Location: arch/arm64/include/asm/pgtable.h:180
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In drivers/xen/xlate_mmu.c (ffff80001083f27c)
Location: arch/arm64/include/asm/pgtable.h:180
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
Location: arch/arm/include/asm/pgtable-2level.h:214
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/arm/include/asm/pgtable-2level.h:214
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/arm/include/asm/pgtable-2level.h:214
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
In mm/memory.c (c0000000003bd59c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:673
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
```
```
In mm/ksm.c (c00000000041af2c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:673
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (c00000000043c9ec)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:673
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (c00000000046b924)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:673
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In mm/memory.c (ffffffe000207144)
Location: arch/riscv/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
```
```
In mm/ksm.c (ffffffe000234b0e)
Location: arch/riscv/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/userfaultfd.c (ffffffe0002504e8)
Location: arch/riscv/include/asm/pgtable.h:281
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In arch/x86/xen/mmu_pv.c (ffffffff81023ce4)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff81256a66)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
```
```
In mm/ksm.c (ffffffff81297ce2)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff812ad3d2)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff812cb649)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In drivers/xen/xlate_mmu.c (ffffffff8163c303)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In mm/memory.c (ffffffff8124941f)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
```
```
In mm/ksm.c (ffffffff81289896)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff8129e29e)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff812bc4f4)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
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
In arch/x86/xen/mmu_pv.c (ffffffff81023b44)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff81254806)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
```
```
In mm/ksm.c (ffffffff81295af2)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff812ab1e2)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff812c9459)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In drivers/xen/xlate_mmu.c (ffffffff8166a453)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/x86/xen/mmu_pv.c (ffffffff81023fd4)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
```
```
In mm/memory.c (ffffffff81264297)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
```
```
In mm/ksm.c (ffffffff812a58ec)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff812bb532)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff812da139)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In drivers/xen/xlate_mmu.c (ffffffff81684a13)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
```
</details>
</li>
</ul>

## Differences
