# Function: <code>ptep_set_access_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070f50)
Location: arch/x86/mm/pgtable.c:409
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:handle_mm_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_fault
```
**Symbols:**

```
ffffffff81070f50-ffffffff81070f7f: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070e90)
Location: arch/x86/mm/pgtable.c:413
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81070e90-ffffffff81070ebf: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81074a10)
Location: arch/x86/mm/pgtable.c:413
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81074a10-ffffffff81074a3f: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81073f60)
Location: arch/x86/mm/pgtable.c:423
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81073f60-ffffffff81073f8f: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81079990)
Location: arch/x86/mm/pgtable.c:425
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81079990-ffffffff810799b3: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107c560)
Location: arch/x86/mm/pgtable.c:430
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff8107c560-ffffffff8107c583: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81082f50)
Location: arch/x86/mm/pgtable.c:496
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81082f50-ffffffff81082f7e: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086bb0)
Location: arch/x86/mm/pgtable.c:483
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81086bb0-ffffffff81086be6: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810878a0)
Location: arch/x86/mm/pgtable.c:479
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff810878a0-ffffffff810878d6: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089cb0)
Location: arch/x86/mm/pgtable.c:486
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_shared
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81089cb0-ffffffff81089cf1: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089f30)
Location: arch/x86/mm/pgtable.c:486
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_shared
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81089f30-ffffffff81089f71: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108ab90)
Location: arch/x86/mm/pgtable.c:486
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_reuse
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff8108ab90-ffffffff8108abd1: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8109a130)
Location: arch/x86/mm/pgtable.c:486
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff8109a130-ffffffff8109a171: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ad210)
Location: arch/x86/mm/pgtable.c:486
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
```
**Symbols:**

```
ffffffff810ad210-ffffffff810ad27b: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c72c0)
Location: arch/x86/mm/pgtable.c:490
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
```
**Symbols:**

```
ffffffff810c72c0-ffffffff810c732b: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810caa10)
Location: arch/x86/mm/pgtable.c:490
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
```
**Symbols:**

```
ffffffff810caa10-ffffffff810caa7b: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d2f60)
Location: arch/x86/mm/pgtable.c:502
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
```
**Symbols:**

```
ffffffff810d2f60-ffffffff810d2fcb: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/fault.c (ffff8000100ad210)
Location: arch/arm64/mm/fault.c:197
Inline: False
Direct callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_access_flags
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
**Symbols:**

```
ffff8000100ad210-ffff8000100ad308: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (c0525484)
Location: mm/pgtable-generic.c:55
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
```
**Symbols:**

```
c0525484-c052552c: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/pgtable.c (c000000000087eb0)
Location: arch/powerpc/mm/pgtable.c:208
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
```
**Symbols:**

```
c000000000087eb0-c00000000008800c: ptep_set_access_flags (STB_GLOBAL)
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
In mm/memory.c (ffffffe000209974)
Location: arch/riscv/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffe00023179a)
Location: arch/riscv/include/asm/pgtable.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
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
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810868a0)
Location: arch/x86/mm/pgtable.c:479
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff810868a0-ffffffff810868d6: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81075580)
Location: arch/x86/mm/pgtable.c:479
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81075580-ffffffff810755a5: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086850)
Location: arch/x86/mm/pgtable.c:479
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81086850-ffffffff81086886: ptep_set_access_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ptep_set_access_flags(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep, pte_t entry, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81088980)
Location: arch/x86/mm/pgtable.c:479
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:insert_pfn
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffffffff81088980-ffffffff810889b6: ptep_set_access_flags (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
