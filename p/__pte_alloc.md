# Function: <code>__pte_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bd230)
Location: mm/memory.c:564
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__get_locked_pte
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff811bd230-ffffffff811bd39d: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d8000)
Location: mm/memory.c:576
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff811d8000-ffffffff811d8110: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e7cd0)
Location: mm/memory.c:578
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff811e7cd0-ffffffff811e7dd7: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f2e70)
Location: mm/memory.c:643
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff811f2e70-ffffffff811f2f77: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81209fd0)
Location: mm/memory.c:645
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81209fd0-ffffffff8120a0e5: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122adf0)
Location: mm/memory.c:660
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8122adf0-ffffffff8122af0c: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123e1b0)
Location: mm/memory.c:403
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8123e1b0-ffffffff8123e2c1: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124fa10)
Location: mm/memory.c:405
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8124fa10-ffffffff8124fb26: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125dfb0)
Location: mm/memory.c:405
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8125dfb0-ffffffff8125e0c6: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128dd50)
Location: mm/memory.c:423
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8128dd50-ffffffff8128de60: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812989d0)
Location: mm/memory.c:425
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812989d0-ffffffff81298b00: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129e0f0)
Location: mm/memory.c:437
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8129e0f0-ffffffff8129e23d: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812df330)
Location: mm/memory.c:436
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812df330-ffffffff812df47b: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8133f940)
Location: mm/memory.c:466
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pages
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8133f940-ffffffff8133f9d9: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b7880)
Location: mm/memory.c:419
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pages
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff813b7880-ffffffff813b7919: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ec630)
Location: mm/memory.c:438
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
**Symbols:**

```
ffffffff813ec630-ffffffff813ec6c9: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81417e70)
Location: mm/memory.c:438
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/mremap.c:move_page_tables
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
**Symbols:**

```
ffffffff81417e70-ffffffff81417f20: __pte_alloc (STB_GLOBAL)
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
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f5a10)
Location: mm/memory.c:405
Inline: False
Direct callers:
  - arch/arm64/mm/hugetlbpage.c:huge_pte_alloc
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffff8000102f5a10-ffff8000102f5b90: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c05177cc)
Location: mm/memory.c:405
Inline: False
Direct callers:
  - arch/arm/mm/pgd.c:pgd_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
c05177cc-c0517950: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bcf20)
Location: mm/memory.c:405
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
c0000000003bcf20-c0000000003bd0d8: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000206ddc)
Location: mm/memory.c:405
Inline: False
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffe000206ddc-ffffffe000206ee8: __pte_alloc (STB_GLOBAL)
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
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256600)
Location: mm/memory.c:405
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81256600-ffffffff81256716: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81249040)
Location: mm/memory.c:405
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pte_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81249040-ffffffff8124912f: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812543a0)
Location: mm/memory.c:405
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812543a0-ffffffff812544b6: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __pte_alloc(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81263e30)
Location: mm/memory.c:405
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81263e30-ffffffff81263f50: __pte_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, vma, pmd, address</code> ➡️ <code>mm, pmd, address</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
</ul>
</details>
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
