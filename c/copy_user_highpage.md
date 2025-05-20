# Function: <code>copy_user_highpage</code>

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
In mm/memory.c (ffffffff811bc4ca)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
```
```
In mm/ksm.c (ffffffff811e6d52)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff811f54b2)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In mm/memory.c (ffffffff811ddd92)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81205d9e)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff81216bb9)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8121a41d)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (ffffffff811edba8)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81217dae)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff81229164)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8122cf93)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/memory.c (ffffffff811f8b0a)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812239b2)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff81235567)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812384fc)
Location: include/linux/highmem.h:225
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (ffffffff81210e68)
Location: include/linux/highmem.h:226
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff8123eff2)
Location: include/linux/highmem.h:226
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff81253f28)
Location: include/linux/highmem.h:226
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81259a20)
Location: include/linux/highmem.h:226
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff812318ea)
Location: include/linux/highmem.h:226
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:wp_page_copy
Direct callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/ksm.c (ffffffff8126279e)
Location: include/linux/highmem.h:226
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff8127391b)
Location: include/linux/highmem.h:226
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127c39e)
Location: include/linux/highmem.h:226
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812291d0-ffffffff8122922e: copy_user_highpage.isra.83 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff812450ca)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:wp_page_copy
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/ksm.c (ffffffff8127701e)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff81287ebe)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff81290a41)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8123c860-ffffffff8123c8be: copy_user_highpage.isra.78 (STB_LOCAL)
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
In mm/memory.c (ffffffff81257096)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff8129287c)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff812a2ae1)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a9d81)
Location: include/linux/highmem.h:250
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
In mm/memory.c (ffffffff81265626)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812a25ff)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff812b3fd4)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bb2f1)
Location: include/linux/highmem.h:250
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
In mm/memory.c (ffffffff81295a20)
Location: include/linux/highmem.h:319
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_cow_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812d6d26)
Location: include/linux/highmem.h:319
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff812f0545)
Location: include/linux/highmem.h:319
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_copy
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
In mm/memory.c (ffffffff812a0795)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:do_cow_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812e28b6)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff812fbcf7)
Location: include/linux/highmem.h:250
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff812a60d5)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
Direct callers:
  - mm/memory.c:do_fault
```
```
In mm/ksm.c (ffffffff812ea046)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff81302c41)
Location: include/linux/highmem.h:250
Inline: True
```
**Symbols:**

```
ffffffff8129c880-ffffffff8129c8e1: copy_user_highpage.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff812e7565)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_pte_range
Direct callers:
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81331f68)
Location: include/linux/highmem.h:236
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff8134c701)
Location: include/linux/highmem.h:236
Inline: True
```
**Symbols:**

```
ffffffff812dd5b0-ffffffff812dd611: copy_user_highpage.constprop.0 (STB_LOCAL)
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
In mm/memory.c (ffffffff8134882e)
Location: include/linux/highmem.h:307
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
```
```
In mm/ksm.c (ffffffff813a32f1)
Location: include/linux/highmem.h:307
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff813c3f85)
Location: include/linux/highmem.h:307
Inline: True
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
In mm/memory.c (ffffffff813c0d1a)
Location: include/linux/highmem.h:307
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:do_fault
  - mm/memory.c:copy_present_pte
```
```
In mm/khugepaged.c (ffffffff81447729)
Location: include/linux/highmem.h:307
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f031d)
Location: include/linux/highmem.h:303
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
  - mm/memory.c:copy_present_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141bb5c)
Location: include/linux/highmem.h:303
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:copy_present_pte
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
In mm/memory.c (ffff8000102fc074)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffff800010341ff0)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffff80001035567c)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffff80001035e598)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (c0000000003c77b8)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (c00000000041f834)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (c00000000043cc98)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (c000000000445fbc)
Location: include/linux/highmem.h:250
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
In mm/memory.c (ffffffe00020b620)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffe0002362b6)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
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
In mm/memory.c (ffffffff8125dc76)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff8129abdf)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff812ac5b4)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b38d1)
Location: include/linux/highmem.h:250
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
In mm/memory.c (ffffffff812500c6)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff8128c79f)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff8129e661)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a688b)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (ffffffff8125ba16)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812989ef)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff812aa3c4)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b16e1)
Location: include/linux/highmem.h:250
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
In mm/memory.c (ffffffff8126b3c3)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812a879f)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff812ba722)
Location: include/linux/highmem.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c1a1f)
Location: include/linux/highmem.h:250
Inline: True
```
</details>
</li>
</ul>

## Differences
