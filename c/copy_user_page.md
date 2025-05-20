# Function: <code>copy_user_page</code>

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
In mm/memory.c (ffffffff811bc4e5)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
```
```
In mm/ksm.c (ffffffff811e6d6b)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff811f5505)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In fs/dax.c (ffffffff8125ded3)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
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
In mm/memory.c (ffffffff811dde16)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81205ded)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff81216c57)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8121a494)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81287bd4)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
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
In mm/memory.c (ffffffff811edc30)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81217dff)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff81229205)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8122e893)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff8129c4b5)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In mm/memory.c (ffffffff811f8b61)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81223a03)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff812355c6)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81238580)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812ab6f4)
Location: arch/x86/include/asm/page.h:30
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In mm/memory.c (ffffffff81210eb1)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff8123f043)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff81253f72)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81259a6b)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff812cf201)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In mm/memory.c (ffffffff8123191a)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812627d2)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff8127394d)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127c3d0)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812f954f)
Location: arch/x86/include/asm/page.h:31
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
In mm/memory.c (ffffffff812450fa)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81277052)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff81287ef0)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff81290a73)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8130d71c)
Location: arch/x86/include/asm/page.h:31
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
In mm/memory.c (ffffffff812570c1)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812928b0)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff812a2b0c)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a9db0)
Location: arch/x86/include/asm/page.h:31
Inline: True
```
```
In fs/dax.c (ffffffff81335935)
Location: arch/x86/include/asm/page.h:31
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
In mm/memory.c (ffffffff81265651)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812a2633)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff812b3fff)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bb320)
Location: arch/x86/include/asm/page.h:31
Inline: True
```
```
In fs/dax.c (ffffffff81349535)
Location: arch/x86/include/asm/page.h:31
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
In mm/memory.c (ffffffff81295a49)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_cow_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812d6d58)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff812f0574)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_copy
```
```
In fs/dax.c (ffffffff8138c79d)
Location: arch/x86/include/asm/page.h:31
Inline: True
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
In mm/memory.c (ffffffff812a07bf)
Location: arch/x86/include/asm/page.h:31
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
In mm/ksm.c (ffffffff812e28e8)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff812fbd20)
Location: arch/x86/include/asm/page.h:31
Inline: True
```
```
In fs/dax.c (ffffffff8139decd)
Location: arch/x86/include/asm/page.h:31
Inline: True
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
In mm/memory.c (ffffffff812a60ff)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/ksm.c (ffffffff812ea078)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff81302c68)
Location: arch/x86/include/asm/page.h:31
Inline: True
```
```
In fs/dax.c (ffffffff813a76bf)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
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
In mm/memory.c (ffffffff812e758f)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_pte_range
```
```
In mm/ksm.c (ffffffff81331f9a)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff8134c728)
Location: arch/x86/include/asm/page.h:31
Inline: True
```
```
In fs/dax.c (ffffffff813f4d81)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
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
In mm/memory.c (ffffffff81348842)
Location: arch/x86/include/asm/page.h:31
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
In mm/ksm.c (ffffffff813a3305)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/khugepaged.c (ffffffff813c3f85)
Location: arch/x86/include/asm/page.h:31
Inline: True
```
```
In fs/dax.c (ffffffff8146795e)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
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
In mm/memory.c (ffffffff813c0d2e)
Location: arch/x86/include/asm/page.h:31
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
Location: arch/x86/include/asm/page.h:31
Inline: True
```
```
In fs/dax.c (ffffffff814f801e)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
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
In mm/memory.c (ffffffff813f0333)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
  - mm/memory.c:copy_present_pte
```
```
In fs/dax.c (ffffffff8152f21e)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
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
In mm/memory.c (ffffffff8141bb72)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:copy_present_pte
```
```
In fs/dax.c (ffffffff815640fe)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
</details>
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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void copy_user_page(void *vto, void *vfrom, long unsigned int vaddr, struct page *pg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/mem.c (c000000000087550)
Location: arch/powerpc/mm/mem.c:552
Inline: False
Direct callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
**Symbols:**

```
c000000000087550-c000000000087584: copy_user_page (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125dca1)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff8129ac13)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff812ac5df)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b3900)
Location: arch/x86/include/asm/page.h:31
Inline: True
```
```
In fs/dax.c (ffffffff81341b15)
Location: arch/x86/include/asm/page.h:31
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
In mm/memory.c (ffffffff812500f1)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff8128c7d3)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff8129e68c)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a68b4)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813325d3)
Location: arch/x86/include/asm/page.h:31
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
In mm/memory.c (ffffffff8125ba41)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff81298a23)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff812aa3ef)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b1710)
Location: arch/x86/include/asm/page.h:31
Inline: True
```
```
In fs/dax.c (ffffffff8133f5e5)
Location: arch/x86/include/asm/page.h:31
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
In mm/memory.c (ffffffff8126b3fe)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (ffffffff812a87e1)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff812ba759)
Location: arch/x86/include/asm/page.h:31
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c1a5c)
Location: arch/x86/include/asm/page.h:31
Inline: True
```
```
In fs/dax.c (ffffffff81352f91)
Location: arch/x86/include/asm/page.h:31
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
