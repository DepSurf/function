# Function: <code>__pmd_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811beaa0)
Location: mm/memory.c:3498
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__get_locked_pte
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff811beaa0-ffffffff811bebca: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811da8e0)
Location: mm/memory.c:3693
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff811da8e0-ffffffff811daa34: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ea450)
Location: mm/memory.c:3748
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff811ea450-ffffffff811ea5a1: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f54d0)
Location: mm/memory.c:4018
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff811f54d0-ffffffff811f561f: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120e3a0)
Location: mm/memory.c:4196
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8120e3a0-ffffffff8120e516: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122eda0)
Location: mm/memory.c:4241
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8122eda0-ffffffff8122ef0d: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81241830)
Location: mm/memory.c:4031
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81241830-ffffffff8124199d: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812541b0)
Location: mm/memory.c:4080
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff812541b0-ffffffff8125431d: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81262710)
Location: mm/memory.c:4105
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81262710-ffffffff8126287d: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81292610)
Location: mm/memory.c:4478
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/vmalloc.c:vmap_p4d_range
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81292610-ffffffff8129277d: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129cec0)
Location: mm/memory.c:4701
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_p4d_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vmap_p4d_range
  - mm/ioremap.c:ioremap_page_range
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff8129cec0-ffffffff8129d0d6: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a25a0)
Location: mm/memory.c:4728
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pmd_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff812a25a0-ffffffff812a27cd: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e3910)
Location: mm/memory.c:4874
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_pmd_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff812e3910-ffffffff812e3b3b: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81344cc0)
Location: mm/memory.c:5216
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff81344cc0-ffffffff81344ebf: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bcef0)
Location: mm/memory.c:5296
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff813bcef0-ffffffff813bd0ef: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f1c30)
Location: mm/memory.c:5488
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/mprotect.c:change_p4d_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff813f1c30-ffffffff813f1e35: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141c920)
Location: mm/memory.c:5714
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:copy_p4d_range
  - mm/mprotect.c:change_p4d_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_share
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/userfaultfd.c:mm_alloc_pmd
```
**Symbols:**

```
ffffffff8141c920-ffffffff8141caba: __pmd_alloc (STB_GLOBAL)
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
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f9988)
Location: mm/memory.c:4105
Inline: False
Direct callers:
  - arch/arm64/mm/hugetlbpage.c:huge_pte_alloc
  - arch/arm64/mm/hugetlbpage.c:huge_pte_alloc
  - arch/arm64/mm/hugetlbpage.c:huge_pte_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffff8000102f9988-ffff8000102f9b0c: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c38e0)
Location: mm/memory.c:4105
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__map_kernel_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
  - arch/powerpc/mm/hugetlbpage.c:huge_pte_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vmap_page_range_noflush
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
c0000000003c38e0-c0000000003c39f8: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000209748)
Location: mm/memory.c:4105
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffe000209748-ffffffe000209812: __pmd_alloc (STB_GLOBAL)
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
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125ad60)
Location: mm/memory.c:4105
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8125ad60-ffffffff8125aecd: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124d0f0)
Location: mm/memory.c:4105
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff8124d0f0-ffffffff8124d204: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81258b00)
Location: mm/memory.c:4105
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81258b00-ffffffff81258c6d: __pmd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __pmd_alloc(struct mm_struct *mm, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81268500)
Location: mm/memory.c:4105
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/userfaultfd.c:mm_alloc_pmd
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81268500-ffffffff8126866b: __pmd_alloc (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
